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

...라는 생각에 힘겨워하다가 문득 그런 생각이 들었다.
간단한 블로그 안에 프로젝트만 따로 링크를 걸면 되지 않나?
깨달음이 번뜩였고 마침 돌아다니던 Github를 보다 Jekyll이 생각났다.

>Jekyll 은 아주 심플하고 블로그 지향적인 정적 사이트 생성기입니다. Jekyll 은 다양한 포맷의 원본 텍스트 파일을 템플릿 디렉토리로부터 읽어서, (Markdown 등의) 변환기와 Liquid 렌더러를 통해 가공하여, 당신이 즐겨 사용하는 웹 서버에 곧바로 게시할 수 있는, 완성된 정적 웹사이트를 만들어냅니다. 그리고 Jekyll 은 GitHub Pages 의 내부 엔진이기도 합니다. 다시 말해, Jekyll 을 사용하면 자신의 프로젝트 페이지나 블로그, 웹사이트를 무료로 GitHub 에 호스팅 할 수 있다는 뜻입니다.

위의 내용은 문서에 기술된 Jekyll에 대한 정의이다.
내용 중에 Markdown은 텍스트를 HTML로 변환하는 변환기이며 '#', '=', '>' 등을 사용한 간단한 문법으로 쉽게 포스트를 작성할 수 있다. Liquid는 Ruby로 작성된 오픈소스 템플릿 언어이다. 웹페이지에 동적인 컨텐츠를 로드하는 Shopify의 Backbone으로 기능하고 있다.

중요한 점은 Jekyll이 GitHub Pages 의 내부 엔진이라는 점이다. "ID.github.io"라는 Repository 만 만들면 간단하게 블로그를 개설할 수 있다. 또한, <a href='http://jekyllthemes.org/'>Jekyll 테마 웹사이트</a> 에서 무료 테마를 지원받을 수 있어서 손쉽게 멋진 디자인을 꾸밀 수 있다.
