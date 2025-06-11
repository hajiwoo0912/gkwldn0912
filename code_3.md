# .gitignore 사용 및 예외 설정

## 1. .gitignore 파일 생성

```bash
touch .gitignore
```

➡️ Git이 무시할 파일 목록을 설정할 수 있는 .gitignore 파일을 생성합니다.

---

## 2. 무시할 파일 예시 작성

```plaintext
*.log
node_modules/
.DS_Store
```

➡️ 특정 확장자, 폴더, 숨김 파일 등을 무시할 수 있습니다.

---

## 3. 이미 트래킹 중인 파일 무시하기

```bash
git rm --cached 파일명
```

➡️ 이미 Git에 올라간 파일은 강제로 제거 후 무시해야 적용됩니다.
