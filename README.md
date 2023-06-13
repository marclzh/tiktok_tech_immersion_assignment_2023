# TikTok Tech Immersion Assignment 1

![Tests](https://github.com/marclzh/tiktok_tech_immersion_assignment_2023/blob/main/.github/workflows/test.yml/badge.svg)
Code Adapted from https://github.com/weixingp/tiktok-tech-immersion-2023.

This is the backend assignment of 2023 TikTok Tech Immersion.

## Installation

Requirement:

- golang 1.18+
- docker

To install dependency tools:

```bash
make pre
```

## Run

```bash
docker-compose up -d
```

Check if it's running:

```bash
curl localhost:8080/ping
```
