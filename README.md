# Minishell

## 개요
이 프로젝트는 Linux 환경에서 C 언어를 사용하여 **Bash 쉘과 유사한 동작을 수행하는 커스텀 쉘**을 구현한 것입니다. 사용자는 기본적인 명령어 실행과 입출력, 파이프, 시그널 처리 등을 수행할 수 있습니다.

---

## 주요 기능

- **빌트인 명령어**: `cd`, `echo`, `pwd`, `export`, `unset`, `env`, `exit` 등
- **파이프(Pipe) 지원**: 여러 명령어를 파이프를 통해 연결
- **시그널 처리**: `Ctrl+C`, `Ctrl+D` 등 시그널 처리
- **환경 변수 관리**: 사용자 환경 변수 읽기/설정/삭제
- **입출력 처리 및 에러 핸들링**: 파일 리디렉션(`>`, `<`, `>>`) 및 오류 메시지 처리

---

## 사용 방법

```bash
git clone https://github.com/Dendrog/minishell.git
cd minishell
make
./minishell
```

## 실행 화면
<img width="815" height="501" alt="image" src="https://github.com/user-attachments/assets/642d1fec-6d71-4b07-bcb9-a420b7bc7e2f" />

