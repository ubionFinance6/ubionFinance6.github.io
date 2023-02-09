----
layout: post
title: Welcome to Not Pure Poole
date: 2023-02-09 23:18 +0800
last_modified_at: 2020-10-01 01:08:25 +0800
tags: [github theme, jekyll, tutorial]
toc:  true
----

Github를 이용해 [정적(Static) 페이지(Page)](https://ko.wikipedia.org/wiki/%EC%A0%95%EC%A0%81_%EC%9B%B9_%ED%8E%98%EC%9D%B4%EC%A7%80)를 제작해 개발 및 자신의 도메인영역을 정리하는 블로그를 만들어 보도록 하겠습니다.

항상 공식 가이드를 참조하는 것이 중요하므로 아래와 같이 공식 가이드 링크가 있으니 꼭 보시길 바랍니다.

[
Getting started with GitHub Pages - GitHub Docs
Getting started with GitHub Pages You can set up a basic GitHub Pages site for yourself, your organization, or your project. GitHub Pages is available in public repositories with GitHub Free and GitHub Free for organizations, and in public and private repo
docs.github.com](https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/getting-started-with-github-pages)

- Github페이지 회원 가입 및 로그인
    
    ![Untitled](GitHub%20Web%20Page%201af04c28f6e84b559f992afd6e6c7d57/Untitled.png)
    
    위와 같은 페이지에서 회원가입 및 로그인을 진행한다.
    
    ![Untitled](GitHub%20Web%20Page%201af04c28f6e84b559f992afd6e6c7d57/Untitled%201.png)
    
    웹페이지의 버전에 따라 다를 수 있지만 제가 현재 가입당시 처음 로그인 페이지 모습입니다.
    

- Github에 webpage 만들기

![Untitled](GitHub%20Web%20Page%201af04c28f6e84b559f992afd6e6c7d57/Untitled%202.png)

위와 같이 노란색으로 표시한 부분중 아무거나 클릭을 한 후 repository를 생성합니다.

웹을 구성하는 파일(HTML, CSS, JS ...)이 업로드될 저장소(Repository)를 만들어야 합니다.

위 그림과 같이 노란색으로 표시한 부분중 아무거나 클릭을 한 후 repository를 생성합니다.

저장소 정보를 입력하는 화면에는 아래 사항에 유의하여 작성한다.

**Repository name:**

- 반드시 <사용자이름>.github.io 또는 <조직이름>.github.io로 명명해야 합니다. 즉 제가 가입한
    
    깃허브 주소는 [h](https://github.com/)[ttps://github.com/TKBIGDATA](https://github.com/TKBIGDATA) 입니다. 그러므로 저는 [TKBIGDATA](https://github.com/TKBIGDATA).github.io 이런식으로 만들어야 합니다.
    
- *반드시 <사용자이름>에는 자신의 github 사용자이름을 명확하게 넣어야 합니다.*
- 만약 <사용자이름>.github.com 이라는 저장소와 <사용자이름>.github.io 라는 저장소가 공존하는 경우 오직 <사용자이름.github.io 만 사이트로 배포된다. (github 가이드의 #types-of-github-pages-sites)

**Description:**

- 선택사항으로서 부연 설명이 필요한 경우 자유롭게 기입하고 패스 해도 무방합니다.

**Public 또는 Private:**

- 당연히 공공연히 공개할 것이므로 Public에 체크합니다.

**Initialize this repo....:**

- 'Add a README file' 공식 가이드에서는 체크표시를 해두라고 하지만 꼭 할 필요는 없다 하지만
    
    여기서는 github web 페이지를 만드는 과저엥서는 체크 하길 바랍니다.
    

![Untitled](GitHub%20Web%20Page%201af04c28f6e84b559f992afd6e6c7d57/Untitled%203.png)

- 그 외엔 자신의 프로젝트에 맞춰  설정 할 수 있지만 처음이니까 나머지는 패스 하도록 하겠습니다.

- 다음과 같이 빨간색으로 체크한 부분만 유의해서 처리하고 나머지는 그대로 건들지 않기로 하겠습니다.

방금 만든 Github 저장소의 페이지에 진입한 후에 상단에 있는 [**Settings**]를 클릭해줍니다.

나타나는 화면에서 스크롤을 거의 아래쪽으로 내리다 보면 [GitHub Pages]라는 항목이 보일 것이다.

![Untitled](GitHub%20Web%20Page%201af04c28f6e84b559f992afd6e6c7d57/Untitled%204.png)

![Untitled](GitHub%20Web%20Page%201af04c28f6e84b559f992afd6e6c7d57/Untitled%205.png)

기본적으로 [None]으로 선택된 상자를 클릭하고

자신이 보여주고자하는 브랜치(Branch, 분기점)를 선택한 다음 [**Save**] 버튼을 클릭합니다.

![https://blog.kakaocdn.net/dn/olrJw/btqJXWUoqZc/yyAqrfR32r4h25eKeRKZd1/img.png](https://blog.kakaocdn.net/dn/olrJw/btqJXWUoqZc/yyAqrfR32r4h25eKeRKZd1/img.png)

그리고 현재 화면이 새로고침되는데, 다시 GitHub Pages 항목을 본다면 아래와 같이

"Your site is published at http(s)://XXX.github.io" 라는 메시지가 보입니다.

그리고 알려준 주소로 접속해보면 아래와 같이 README.md의 내용이 표시됩니다.

![Untitled](GitHub%20Web%20Page%201af04c28f6e84b559f992afd6e6c7d57/Untitled%206.png)

![Untitled](GitHub%20Web%20Page%201af04c28f6e84b559f992afd6e6c7d57/Untitled%207.png)

이제 나름 HTML을 사용해서 페이지를 만들어서 올려보도록 하겠습니다.

다시 저장소의 [Code]로 돌아가서 README.md를 지우고 새로운 파일을 작성하기 위해 [Add file]을 클릭한다.

![Untitled](GitHub%20Web%20Page%201af04c28f6e84b559f992afd6e6c7d57/Untitled%208.png)

파일 이름을 [index.html]로 명명하고 HTML5의 기본 구조를 간략히 작성후 커밋을 한다.

- index.html은 보통 목적지가 html이 아닌 디렉토리(폴더)만 접근하면 나타나는 인덱스 페이지(다시 어느 링크가 있을지 가이드를 해주는 느낌의.)를 의미한다.

![Untitled](GitHub%20Web%20Page%201af04c28f6e84b559f992afd6e6c7d57/Untitled%209.png)

페이지 밑에 change commits 버튼을 누른 후 다음과 같이 다시 웹에 접속하면 아래와 같은 페이지가 

랜더링 됨을 알 수 있습니다.

단  github에서 페이지를 만들고 반영되기까지는 어느정도 시간이 걸리기 때문에 바로 보이지는 않고 적당한 시간이 지난후에 다시 접속하면 변경된 부분이 반영되어 있음을 알 수 있습니다.

![Untitled](GitHub%20Web%20Page%201af04c28f6e84b559f992afd6e6c7d57/Untitled%2010.png)

### **Jekyll을 이용한 블로그형 웹페이지 만들기**

물론  이와 같은 템플릿을 이용하여야만 깃허브에 웹페이지가 만들어 진다거나 혹은 다음과 같이 제시하는 방법이 가장 쉽다고는 할 수 없습니다.

단, 어느정도 개발자적인 부분에서 블로그를 만들고 한다면 markdown 파일 형식을 이용하게 되는 부분이 많고 이 파일 형식으로 콘텐츠를 올릴 수 있는 최적의 템플릿이라 생각되서 **Jekyll을 활용한**

웹 구성을 다뤄 보도록 하겠습니다.

**로컬에 Jekyll 설치하기**

1. 아래 명령어를 이용해 Ruby 버전을 확인합니다.   

Ruby가 설치되어 있지 않거나 버전이 2.4 미만이라면, [이 글](https://junstar92.tistory.com/5)을 참조해서 설치를 진행합니다.

```bash
C:\apps\TKBIGDATA.giihub.io> ruby -v# ruby 2.4.4 (2018-03-28) [x86_64-darwin18] 와 같은 형태로 버전이 출력됩니다.
```

2. 아래 명령어를 이용해 Jekyll을 설치합니다.

```
 C:\apps\TKBIGDATA.giihub.io> gem install jekyll bundler
```

![Untitled](GitHub%20Web%20Page%201af04c28f6e84b559f992afd6e6c7d57/Untitled%2011.png)

위와 같이 설치가 되는데 설치 내용이 다소 다를 수 있습니다.

**GitHub Repository 다운로드 하기**

1. GitHub에서 Repository 경로를 확인합니다.

![Untitled](GitHub%20Web%20Page%201af04c28f6e84b559f992afd6e6c7d57/Untitled%2012.png)

2. git clone 명령어를 이용해서 로컬로 다운로드하고, 디렉토리를 이동합니다.

```
C:\apps> git clone https://github.com/TKBIGDATA/TKBIGDATA.github.io.git# 제 경로는 이렇게 됩니다.
C:\apps>C:\apps> cd KBIGDATA.github.io

```

**Jekyll 생성하기**

1. 테스트로 생성했던 index.html을 삭제합니다.

```
C:\apps> del index.html
```

2. Jekyll을 생성합니다.

```
C:\apps> jekyll new ./
C:\apps> bundle install

```

3. 생성된 사이트를 실행해봅니다.

```
C:\apps> bundle exec jekyll serve
```

4. 개발용 서버가 실행됩니다. [http://localhost:4000](http://127.0.0.1:4000/)에 접속해서 생성된 사이트를 확인할 수 있습니다.

- localhost:4000으로 접속 했는데 에러가 나는 분들은 이 부분을 고민 하지 마시고 생략해도 됩니다. 다음 5번으로 넘겨서 진행하면 됩니다.

1. git add , git commit , git push 명령을 이용해서 github 페이지에 업로드 한후 일정시간이 지나면
    
    다음과 같이 페이지가 바뀐것을 확인 할 수있습니다.
    

![Untitled](GitHub%20Web%20Page%201af04c28f6e84b559f992afd6e6c7d57/Untitled%2013.png)

### 다음 진행해야 하는 것은 본인에 입맛에 맞는 jekyll 템플릿을 찾아 적용시킨후 포스트를 작성해 올리는 부분입니다. 이부분은 [**다음 포스트**](https://www.notion.so/Github-Web-page-2-7a5efa12597c46b68698b242a3096539)에서 진행하도록 하겠습니다.