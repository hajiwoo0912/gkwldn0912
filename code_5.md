# GitHub Pull Request 생성 및 병합

## 1. 브랜치 푸시

```bash
git push origin feature-branch
```

➡️ 작업한 브랜치를 GitHub로 푸시합니다.

---

## 2. GitHub에서 Pull Request 생성

➡️ GitHub 웹에서 "Compare & pull request" 버튼 클릭 → 설명 작성 후 PR 생성

---

## 3. Pull Request 병합

➡️ 리뷰가 끝난 후 "Merge pull request" 클릭 → "Confirm merge"로 완료

---

## 4. 병합 후 브랜치 삭제

```bash
git branch -d feature-branch
```

➡️ 로컬 브랜치를 정리합니다.
