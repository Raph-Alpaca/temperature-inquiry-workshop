# 온도센서로 나만의 탐구 앱 만들기

중학교 과학교사를 위한 PASCO PS-3201 · Gemini Canvas · Lovable 실습 안내입니다.

조승호 교사 · [raphres@sen.go.kr](mailto:raphres@sen.go.kr)

## GitHub Pages에 올리기

추천 repository 이름: **temperature-inquiry-workshop**

1. GitHub에 로그인하고 **New repository**를 누릅니다. 이름에 `temperature-inquiry-workshop`을 입력하고 **Public**, **Add README**를 선택한 뒤 **Create repository**를 누릅니다. 같은 계정에 이 이름이 이미 있다면 `temperature-inquiry-workshop-2026`처럼 다른 이름을 사용합니다.
2. 저장소의 **Code → Add file → Upload files**에서 제공받은 **index.html**을 올리고 **Commit changes**를 누릅니다. 폴더 안이 아니라 저장소 최상위에 `index.html`이 보이게 올려 주세요. 이미지와 기능 코드가 모두 포함되어 있어 이 파일 하나로 실행됩니다. 이 README는 설명서이므로 업로드하지 않아도 됩니다.
3. **Settings → Pages → Build and deployment**에서 **Source: Deploy from a branch**, **Branch: main**, **폴더: / (root)**를 선택하고 **Save**를 누릅니다.
4. 게시가 끝나면 같은 Pages 화면의 **Visit site**를 누릅니다. 주소 형식은 `https://본인아이디.github.io/temperature-inquiry-workshop/`입니다. 저장소 이름을 다르게 정했다면 주소의 마지막 부분도 달라집니다.
5. 사이트에서 3단계 이동, 캐릭터, 요청문 복사, 기능 선택과 HTML 검사를 확인합니다. 센서 실습은 연결된 시범 앱 또는 선생님이 만든 앱의 게시된 주소에서 진행합니다.

업데이트할 때는 같은 이름의 `index.html`을 다시 업로드하고 **Commit changes**를 누르면 됩니다. 게시가 바로 보이지 않으면 잠시 기다린 뒤 새로고침하고, **Actions**에서 게시 결과를 확인하세요.

## 파일 사용

- `index.html`은 이미지·스타일·기능을 모두 담은 단일 파일입니다. Chrome 또는 Edge로 직접 열어도 안내, 요청문 생성, HTML 코드 검사를 사용할 수 있습니다.
- 시범 앱·Gemini·Lovable 버튼은 온라인 서비스로 연결되므로 인터넷이 필요합니다.
- HTML 코드 검사는 파일을 브라우저에서 읽어 비교합니다. 실물 센서의 작동 여부는 별도로 확인해야 합니다.
- Gemini Pro의 무료 사용 한도와 Lovable 크레딧은 서비스 정책 및 계정에 따라 달라질 수 있습니다.

## 공식 안내 자료

2026-09-27 확인.

- [GitHub: 파일 업로드](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository)
- [GitHub: Pages 게시 위치 설정](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
- [Google: Gemini 모델 및 사용 한도](https://support.google.com/gemini/answer/16275805?hl=ko)
- [Google: Canvas로 문서와 앱 만들기](https://support.google.com/gemini/answer/16047321?hl=ko)
- [Lovable: Build 모드와 수정 범위 지정](https://docs.lovable.dev/features/agent-mode)
- [Lovable: Publish와 변경 사항 게시](https://docs.lovable.dev/features/publish)
