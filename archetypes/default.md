+++
title = '{{ replace .File.ContentBaseName `-` ` ` | title }}'
date = {{ .Date }}
draft = true
tags = []
categories = ['{{ index (split .File.Dir "\\") 1 | title }}']
+++
