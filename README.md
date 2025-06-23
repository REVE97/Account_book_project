# 토이 프로젝트

# SKELETON PROJECT 가계부
<h2>2025.04.07 ~ 2025.04.11</h2>
<h2>>WEB : https://teongjangsaver.netlify.app/</h2>
<h2>>MOBILE : https://teonjang-saver.netlify.app/</h2>

# UI
![Image](https://github.com/user-attachments/assets/3106a8b7-c9fd-420e-9c99-accd6860966c)

# ERD
<img width="647" alt="Image" src="https://github.com/user-attachments/assets/3eb6b5e3-8ecf-4b59-a402-82c2d995efcb" />

<hr />

## 🧾 Git 규칙 및 협업 전략

### 1. 📌 커밋 컨벤션 (Commit Convention)

> 커밋 메시지는 다음과 같은 형식을 따릅니다:

#### 커밋 타입 예시
| 타입 | 설명 |
|------|------|
| feat | 새로운 기능 추가 |
| fix | 버그 수정 |
| docs | 문서 수정 (README 등) |
| style | 코드 포맷팅, 세미콜론 누락 등 |
| refactor | 코드 리팩토링 |
| test | 테스트 코드 추가 |
| chore | 기타 변경사항 (빌드 설정, 패키지 등) |

#### ✅ 예시:

- `feat: 가계부 수정 기능 추가`
- `fix: 가계부 수정 시 메인에 적용되지 않던 오류 해결`



### 2. 🐬 이슈 컨벤션 (Issue Convention)

> Issue 제목과 본문은 다음 형식을 따릅니다:

#### Issue 제목:
- 제목 : [feat] : 기능명
- ex) [feat] : pull request template 작성

#### PR 본문 구조 (권장)
---

> 무엇을?
> 추가하려는 기능에 대해 간결하게 설명

> 작업 상세 내용

- [ ] TODO
- [ ] TODO
- [ ] TODO

> 참고 자료



### 3. 🚀 풀 리퀘스트 컨벤션 (Pull Request Convention)

> PR 제목과 본문은 다음 형식을 따릅니다:

#### PR 제목:
- 제목 : [feat] : 기능명
- ex) [feat] : pull request template 작성

#### PR 본문 구조 (권장)
> #이슈번호

> Close #이슈번호
 
> 📑 작업 내용
> 이번 PR에서 작업한 내용 간략히 설명해주세요(이미지 첨부 가능)

> ✂️ 스크린샷 (선택)
>

> 💭 리뷰 요구사항 (선택)
> 리뷰어가 특별히 봐주었으면 하는 부분이 있다면 작성해주세요




### 4. 🌿 브랜치 전략 (Branch Strategy)
![image](https://github.com/user-attachments/assets/bbaaa52d-83a9-4451-88c2-cfdad7de0d23)

#### 브랜치 종류
| 브랜치명 | 설명 |
|----------|------|
| `main` | 제품 릴리즈용 안정 버전 |
| `feat/` | 새로운 기능 개발용 |
| `fix/` | 버그 수정용 브랜치 |
| `hotfix/` | 운영 중 긴급 수정 |
| `refactor/` | 코드 구조 개선 |

#### 브랜치 이름 규칙 예시:
- `feat/login-page`
- `fix/typo-in-readme`
- `hotfix/login-error`
