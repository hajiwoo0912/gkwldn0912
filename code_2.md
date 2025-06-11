# Git 브랜치 생성 및 전환

## 1. 브랜치 목록 보기

```bash
git branch
```

➡️ 현재 로컬 저장소에 존재하는 브랜치들을 확인합니다.

---

## 2. 새 브랜치 생성

```bash
git branch feature-branch
```

➡️ 'feature-branch'라는 이름의 새 브랜치를 생성합니다.

---

## 3. 브랜치 전환

```bash
git checkout feature-branch
```

➡️ 해당 브랜치로 이동하여 작업을 시작할 수 있습니다.

---

## 4. 생성과 전환 동시에

```bash
git checkout -b new-branch
```

➡️ 브랜치를 만들고 즉시 그 브랜치로 전환합니다.
