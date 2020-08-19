---
title:  "깃허브 블로그 포스팅 방법 단계별"
excerpt: "내가 포스팅 하는 단계별 방법"

categories:
  - Blog
tags:
  - Blog
last_modified_at: 2020-08-19
---
제가 포스팅하는 순서들로 적었습니다. <br>
1. gitbash 켜기  <br>
2. cd yourname.github.io본인 컴퓨터의 레파지토리로 이동  <br>
3. cd _posts  폴더로 이동 <br>
4. touch 2020-08-19-post-name.md 날짜와 포스트이름으로 마크다운파일생성  <br>
5. vi 2020-08-19-post-name.md 들어가서 포스팅  <br><br>
6. git add .
7. git commit –m “커밋내용”
8. push 하기 전 로컬로 확인하는 방법 <br> bundle exec jekyll serve 한뒤 127.0.0.1:4000 주소를 확인.<br> (하기전 yourname.github.io 레파지토리로 이동 해야함)<br>
9. git push origin master 

~끝~
