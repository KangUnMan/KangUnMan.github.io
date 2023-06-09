---
layout: post
title: PRG Pattern
date: 2023-06-09 00:00:00 +0300
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img:  PRG.jpg # Add image post (optional)
tags: [programming, PRG] # add tag
---


### PRG 패턴이란?
**정의**

PRG(POST-Redirect-GET) 패턴은 웹 개발 시에 권장되는 디자인 패턴으로, HTTP POST 요청에 대한 응답이 또 다른 URL로의 GET 요청을 위한 리다이렉트여야 한다는 것을 의미한다.

**사용해야 하는 이유**

가장 큰 이유는 새로 고침으로 인해 동일한 POST 요청이 중복으로 발생할 수 있는 문제가 있다.  

**사용 방법**

redirect 를 이용하여 URL로 이동시키자.

**redirect란 ?**

리다이렉트(Redirect)는 서버에서 클라이언트에서 요청한 URL에 대 응답에서 다른 URL로 재접속 하라고 명령을 보내는 것을 말한다. Re-Direct는 'URL을 다시 가리킨다' 라는 뜻을 가지며, 클라이언트는 해당 URL로 다시 요청하게 된다.



