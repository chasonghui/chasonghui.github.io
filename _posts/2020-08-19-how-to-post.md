---
title:  "깃허브 블로그 포스팅 방법 단계별"
excerpt: "내가 포스팅 하는 단계별 방법"

categories:
  - Blog
tags:
  - Blog
last_modified_at: 2020-08-19T17:23:00
---
짬송이 포포스팅하는 순서 
==========================
gitbash 켜기   
```
cd yourname.github.io
```
본인 컴퓨터의 레파지토리로 이동    
<hr/>
```
cd _posts
```
폴더로 이동   
<hr/>
```
touch 2020-08-19-post-name.md
```
날짜와 포스트이름으로 마크다운파일생성   
<hr/>
```
vi 2020-08-19-post-name.md
```
들어가서 포스팅 
<hr/>
```
git add .
git commit –m “커밋내용”
```
add 하고. commit 하기   
<hr/>
push 하기 전 로컬로 확인하는 방법   
```
bundle exec jekyll serve 
```
한뒤 127.0.0.1:4000 주소를 확인.   
(주의: 이동전 yourname.github.io 레파지토리로이동)   
```
git push origin master
```
push 해준다.

~끝~
