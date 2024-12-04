![TODO](https://github.com/user-attachments/assets/04299f64-c06e-41eb-910c-77277d45dc87)


# 📝 작업 관리 애플리케이션  

![License Badge](https://img.shields.io/badge/license-MIT-blue)  
![Python Badge](https://img.shields.io/badge/language-Python-green)  
![Status Badge](https://img.shields.io/badge/status-Active-brightgreen)  

**간단한 CLI(명령줄 인터페이스)로 할 일을 효율적으로 관리하세요!**

---

## 📖 프로젝트 설명  
이 프로젝트는 Python을 기반으로 한 **작업 관리 애플리케이션**입니다.  
사용자는 새로운 작업을 추가하고, 목록을 확인하며, 작업을 완료 처리하거나 삭제할 수 있습니다.  

작업은 JSON 파일에 저장되어 프로그램을 종료하고 다시 실행해도 작업 데이터가 유지됩니다.  
또한, 작업 상태(`완료`, `미완료`)를 확인할 수 있어 진행 상황을 손쉽게 추적할 수 있습니다.  

---

## 🐤 데모  

아래는 애플리케이션 실행 화면 예시입니다:  

```plaintext
작업 관리 애플리케이션
1. 할 일 추가  
2. 할 일 목록 보기  
3. 할 일 완료  
4. 할 일 삭제  
5. 종료  

원하는 작업을 선택하세요 (1~5):
```

---

## ⭐ 주요 기능  
- **할 일 추가**: 새로운 작업을 추가합니다.  
- **할 일 목록 보기**: 등록된 작업과 완료 여부를 확인합니다.  
- **완료 처리**: 작업 상태를 `완료`로 변경합니다.  
- **작업 삭제**: 더 이상 필요하지 않은 작업을 삭제합니다.  
- **데이터 영구 저장**: JSON 파일(`tasks.json`)을 사용해 작업 데이터를 저장합니다.  

---

## 💻 시작하기  

### 설치  
1. 이 저장소를 클론합니다:  
   ```bash
   git clone https://github.com/yourusername/task-manager.git
   cd task-manager
   ```

2. Python을 설치합니다(버전 3.6 이상 권장).

### 애플리케이션 실행  
Python으로 스크립트를 실행합니다:  
```bash
python task_manager.py
```

### 사용 예시  
1. 새로운 작업을 추가합니다.  
2. 작업 목록을 확인합니다.  
3. 작업을 완료 처리하거나 삭제합니다.  
4. 프로그램 종료 후에도 작업 데이터는 저장됩니다.  

---

## 🔧 기술 스택  
- **언어**: Python  
- **파일 형식**: JSON을 사용한 데이터 저장  

---

## 📂 프로젝트 구조  

```plaintext
task_manager/
├── task_manager.py  # 메인 스크립트
├── tasks.json       # 데이터 저장 파일
└── README.md        # 프로젝트 문서
```

---

## ⚒ 개발 과정  

1. **JSON 파일 기반 데이터 저장**: 작업 데이터를 `tasks.json` 파일에 저장하고 불러옵니다.  
2. **동적 사용자 입력 처리**: 메뉴 옵션에 따라 작업 추가, 보기, 완료 처리, 삭제 등의 기능을 제공합니다.  
3. **에러 처리**: 잘못된 입력에 대해 적절한 오류 메시지를 출력해 사용자 경험을 향상시켰습니다.  

---

## 👨‍💻 역할 및 기여  

- **개발자**: [Your Name]  
    - CLI 기반 작업 관리 애플리케이션 설계 및 구현.  
    - JSON을 이용한 데이터 영구 저장 구현.  
    - 직관적인 메뉴 옵션 및 사용자 인터페이스 구성.  

---

## 👨‍👩‍👧‍👦 개발자  

- [Your Name](https://github.com/yourusername)  

---

이 프로젝트는 Python과 JSON 데이터 관리를 학습하는 초보자 또는 간단한 오프라인 작업 관리 도구를 찾는 사용자에게 적합합니다. 🚀

