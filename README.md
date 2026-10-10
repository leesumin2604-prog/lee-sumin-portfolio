# LEE SUMIN — artist portfolio

한국화·서양화·영상 작가 이수민의 작품 아카이브입니다. HTML/CSS/JS로 만든 정적 사이트로, 유료 서버나 빌드 환경 없이 GitHub Pages에 게시할 수 있습니다.

## 2026.10 디자인 업데이트

- 이미지 중심 에디토리얼 섹션 추가: 〈축적〉과 〈싱그러운〉을 나란히 배치해 수묵과 채색의 대비를 표현합니다.
- 크림/올리브 톤의 카드 레이아웃을 유지하면서 화면의 시각적 리듬을 개선했습니다.
- 홈/작품/작가노트/영상/약력·수상/연락 내비게이션, 작품 필터·상세보기, 콘텐츠 편집 기능 유지.
- 블로그는 외부 접근이 제한되어 설명 문구를 직접 검증하지 못했습니다. 정확한 블로그 본문을 복사하지 않았습니다.
- GitHub 연결에서 조회 권한은 확인됐지만 파일 쓰기 API는 403을 반환했습니다. 현재는 수동 업로드가 필요합니다.

## 바로 보기

`index.html`을 브라우저에서 여세요. GitHub Pages 배포 후에는 공개 URL로 볼 수 있습니다.

## GitHub Pages 배포

1. GitHub에서 **Public** 저장소를 만드세요. 추천 이름: `lee-sumin-portfolio`.
2. 이 ZIP의 **압축을 풀고 내부의 모든 파일과 assets 폴더**를 저장소 최상단(root)에 업로드한 다음 `Commit changes`를 누르세요. ZIP 파일 자체를 업로드하는 게 아닙니다.
3. 저장소 → **Settings → Pages → Build and deployment** → Source: **Deploy from a branch** → Branch: **main**, Folder: **/(root)** → **Save**.
4. GitHub Pages는 보통 수 분 후 `https://leesumin2604-prog.github.io/lee-sumin-portfolio/` 형태의 주소를 제공합니다. 실제 주소는 GitHub Pages 설정 화면에서 확인하세요. (이 URL은 배포 전 예시입니다.)
5. 사이트의 공개 여부와 모든 사진·이력·연락처를 확인한 뒤 외부 공유하세요.

> 연결된 GitHub 도구에 저장소 생성 및 Pages 설정 변경 권한이 없어, 사용자가 저장소 생성/Pages 활성화를 직접 해야 할 수 있습니다.

## 웹에서 내용 편집 (코드 몰라도 됨)

1. 게시한 사이트 주소 뒤에 `/studio.html`을 붙여 여세요. 이 화면은 비밀번호가 필요 없는 **클라이언트 편집기**입니다. 누구나 열어볼 수 있어도 **GitHub 저장소 쓰기 권한 없이는 실제 게시를 변경할 수 없습니다**.
2. 작품·약력·작가 노트·수상·전시 내용을 입력합니다. `임시 저장`은 해당 브라우저의 임시 데이터에만 보존됩니다.
3. `미리 보기`를 누르면 공개 화면과 구분된 미리보기가 열립니다.
4. `content.js 다운로드`를 누르고, GitHub 웹사이트에서 저장소의 기존 `content.js`를 새 파일로 교체한 다음 Commit 합니다.
5. 실제 공개 변경사항은 GitHub Pages 재배포 후 반영됩니다. **임시 저장만으로는 공개 사이트가 바뀌지 않습니다.**

### GitHub 자체 편집

저장소의 `content.js` 파일에 있는 연도·작품 설명·문단을 GitHub 편집 기능으로 고치고 Commit할 수도 있습니다. 이미지를 교체하려면 `assets/`에 같은 이름으로 다시 올리거나, 새 파일을 업로드해 `content.js`의 `image`/`thumbnail` 경로를 변경하세요.

### 추가 가능 내용

- 실제 전시 이력은 아직 등록되지 않았습니다. 허위 전시 정보를 넣지 않았고, 편집 화면에서 추가할 수 있습니다.
- 작가 블로그 본문은 외부 열람이 제한되어 블로그의 작품 설명을 복사하지 않았습니다. 작품 설명은 업로드한 작가 포트폴리오와 자기소개서, 작업 개념을 토대로 마련한 편집 가능한 초안입니다.
- 〈밤거리〉는 원본 파일에 제작연도·재료·크기가 없어 미확정 상태입니다.
- 2023년 서양화 3점은 전달된 서양화 PPTX의 원본 미디어에서 다시 추출했습니다. 〈금토일금토일금토일〉은 캔버스/돌 이미지를 하나의 기록 이미지로 함께 배치했습니다. 나머지 회화 10점은 이번에 다시 업로드한 원본으로 교체했습니다.
- 작품 이미지와 영상의 저작권은 작가에게 있습니다. 공개 전 외부 사용 가능성을 확인하세요.

## 파일 설명

- `index.html` : 공개 홈페이지
- `style.css` : 사이트 디자인
- `app.js` : 작품 목록, 필터 및 상세보기
- `content.js` : 편집 가능한 실제 공개 작품 데이터와 글
- `studio.html`, `studio.css`, `studio.js` : 콘텐츠 편집 도구
- `assets/*.webp` : 작품 원본 기반 고화질 이미지 및 목록용 이미지
- `assets/dream-ideal-reality.mp4` : 웹용으로 최적화된 90초 영상
- `.nojekyll` : GitHub Pages 파일 처리용

## 정보 정확성

수상 경력은 첨부된 대학원 자기소개서·수학계획서에 기재된 정보를 바탕으로 정리했습니다. 확인되지 않은 전시/학력을 임의로 추가하지 않았습니다.

## 작가 블로그 기록 9개

사용자가 직접 제공한 블로그 링크 9개를 홈페이지의 「작업 기록 / JOURNAL」에 연결했습니다. 네이버 외부 페이지의 본문을 검증할 수 없어 실제 게시글 제목을 추정하지 않고 `작업 기록 01~09`로 표시합니다.

홈페이지 브랜드 표기는 `LEE SUMIN`으로 통일했습니다. GitHub 커넥터의 `create_file` API가 여전히 HTTP 403을 반환하여 저장소 자동 업로드는 완료되지 않았습니다.


## 2025 Louvre exhibition archive / 전시 기록

The exhibition gallery section includes photographs of the **IAP International Art Exhibition 2025, Le Carrousel du Louvre** and supporting documentation for the exhibited artwork 〈싱그러운〉, plus separate materials relating to the 2024 Louvre competition. Exhibition photographs and event videos were supplied by the artist.

To edit the photos, open `studio.html` → **전시 사진 편집**. Edit titles, captions, year and image path or reorder photos, then click **content.js 다운로드**. Upload the downloaded `content.js` to the repository root on GitHub and commit the changes.

To add photos, first upload images to `assets/`. Reference them as `assets/filename.webp` in the editor. Video references are in the `exhibitionVideos` array of `content.js` and videos live in `assets/`. The studio editor is not authenticated and does not publish automatically; only a GitHub commit updates the public page.

On GitHub, preserve the `assets/` directory in the repository **root**. Do not upload images alone into the root. The files `index.html`, `app.js`, `style.css`, `studio.html`, `studio.js`, `studio.css`, and `content.js` must all remain in the root.
