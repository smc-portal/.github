# Github 사용법
GitHub Organization 작업 가이드
Organization 내에서 레포지토리를 관리하고 브랜치 작업을 수행하는 표준 절차입니다.

---

1. 레포지토리 생성 및 클론
1. Organization 페이지에서 New repository를 클릭하여 생성합니다.

2. 터미널을 열고 로컬 환경으로 클론합니다.

```

git clone [의심스러운 링크 삭제됨]

cd Repository-Name

```


2. 새 브랜치 생성 및 이동
   새로운 기능을 구현하거나 문서를 수정할 때는 별도의 브랜치를 사용합니다.

```

# 브랜치 생성 및 이동

git checkout -b feature/organization-guide

```

3. 변경 사항 작성 및 커밋
   파일을 수정하거나 새 내용을 작성한 후 로컬 저장소에 저장합니다.

```

# 변경된 모든 파일 스테이징

git add .

# 커밋 메시지 작성

git commit -m "Docs: GitHub Organization 사용법 가이드 추가"

```

4. 원격 저장소에 Push
   작성한 브랜치를 원격(GitHub)에 업로드합니다.

```

git push origin feature/organization-guide

```

5. Pull Request 생성
   GitHub 웹사이트에서 Compare & pull request 버튼을 눌러 코드 리뷰를 요청하고 메인 브랜치에 반영합니다..