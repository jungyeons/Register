
# 📘 CS 프로젝트

이 저장소는 컴퓨터 과학 개념(운영체제, 네트워크, 아키텍처, 시스템 프로그래밍 등)을 이해하기 위해 만들어졌습니다.

## 📂 디렉터리 구조

```
cs-main/
├── arch/        # 아키텍처 관련 파일 (예: 인코딩 예제, 문서)
├── net/         # 네트워크 분석 파일 (PCAP 형식)
├── os/          # 운영체제 코드 예제 (C, Java, Python)
├── sql/         # 데이터베이스 조작을 위한 SQL 스크립트
├── sys/         # 시스템 프로그래밍 예제 (멀티스레딩, 파일 처리 등)
```

### 주요 디렉터리 및 파일
- **arch**:
  - `README.md`: 아키텍처 관련 주제 문서.
  - `encoding.py`: 인코딩 데모 Python 스크립트.
  - `x86-64-reference.pdf`: x86-64 아키텍처 참조 문서.

- **net**: 네트워크 패킷 캡처 파일(Pcap) 포함:
  - `3-way-handshake.pcap`: TCP 3-way 핸드셰이크 시연.
  - `fragmentation.pcapng`: IP 패킷 분할 예제.

- **os**: 운영체제 개념의 예제와 연습 문제:
  - `MultiThreadExample.java`: Java 멀티스레딩 예제.
  - `mulp*.c`: 운영체제 관련 다양한 C 프로그램.

- **sql**: SQL 스크립트:
  - `create_db_and_table.sql`: 데이터베이스 및 테이블 생성 스크립트.
  - `select.sql`: SELECT 쿼리 예제.

- **sys**: 시스템 프로그래밍 예제:
  - `file_*.c`: C 언어 파일 처리 예제.
  - `pipe_*.c`: 파이프를 사용한 프로세스 간 통신 예제.
  - `mmap_*.c`: C 언어 메모리 매핑 예제.

## 🚀 설치 방법
1. 저장소를 클론합니다:
   ```bash
   git clone https://github.com/yourusername/fastcampus-cs-main.git
   ```
2. 원하는 디렉터리로 이동하여 예제와 연습을 탐색하세요.

## 🛠️ 사용 방법
- Python 스크립트 실행:
  ```bash
  python3 script_name.py
  ```
- C 프로그램 컴파일 및 실행:
  ```bash
  gcc program.c -o program
  ./program
  ```
- Java 프로그램 컴파일 및 실행:
  ```bash
  javac Program.java
  java Program
  ```

## 🤝 기여하기
기여는 언제나 환영입니다! [GitHub 워크플로우](https://guides.github.com/introduction/flow/)를 따라 변경 사항을 제출해주세요.

## 📜 라이선스
이 프로젝트는 MIT 라이선스에 따라 라이선스가 부여됩니다. 자세한 내용은 LICENSE 파일을 참조하세요.
