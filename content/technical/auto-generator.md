+++
title = "3D一筆書きゲームの作成補助ツール"
date = 2024-01-05
summary = "3D一筆書きを作成するため、点と点(球と球)を結ぶ線(円柱)オブジェクトを自動で配置するツールを作成。\n開発人数:　1人\n開発時期:　2023年月~月(ヶ月)"
featured = true
weight = 2
tags = ["ツール", "個人開発"]
categories = ["ツール"]
main_image = "images/one_stroke_tool.gif"
+++

A custom static site generator that prioritizes speed and simplicity. Built in Go for maximum performance.

## Key Features

- Lightning-fast build times
- Markdown support with custom extensions
- Template system with inheritance
- Asset pipeline for CSS and JavaScript
- Live reload during development
- Flexible plugin system

## Why Another Generator?

While existing tools are great, this project explores alternative approaches to content transformation and focuses on minimalism and speed.

## Performance

Builds a 1000-page site in under 200ms on average hardware. Uses parallel processing and smart caching.

## Usage

```bash
# Install
go install github.com/yourusername/ssg

# New site
ssg new mysite

# Build
ssg build

# Serve with live reload
ssg serve
```

## Future Plans

- Incremental builds
- Extended plugin API
- Theme marketplace
- Cloud deployment integration
