
# GitHub SSH 연결 및 Git 사용 정리

## 1. SSH 키 생성

```bash
ssh-keygen -t ed25519 -C "your_email@example.com"
```

➡️ SSH 키를 생성하는 명령어입니다.

---

## 2. 공개키 확인 및 등록

```bash
cat ~/.ssh/id_ed25519.pub
```

➡️ 생성한 공개키를 GitHub에 등록합니다.

---

## 3. Git 저장소 초기화

```bash
git init
git remote add origin git@github.com:username/repo.git
```

➡️ Git 저장소를 만들고 원격 저장소를 연결합니다.

---

## 4. 커밋

```bash
git add .
git commit -m "처음 커밋"
```

➡️ 변경된 파일을 저장하고 설명을 붙입니다.

---

## 5. 푸시

```bash
git push -u origin main
```

➡️ 작성한 커밋을 GitHub 저장소에 올립니다.
