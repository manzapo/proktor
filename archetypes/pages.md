---
date        : {{ .Date }}
title       : {{ replace .Name "-" " " | title }}
description : {{ replace .Name "-" " " | title }}
slug        : {{ .Name }}
url         : {{ .Name }}
stylesheet  :
- bootstrap-icons.css
layout      : plain
---
