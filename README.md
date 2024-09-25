## 📝 서비스 소개

사용자는 Pill-Buddy 를 통해 매일 복용해야 할 약이나 영양제를 등록하고, 복용 시간에 맞춰 알림을 받을 수 있습니다. <br> 또한 사용자는 보호자를 추가하여 약 복용 여부를 확인하고 관리할 수 있습니다.

마지막으로 [식품의약품안전처](https://www.mfds.go.kr/index.do)의 공공 API 를 통해 사용자는 약의 주요 정보들을 조회할 수 있습니다.

<br>

## 👬 팀원 소개
|                                        Backend                                         |                           Backend                            |                           Backend                            |                           Backend                            |                           Backend                            |
|:--------------------------------------------------------------------------------------:|:-------------------------------------------------------------:|:-------------------------------------------------------------:|:-------------------------------------------------------------:|:-------------------------------------------------------------:|
| ![진우](https://github.com/user-attachments/assets/43b44089-e9a1-4e6a-89a1-b1bc9a8e8a4a) | ![홍제](https://github.com/user-attachments/assets/6ab12390-7dd5-46c7-88dd-b808a86de5dd) | ![성겸](https://github.com/user-attachments/assets/d12b5ad8-95b9-4e1c-a207-e99a7a123e38) | ![현우](https://github.com/user-attachments/assets/7e75a7a3-d77b-44bd-8dcb-080378caf6e9) | ![소희](https://github.com/user-attachments/assets/b729e0e6-2724-471f-b544-a31e46d0a0d6) |
|                        [이진우 (팀장)](https://github.com/jinw0olee)                        |      [안홍제](https://github.com/hongjeZZ)      |      [김성겸](https://github.com/xxxkyeom)      |      [신현우](https://github.com/Dia2Fan)      |      [양소희](https://github.com/MisaSohee)      |


<br>

## 🌱 Team Convention

| Tag Name | Description |
| --- | --- |
| feat | 새로운 기능을 추가할 때 사용 |
| fix | 버그를 수정할 때 사용 |
| style | 코드 포맷 변경, 세미콜론 누락 등 로직 변경이 없는 경우 사용 |
| refactor | 프로덕션 코드를 리팩토링할 때 사용 |
| comment | 주석을 추가하거나 변경할 때 사용 |
| docs | 문서를 수정할 때 사용 |
| test | 테스트 코드 작성, 리팩토링, 실제 코드 변경 없이 테스트만 추가할 때 사용 |
| chore | 빌드 업무 수정, 패키지 매니저 수정 등, 실제 코드 변경이 없는 경우 사용 |
| rename | 파일 또는 폴더명을 수정하거나 이동할 때 사용 |
| remove | 파일 삭제 작업만 수행할 때 사용 |

<br>

- Commit 시 `Tag Name` 은 소문자로 통일합니다. (Feat -> feat, Docs -> docs)
  ```text
  feat: 회원 가입 기능 구현
  
  SMS, 이메일 중복 확인 API 개발
  ```
- branch 이름은 목적에 따라 `tag name + 기능명` 으로 작성합니다.
  ```text
  feat/get-notification, fix/sms-notification-bug
  ```
- Pull Request 이름은 `{이슈번호}:[FEAT] {기능}` 으로 작성합니다.
  ```
  1:[FEAT] 알림 정보 조회 API 구현
  ```
- Issue 이름은 `[FEAT] {기능}` 으로 작성합니다.
  ```
  [FEAT] 알림 정보 조회 API 구현
  ```
