# Docsify 시작하기

Docsify는 매우 간단하게 시작할 수 있습니다.

### 1. Docsify CLI 설치

`npm`을 사용하여 Docsify CLI (Command Line Interface)를 전역으로 설치합니다.

```bash
npm install -g docsify-cli
```

### 2. 프로젝트 초기화

원하는 폴더에서 아래 명령어를 실행하여 프로젝트를 초기화합니다.

```bash
docsify init ./docs
```
- `docs` 라는 폴더에 기본 파일들이 생성됩니다.

### 3. 서버 실행

프로젝트 폴더로 이동하여 서버를 실행합니다.

```bash
cd docs
docsify serve .
```

이제 브라우저에서 `http://localhost:3000`으로 접속하여 사이트를 확인할 수 있습니다.
