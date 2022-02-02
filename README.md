# React JS Landing Page Template

Main landing page repo for HackerWay Studio



Dependency:
* yarn for gh-pages module

Usage:
yarn add --dev gh-pages

"homepage": "https://hackerwaystudio.github.io/hackerway-studio",
"predeploy": "export NODE_OPTIONS=--openssl-legacy-provider; yarn run build",
"deploy": "gh-pages -d build",
