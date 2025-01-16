# 해커 노트북 설정 가이드 (MacOS)

이 레포지토리는 Apple Silicon MacOS 컴퓨터에서 해킹 환경을 설정하기 위한 가이드입니다. 초보자 또는 다양한 해킹 도구를 효율적으로 탐색하려는 사용자를 위해 간단한 체크리스트를 통해 초기 설정 과정을 간소화하고 설정 관련 리소스를 줄이기 위해 제작되었습니다.

---

## 목적
이 가이드는 다음을 목표로 합니다:
- 초보 사용자가 필수 해킹 도구를 설치할 수 있도록 지원.
- 효율적인 설정을 위한 체크리스트 제공.
- 환경 수동 설정의 부담을 줄임.

---

## 추천 도구 분류 및 주요 기능

| 분류               | 도구명            | 기능                              |
|--------------------|------------------|-----------------------------------|
| 시스템 및 개발 도구 | Terminal         | macOS 명령줄 인터페이스.          |
| 시스템 및 개발 도구 | Homebrew         | 패키지 관리 도구.                 |
| 시스템 및 개발 도구 | Visual Studio Code | 코드 편집기.                      |
| 시스템 및 개발 도구 | C                | 시스템 프로그래밍 언어.           |
| 시스템 및 개발 도구 | Python           | 범용 프로그래밍 언어.             |
| 시스템 및 개발 도구 | Docker           | 컨테이너 기반 가상화 도구.        |
| 네트워크 도구       | Shodan           | 네트워크 장치 검색 도구.          |
| 네트워크 도구       | Censys           | 공개 네트워크 검색 도구.          |
| 네트워크 도구       | Nmap             | 네트워크 포트 스캐너.             |
| 네트워크 도구       | RustScan         | 빠른 포트 스캐너.                 |
| 네트워크 도구       | Wireshark        | 패킷 분석 도구.                   |
| 익스플로잇(PWN)     | Gdb              | 디버깅 도구.                      |
| 익스플로잇(PWN)     | pwndbg           | Gdb 확장 플러그인.                |
| 익스플로잇(PWN)     | gef           | Gdb 확장 플러그인.                |
| 익스플로잇(PWN)     | pwndbg           | Gdb 확장 플러그인.                |
| 웹 테스트 도구      | Burp Suite       | 웹 애플리케이션 테스트 도구.      |
| 웹 테스트 도구      | OWASP ZAP        | 웹 보안 테스트 도구.              |
| 웹 테스트 도구      | Fiddler          | HTTP 트래픽 디버깅 도구.          |
| 암호화 도구         | Sage             | 수학 및 암호화 라이브러리.        |
| 암호화 도구         | NumPy            | 데이터 분석 라이브러리.           |
| 암호화 도구         | PyCryptodome     | 암호화 라이브러리.                |
| 암호화 도구         | CyberChef        | 데이터 변환 도구.                 |
| 리버스 엔지니어링    | IDA              | 바이너리 분석 도구.               |
| 리버스 엔지니어링    | Ghidra           | 리버스 엔지니어링 도구.           |
| 리버스 엔지니어링    | Binary Ninja     | 바이너리 분석 및 수정 도구.       |
| 리버스 엔지니어링    | 010 Editor       | 바이너리 편집기.                  |
| 포렌식              | Autopsy          | 파일 시스템 분석 도구.            |
| 포렌식              | Volatility       | 메모리 분석 도구.                 |

---


## 작성자
**이재준** (koreant@hspace.io)  
작성일: 2025년 1월 1일

---

## 참고 사항
- 문제 해결 및 고급 설정을 위해 문서의 상세 가이드를 참고하세요.
- 최신 도구와 실습 방법을 반영하기 위해 이 레포지토리는 지속적으로 업데이트됩니다.
