---
layout: app

permalink: /ieaseMusic/
description: 这应该是最好的网易云音乐播放器了，没有之一，如果有请打醒 🤘

screenshots:
  - ieaseMusic/screenshot.png

authors:
  - name: trazyn
    url: https://github.com/trazyn

links:
  - type: GitHub
    url: trazyn/ieaseMusic
  - type: Install
    url: https://github.com/trazyn/ieaseMusic/releases

desktop:
  Desktop Entry:
    Name: ieaseMusic
    Comment: "这应该是最好的网易云音乐播放器了，没有之一，如果有请打醒 \U0001F918"
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: iease-music
    X-AppImage-Version: 1.0.1
    X-AppImage-BuildId: c320cf20-b312-11a7-25a8-0df93c0d8341
    Categories: Music
  AppImageHub:
    X-AppImage-UpdateInformation: 
    X-AppImage-Type: 1
    X-AppImage-Architecture: x86_64

electron:
  main: main.js
  author:
    name: trazyn
    email: var.darling@gmail.com
    url: https://twitter.com/var_darling
  license: MIT
  repository:
    type: git
    url: https://github.com/trazyn/ieaseMusic.git
  dependencies:
    apicache: "^0.11.2"
    axios: "^0.16.2"
    big-integer: "^1.6.25"
    classname: 0.0.0
    cookie-parser: "^1.4.3"
    debug: "^3.0.1"
    delegate: "^3.1.3"
    electron-json-storage: "^3.1.0"
    electron-window-state: "^4.1.1"
    han: 0.0.7
    ionicons201: "^1.0.0"
    md5: "^2.2.1"
    mobx: "^3.2.2"
    mobx-react: "^4.2.2"
    moment: "^2.18.1"
    perdido: "^2.0.1"
    react: "^15.6.1"
    react-addons-css-transition-group: "^15.6.0"
    react-dom: "^15.6.1"
    react-jss: "^7.1.0"
    react-router: "^3.0.5"
    react-scroll-horizontal: github:trazyn/react-scroll-horizontal#gh-pages
    request: "^2.81.0"
---
