
# ERICA LIFE

## 1. 프로젝트 소개
ERICA LIFE는 한양대학교 ERICA 학생들을 위한
캠퍼스 생활 정보 안내 웹사이트입니다.

학교 시설, 맛집과 카페, 공부 및 휴식 공간 등의
정보를 한눈에 확인할 수 있도록 제작합니다.

## 2. 프로젝트 목표
- 신입생에게 유용한 캠퍼스 정보 제공
- 다양한 생활 정보를 카테고리별로 정리
- HTML과 CSS를 활용한 웹사이트 제작
- GitHub를 통한 팀 협업 경험

## 3. 팀원 및 역할
| 팀원 | 역할 | 담당 작업 |
|---|---|---|
| 손재홍 | 팀장·품질 관리 | 메인, 시설, 오류 점검 |
| 김민성 | 문서·배포 | README, 맛집·카페, 배포 |
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
index.html
pages/
css/
images/
README.md

## 7. 진행 계획
- M1: 기본 구조 및 기획
- M2: 콘텐츠와 CSS 제작
- M3: 최종 완성 및 배포

## 8. 이미지 출처
추후 실제 사용 이미지와 출처를 기록합니다.

## 9. AI 활용 내역
실제 AI 사용 도구와 용도를 기록합니다.
```

팀원 이름이나 실제 페이지 구성은 팀에서 확정한 정보로 바꾸세요. 특히 AI 활용 내역은 실제 사용한 내용만 작성해야 합니다.

## STEP 4. README 커밋하기

README를 수정했다면 다음과 같이 입력합니다.

<box background="surface-secondary" radius="lg" padding={3} gap={2}>
  <text color="secondary" size="xs">Commit message</text>
  <row align="center" justify="between">
    `docs: README 프로젝트 소개 및 팀원 역할 작성 (#3)`
    <button size="xs" variant="outline" color="secondary" onClick={()=>GenUI.copy("docs: README 프로젝트 소개 및 팀원 역할 작성 (#3)")}>
      <icon name="copy" size="xs"/>
    </button>
  </row>
</box>

`#3`은 실제 이슈 번호가 3번일 때만 사용합니다. GitHub에 생성된 이슈 번호가 다르면 그 번호로 변경하세요.

협업 기록을 위해서는 **새 브랜치에서 수정하고 PR을 만들어 리뷰받는 방식**을 권장합니다. GitHub 파일 편집 화면의 커밋 옵션에서 새 브랜치를 선택할 수 있다면 그 방식을 사용하세요.

# 4. 맛집·카페 HTML 파일 만들기

이번 주에는 B도 본인 HTML 파일을 만들고 첫 커밋을 남기는 것이 좋습니다.

## STEP 5. food.html 만들기

팀 저장소에서 본인 작업용 브랜치를 선택한 뒤 다음 순서로 진행합니다.

1. `Code` 탭으로 이동합니다.
2. `Add file → Create new file`을 클릭합니다.
3. 파일 이름에 `pages/food.html`을 입력합니다.
4. 아래 HTML 코드를 복사합니다.
5. `Commit changes`로 저장합니다.

<CodeBlock language="html" editable>
<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport"
        content="width=device-width, initial-scale=1.0">
  <title>맛집·카페 | ERICA LIFE</title>
  <link rel="stylesheet" href="../css/style.css">
</head>

<body>
  <header>
    <h1>ERICA LIFE</h1>
  </header>

  <nav aria-label="주요 메뉴">
    <ul>
      <li><a href="../index.html">홈</a></li>
      <li><a href="facilities.html">시설</a></li>
      <li><a href="food.html">맛집·카페</a></li>
      <li><a href="study-rest.html">공부·휴식</a></li>
    </ul>
  </nav>

  <main>
    <section>
      <h2>맛집·카페 안내</h2>
      <p>ERICA 캠퍼스에서 이용할 수 있는
         식당과 카페를 소개합니다.</p>
    </section>

    <section>
      <h2>교내 식당</h2>
      <p>교내 식당의 메뉴와 이용 정보를 정리합니다.</p>
    </section>

    <section>
      <h2>주변 맛집</h2>
      <p>학교 주변 음식점을 소개합니다.</p>
    </section>

    <section>
      <h2>카페</h2>
      <p>공부와 휴식에 좋은 카페를 소개합니다.</p>
    </section>
  </main>

  <footer>
    <p>© 2026 ERICA LIFE</p>
  </footer>
</body>
</html>
