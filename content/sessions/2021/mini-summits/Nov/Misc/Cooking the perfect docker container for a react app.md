---
title        : Cooking the perfect docker container for a react app
track        : 
project      : 
type         : working-session
topics       :
featured     :
event        : mini-summit
when_year    : 2021
when_month   : Nov
when_day     : Thu
when_time    : WS-2
hey_summit   : https://post-summit-sessions.heysummit.com/talks/cooking-the-perfect-docker-container-for-a-react-app/
session_slack:
#status      : 
description  :
organizers   :
    - Luis Servin
youtube_link : 
zoom_link    : https://us06web.zoom.us/j/89282301436?pwd=cDhMRzZTeVRHV2tGRm12RGRLTDZrUT09
---

## About this session
Modern web development is built on top of complex leaky abstractions. Single page applications use some flavor of JavaScript, like react. 
This builds on top of nodejs for package management, but only needs it for building static JS and CSS files which can be served by any web server. 
Nodejs packages will pull other packages they depend upon and they will bring many vulnerabilities along. Creating a docker container for building the 
react app and publishing it without any vulnerabilities is a challenge. In this presentation well look at different recipes for creating react applications 
in docker containers, until we reach the best possible one: small size, only non-vulnerable components included.