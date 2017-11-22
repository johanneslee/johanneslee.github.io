---
layout: post
title: GitHub 블로그 개설과 Jekyll
excerpt: "블로그를 개설하게 된 계기와 Jekyll을 사용하게 된 이유"
modified: 2017-11-22T04:21:25-04:00
categories: articles
comments: true
share: true
---

### 개발자라면 내가 직접 만든 블로그 하나쯤은 있어야지!

...라는 생각에 오랜 시간을 힘겨워하다가 문득 깨달았다. "그냥 블로그 간단하게 만들고 프로젝트만 따로 링크를 걸면 되는 걸!" 잠시 이불을 팡팡 차다가 여러 기술 블로그가 GitHub 를 주소로 하고 있었던 것이 생각났다. 처음 블로그를 생성하면서 그렇게 Jekyll 을 알게 됐다.

>Jekyll 은 아주 심플하고 블로그 지향적인 정적 사이트 생성기입니다. Jekyll 은 다양한 포맷의 원본 텍스트 파일을 템플릿 디렉토리로부터 읽어서, (Markdown 등의) 변환기와 Liquid 렌더러를 통해 가공하여, 당신이 즐겨 사용하는 웹 서버에 곧바로 게시할 수 있는, 완성된 정적 웹사이트를 만들어냅니다. 그리고 Jekyll 은 GitHub Pages 의 내부 엔진이기도 합니다. 다시 말해, Jekyll 을 사용하면 자신의 프로젝트 페이지나 블로그, 웹사이트를 무료로 GitHub 에 호스팅 할 수 있다는 뜻입니다.

위의 내용은 문서에 기술된 Jekyll에 대한 정의이다.  
Markdown은 위키에서 활동하면서 익숙해진 마크업 언어인데, Liquid는 처음 접하는 언어였다.

>Liquid is an open-source template language created by Shopify and written in Ruby. It is the backbone of Shopify themes and is used to load dynamic content on storefronts.

공식 사이트에서 설명하는 정의는 위와 같고 기본적인 문법은 ASP, JSP, PHP 를 생각나게 한다. 그리고, 자체적으로 제공하는 여러 Object 가 있는 것 같은데, 이 부분은 좀더 살펴보아야 할 것 같다.

그리고 Jekyll, 이것의 중요한 포인트는 GitHub Pages 의 내부 엔진이라는 점이다. GitHub 는 "username.github.io" 라는 Repository 를 생성하면 그것을 주소로 하는 블로그를 즉시 개설할 수 있도록 지원한다. 또한, 나처럼 아직 Liquid 에 익숙하지 않은 사용자들을 위해 [무료 테마를 다운로드 할 수 있는 웹사이트](http://jekyllthemes.org/) 가 존재하기 때문에 손쉽게 그럴듯한 디자인을 적용할 수 있다.
