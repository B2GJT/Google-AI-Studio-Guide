# Google AI Studio 설정법 가이드

## 개요

Google AI Studio의 UI 업데이트에 따라 달라진 인터페이스 설정법을 수강생에게 안내하기 위한 웹 페이지 가이드입니다.

기존 노션 문서 형태로 제공하던 가이드를 수강생 접근성 향상을 위해 웹 페이지로 전환하였습니다.

- **대상:** 패스트캠퍼스 Google AI Studio 관련 과정 수강생
- **기준 버전:** Google AI Studio (2026년 2월 27일 기준)

---

## 페이지 구성

| 섹션 | 내용 |
|------|------|
| 1 | Google AI Studio 로그인 |
| 2 | Google AI Studio 메뉴 소개 |
| 3 | Playground에서 나노바나나 모델 선택 |
| 4 | Playground - Nano Banana 메뉴 안내 |
| 5 | Playground - Nano Banana 참고 사항 |

- **디자인:** Mintlify 스타일 기반 단일 HTML 파일 (외부 프레임워크 없음)
- **구조:** 상단 네비바 + 좌측 목차 사이드바 + 본문

---

## 파일 구조

```
Google-AI-Studio-Guide/
├── index.html        # 가이드 본문
└── images/
    ├── image 1.png   # 로그인 화면
    ├── image 2.png   # 메뉴 소개 화면
    ├── image 3.png   # Playground 모델 선택 화면
    ├── image 4.png   # Nano Banana 메뉴 안내 화면
    ├── image 5.png   # 참고 사항 화면
    └── image.png     # 기타 참고 이미지
```

---

## 수강생 배포 방법

GitHub Pages를 통해 URL을 생성하고 수강생에게 공유합니다.

### GitHub Pages 활성화 절차

1. 이 저장소의 **Settings** 탭 클릭
2. 좌측 메뉴에서 **Pages** 선택
3. **Branch** 항목에서 `main` 선택 후 **Save**
4. 잠시 후 아래 URL로 배포 완료

### 수강생 공유 URL

```
https://b2gjt.github.io/Google-AI-Studio-Guide/
```

---

## 업데이트 방법

Google AI Studio UI가 변경되어 가이드 수정이 필요한 경우:

- **이미지 교체:** `images/` 폴더 내 해당 파일을 같은 이름으로 덮어쓴 후 push
- **본문 내용 수정:** `index.html` 수정 후 push
- push 후 수 분 내에 배포 URL에 자동 반영됩니다.
