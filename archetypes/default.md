---
date        : {{ .Date }}
title       : {{ replace .Name "-" " " | title }}
description : {{ replace .Name "-" " " | title }}
slug        : {{ .Name }}
stylesheet  :
- 
layout      : plain
---

