컴포넌트 구조 💥💥💥 여기 부분 저희것에 맞게 수정 예정입니다!!

<!-- Common Components: 여러 곳에서 재사용되는 공통 컴포넌트들 (e.g., 버튼, 입력 필드 등)
Feature-Specific Components: 특정 기능이나 페이지에만 사용되는 컴포넌트들
Layout Components: 페이지 레이아웃을 구성하는 컴포넌트들 (e.g., Header, Footer, Sidebar 등)
Pages: 각 페이지별로 사용되는 컴포넌트들을 해당 페이지 폴더 안에 넣어 관리  //-->

브랜치 전략

Format
branch-type/#issue-id

Rule
적절한 브랜치 생성
작업 후 해당 브랜치를 생성했던 브랜치로 PR
작업 완료된 브랜치는 삭제

Branch Type - Github Flow

https://private-user-images.githubusercontent.com/50333168/298597543-1dc87948-57cf-4b1e-94ab-13c691c2cf76.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3Mzk0MjMzOTgsIm5iZiI6MTczOTQyMzA5OCwicGF0aCI6Ii81MDMzMzE2OC8yOTg1OTc1NDMtMWRjODc5NDgtNTdjZi00YjFlLTk0YWItMTNjNjkxYzJjZjc2LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTAyMTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUwMjEzVDA1MDQ1OFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTFkODU0Yjg1ZWU0ZTYwNjIxNmY3ZjJiYWI3NTg4ZWRkODZkMmY2OTcwNzIzMjg1YzEwYzBjYTliMWU3NjVjNTEmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.z5j7A9CIqfjuZSv8Zg6MOpuqHxLdsfewRB8X0LN_7RM

브랜치명 설명 예시
main 배포용 브랜치 main
dev 통합(개발)용 브랜치 dev
feature/ 기능 개발 브랜치 feature/login
bugfix/ 버그 수정 브랜치 bugfix/nav-bar
hotfix/ 긴급 패치 브랜치 hotfix/payment
chore/ 문서, 설정파일 변경 chore/update-readme
docs/ 문서 작업 브랜치 docs/api-guide
refactor/ 리팩토링 브랜치 refactor/homepage-ui

커밋 메시지
타입 설명
feat (#이슈번호) 새로운 기능 추가
fix (#이슈번호) 버그 수정
docs (#이슈번호) 문서 수정
style (#이슈번호) 공백, 세미콜론 등 스타일 수정
refactor (#이슈번호) 코드 리팩토링
perf (#이슈번호) 성능 개선
test (#이슈번호) 테스트 추가
chore (#이슈번호) 빌드 과정 또는 보조 기능(문서 생성 기능 등) 수정
design (#이슈번호) 기능 수정 없이 스타일(CSS)만 수정

Example 💥💥💥 여기 부분도 저희것에 맞게 수정 예정

git commit -am 'feat (#189) : 게시판 작성 기능 구현'
디렉토리 구조 및 네이밍 컨벤션
디렉토리 구조
네이밍 컨벤션

1.디렉토리 및 폴더명

- 소문자로 작성하며, 카멜케이스를 사용.

  2.파일명

- 컴포넌트 파일명: PascalCase를 사용하여 작성.
- 일반 파일명: 소문자와 **하이픈(-)**을 사용하여 작성.
- 이미지파일명 : img→suffix
- boolean타입 리턴 or 함수값은 : is→prefix

  3.컴포넌트명

- PascalCase를 사용하여 작성.
- 컴포넌트 파일명과 일치시킴.

  4.CSS 클래스명

- BEM(Block Element Modifier) 규칙을 사용.

  5.상수명

- 모든 글자를 대문자로 작성하고, 단어 사이에 언더바(\_) 사용.

  6.함수명 및 변수명

- camelCase를 사용하여 작성.

  7.프로퍼티 및 메소드명 (React)

- camelCase를 사용하여 작성.
- 메소드명은 handle로 시작.
