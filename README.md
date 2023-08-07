SEB_45_Team_023_pre_project!

# Project Name


## Features



## Contributors

-FE: 이인우, 이종범, 정회엽  
-BE: 김호빈, 박정우, 임한준

## Project Wiki

# Git 브랜치명 규칙과 커밋 메시지 컨벤션

## Git 브랜치명 규칙

프로젝트의 팀원들은 아래와 같은 Git 브랜치명 규칙을 따라 브랜치를 관리합니다. 이 규칙은 팀원들이 브랜치를 일관성 있게 생성하고 관리하여 협업을 원할하게 하도록 도와줍니다.

## 기본 브랜치 

● 메인 브랜치 : 'main'
● 개발 브랜치 : 'dev'

## 개발 브랜치 

● BE 개발 브랜치 : 'beDev'
● FE 개발 브랜치 : 'feDev'

## 기능 브랜치 

● BE 기능 브랜치 : 'be/[타입]/[기능 이름]/[#이슈번호]' 
-예시 : 'be/feat/login/#1'
● FE 기능 브랜치 : 'fe/[타입]/[기능 이름]/[#이슈번호]'
-예시 : 'fe/feat/login/#1'

## Commit Message Convention

프로젝트의 커밋 메시지를 일관성 있고 명확하게 작성하기 위해 아래와 같은 구조로 커밋 메시지를 작성합니다. 이 Convention은 각각의 커밋이 어떤 작업을 수행하는지를 명확히 전달하여 협업과 버전 관리를 원활하게 합니다.

## 구조 

[타입]: 제목 (필수)

[본문] (옵션)

## 타입 및 Emonji 

● feat ✨ :sparkles: - 새로운 기능 추가
● fix 🐛 :bug: - 버그 수정
● design 📱 :iphone: - 사용자 UI 디자인 변경
● style 🎨 :art: - 코드 포맷 변경, 세미 콜론 누락, 코드 수정 없음
● refactor ♻️ :recycle: - 프로덕션 코드 리팩토링
● comment 💡 :bulb: - 주석 추가 및 변경
● docs 📝 :memo: - 문서 수정
● test ✅ :white_check_mark: - 테스트 추가 또는 리팩토링
● chore 🏗️ :truck: - 파일이나 폴더명 변경, 이동 작업만
● rename 🚚 :truck: - 파일이나 폴더명 변경, 이동 작업만
● remove ➖ :heavy_minus_sign: - 파일 삭제 작업만
● !BREAKING CHANGE 👽️ :alien: - 커다란 API 변경
● !HOTFIX 🔥 :fire: - 급하게 치명적인 버그 수정

## 커밋 예시

✨ feat: 검색 기능 추가 #1(이슈 번호 작성)
- 변경 사항 1
- 변경 사항 2 // 본문은 필요에 따라 작성

## 주의사항

● 커밋 메시지는 명료하고 간결하게 작성하는 것이 좋습니다.
● 커밋 타입과 내용을 일광성 있게 작성하여 프로젝트의 커밋 로그를 쉽게 읽을 수 있도록 합니다.
● 이슈를 참조하는 경우 이슈 번호를 커밋 메시지에 포함시키는 것이 유용합니다. 이를 통해 이슈와 관련되 커밋을 추적할 수 있습니다.
