---
title : '{{ replace .File.ContentBaseName "-" " " | title }}'
date : {{ .Date | time.Format ":date_medium" }}
draft : true
tags:
---
