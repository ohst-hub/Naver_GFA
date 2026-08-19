# 네이버 GFA 매출 성장 전략 제안서

GitHub Pages에서 바로 열어볼 수 있는 **10페이지 웹 제안서**입니다.

## 파일 구성
- `index.html` : 제안서 본문
- `styles.css` : 디자인 / 반응형 / 인쇄 스타일
- `script.js` : 페이지 이동 / 목차
- `README.md` : 사용 방법

## GitHub Pages 배포 방법

1. GitHub에서 새 Repository를 생성합니다.
2. ZIP 압축을 풀고 안의 파일 4개를 Repository 최상단에 업로드합니다.
3. Repository → **Settings**
4. 왼쪽 메뉴 → **Pages**
5. `Build and deployment` → `Deploy from a branch`
6. Branch는 `main`, 폴더는 `/(root)` 선택 후 **Save**
7. 잠시 후 표시되는 GitHub Pages URL을 복사하면 제안서 링크로 사용할 수 있습니다.

보통 주소는 아래와 같은 형태입니다.

`https://아이디.github.io/저장소명/`

## 조작법
- 하단 ← → : 페이지 이동
- 키보드 ← → : 페이지 이동
- 우측 상단 `목차` : 전체 페이지 이동
- 우측 상단 `PDF 저장` : 브라우저 인쇄 기능을 이용한 PDF 출력
- URL 뒤에 `#page-3`처럼 붙이면 특정 페이지를 바로 열 수 있습니다.

## 커스터마이징
제목, 회사명, 수치, 사례 등을 수정하려면 `index.html`의 텍스트만 변경하면 됩니다.
메인 컬러는 `styles.css`의 아래 항목을 수정하면 됩니다.

```css
--green:#03c75a;
--green2:#22d978;
```

※ 본 제안서는 특정 업종에 종속되지 않는 공통 영업용 구조로 제작되었습니다.
