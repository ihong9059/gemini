# 사이드바 설정

사이드바는 웹사이트의 내비게이션 메뉴 역할을 합니다. `_sidebar.md` 파일을 생성하고 설정하여 사이드바를 꾸밀 수 있습니다.

### 1. 사이드바 활성화

먼저 `index.html` 파일에서 `loadSidebar` 옵션을 `true`로 설정해야 합니다.

```html
<script>
  window.$docsify = {
    loadSidebar: true
  }
</script>
```

### 2. `_sidebar.md` 작성

프로젝트의 루트 폴더에 `_sidebar.md` 파일을 생성하고, 목록과 링크 형태로 메뉴를 구성합니다.

```markdown
<!-- _sidebar.md -->

- **가이드**
  - [콘텐츠 작성하기](docsify_guide/writing-content.md)

- **시작하기**
  - [빠른 시작](getting-started.md)
```

- 들여쓰기를 사용하여 하위 메뉴를 만들 수 있습니다.
- 링크는 해당 마크다운 파일의 경로를 가리킵니다.
