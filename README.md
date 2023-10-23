# 깃헙 블로그 만드는 방법

## [블로그 구축하기](https://www.youtube.com/watch?v=ACzFIAOsfpM)

* 마음에 드는 [테마](https://github.com/topics/jekyll-theme)를 선택합니다.
* Fork합니다.
  - [도큐먼트](https://mmistakes.github.io/minimal-mistakes/docs/configuration)를 꼼꼼히 확인합니다.
* Settings에서 저장소 이름을 변경합니다.
  - 반드시 이름을 "(내 계정 이름).github.io"라고 해야 합니다.
* _config.yml 파일에서 URL을 수정합니다.
  - 블로그의 주소: "https://(내 계정 이름).github.io"
  - 대부분의 설정은 여기서 할 수 있습니다.
* 테마도 변경해 볼 수 있습니다.
  - _config.yml 에 테마 있음
* 새로운 포스팅을 [생성](https://jekyllrb.com/docs/posts)합니다.
  - 저장소에서 Add file > Create new file을 선택합니다.
  - 만약 처음 포스팅을 하는 것이라면 "(내 계정 이름).github.io/_posts/2023-10-23-first.md" 라는 식으로 작성합니다. (first는 후에 포스트 주소가 됨)
  - md 파일 첫 부분에 다음 속성을 넣으세요.
    ```
    ---
    layout: single
    title: "첫 포스팅 입니다. 설레네요."
    ---
    "포스팅 내용"
    ```
* jupyter notebook 파일을 다운로드 받아 업로드하는 방법도 있습니다.
  - 다운로드 받은 .md 파일명을 변경합니다. (예시: "2023-10-23-second.md")
* images 업로드 방법
  - images 폴더 만들어서 이미지 업로드
