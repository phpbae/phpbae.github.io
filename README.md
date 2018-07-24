# phpbae.github.io

## github page 생성 2018.07.25

## URL : https://phpbae.github.io/

## 댓글기능 : facebook 댓글 플러그인 이용(https://developers.facebook.com/docs/plugins/comments/)

## 사용 테마 및 참고
- Jekyll 기반으로 생성
- Jekyll theme : https://mmistakes.github.io/minimal-mistakes/  
- remote-theme 기능?을 이용해서, 테마를 적용
- _config.yml 파일을 가져와서, 설정을 해주자

```
theme                  : "minimal-mistakes-jekyll"
remote_theme           : "mmistakes/minimal-mistakes" 
minimal_mistakes_skin    : "mint" # 테마는 알아서 선택하시라.
url                      : "https://yourname.github.io" # the base hostname & protocol for your site e.g. "https://mmistakes.github.io"
baseurl                  : "" # the subpath of your site, e.g. "/blog"

```


- index.html 생성

```
---
layout: home
author_profile: true
---
```

- _post 폴더 아래에, 새로운 글을 작성하자.
- YYYY-MM-DD-name-post.md 형식으로 파일을 지정
