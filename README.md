

# ERICA LIFE

## 1. 프로젝트 소개
ERICA LIFE는 한양대학교 ERICA 학생들을 위한 캠퍼스 생활 정보 안내 웹사이트입니다.

학교 시설, 맛집과 카페, 공부 및 휴식 공간 등의 정보를 카테고리별로 제공합니다.

## 2. 프로젝트 목표
- 신입생에게 유용한 캠퍼스 정보 제공
- 카테고리별 정보 분류를 통한 이용 편의성 향상
- HTML5와 CSS3를 활용한 웹사이트 제작
- GitHub를 활용한 팀 협업

## 3. 팀원 및 역할

| 팀원 | 역할 | 담당 작업 |
|---|---|---|
| 손재홍 | 팀장·품질 관리 | 메인 페이지, 시설 안내, 오류 점검 |
| 김민성 | 문서·배포 | README, 맛집·카페, GitHub Pages 배포 |
| 김윤희 | 디자인 | 와이어프레임, 공부·휴식, CSS |

## 4. 주요 페이지
- 메인 홈페이지
- 캠퍼스 시설 안내
- 맛집·카페 안내
- 공부·휴식 공간 안내

## 5. 사용 기술
- HTML5
- CSS3
- Git / GitHub
- GitHub Pages

## 6. 프로젝트 폴더 구조

```text
ERICA-LIFE/
├── index.html
├── pages/
│   ├── facilities.html
│   ├── food.html
│   └── study-rest.html
├── css/
│   └── style.css
├── images/
│   └── wireframe.jpg
└── README.md
```

## 7. 진행 계획
- M1: 프로젝트 기획 및 기본 구조 작성
- M2: HTML 콘텐츠 작성 및 CSS 적용
- M3: 반응형 디자인 완성 및 GitHub Pages 배포

## 8. 이미지 출처
사용한 이미지의 출처를 기록하고, 직접 촬영한 이미지는 별도로 표시합니다.

## 9. AI 활용 내역
- 사용 도구: ChatGPT
- 활용 내용: README 및 HTML 코드 초안 작성 지원
```



<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>맛집·카페 | ERICA LIFE</title>
  <link rel="stylesheet" href="../css/style.css">
</head>

<body>
  <header>
    <h1>ERICA LIFE</h1>
    <p>한양대학교 ERICA 캠퍼스 생활 가이드</p>
  </header>

  <nav aria-label="주요 메뉴">
    <ul>
      <li><a href="../index.html">홈</a></li>
      <li><a href="facilities.html">시설 안내</a></li>
      <li><a href="food.html">맛집·카페</a></li>
      <li><a href="study-rest.html">공부·휴식</a></li>
    </ul>
  </nav>

  <main>
    <section>
      <h2>맛집·카페 안내</h2>
      <p>한양대학교 ERICA 캠퍼스 내외의 식당과 카페를 소개합니다.</p>
    </section>

    <section>
      <h2>교내 식당</h2>
      <p>교내 식당의 위치와 메뉴, 이용 정보를 안내합니다.</p>
    </section>

    <section>
      <h2>주변 맛집</h2>
      <p>학교 주변 음식점의 특징과 이용 정보를 소개합니다.</p>
    </section>

    <section>
      <h2>카페</h2>
      <p>캠퍼스 내외에서 공부하거나 휴식하기 좋은 카페를 소개합니다.</p>
    </section>
  </main>

  <footer>
    <p>© 2026 ERICA LIFE</p>
  </footer>
</body>
</html>
