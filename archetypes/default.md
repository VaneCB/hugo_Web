---
baseURL = 'http://localhost/'
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
theme =['relearn']

---
