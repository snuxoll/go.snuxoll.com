+++
title = 'go.snuxoll.com/{{ .File.ContentBaseName }}'
mod = 'go.snuxoll.com/{{ .File.ContentBaseName }}'
repo = 'github.com/snuxoll/go-{{ .File.ContentBaseName }}'
date = {{ .Date }}
draft = true
+++
{{< package-widgets >}}
## Overview
Package {{ .File.ContentBaseName }}