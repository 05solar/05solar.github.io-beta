---
title: '[c++] [BOJ] 백준 32032 / 만보기 대행 서비스'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Robert Ford

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-10-05T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *UCPC*
publication_short: In *UCPC*

abstract: 1.  입력을 받는다 2  최소 이동 거리 계산하기 2 - (ⅰ)  보관함이 0 (사옥의 위치) 를 기준으로 한쪽 방향 ( 양수 혹은 음수) 에만 존재하는 경우 2 - (ⅱ) 보관함이 사옥 기준 양쪽에 존재하는 경우 ( 양수, 음수 둘다 존재 ) 2 - (ⅱ)  - ①  case1 - 모든 위치를 왕복한 후 최소이동거리를 두번 더하는 경우 2 - (ⅱ)  - ②  case2 - 가장 왼쪽 위치를 두번 왕복하고 오른쪽을 왕복하며 최소이동거리를 걷는 경우 2 - (ⅱ)  - ③  case3 - 가장 오른쪽 위치를 두번 왕복하고 왼쪽을 왕복하며 최소이동거리를 걷는 경우 2 - (ⅱ)  -  ④  case4 - 1 - 가장 먼 두 지점 사이의 거리가 최소 이동거리보다 큰 경우 > > 가장 먼곳까지 두번 왕복  2 - (ⅱ)  - ⑤  case4 - 2 - 가장 먼 두 지점 사이의 거리가 최소 이동거리보다 작은 경우 >> 가장 먼곳까지 두번 왕복 + 최소 이동거리 한번 이동 3 . 2번 과정에서 구한 이동 거리 중 최소값을 출력

# Summary. An optional shortened abstract.
summary:  N명이 고객이 존재하는 서비스에서 휴대폰을 수거 한 채로 Dm를 이동하여야 한다. 휴대폰이 들어있는 각 보관함의 위치는 입력의 두번째 줄의 음수과 양수로 들어오며 사옥의 위치는 0이다. 

tags:
  - Ad hoc

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org


url_code: 'https://www.acmicpc.net/problem/32032'

url_source: 'https://lotus05f.tistory.com/entry/c-%EB%B0%B1%EC%A4%80-32032-%EB%A7%8C%EB%B3%B4%EA%B8%B0-%EB%8C%80%ED%96%89-%EC%84%9C%EB%B9%84%EC%8A%A4'


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/ko/%EC%82%AC%EC%A7%84/%EB%82%AE%EC%97%90-%EB%8F%84%EB%A1%9C-%ED%91%9C%EC%A7%80%ED%8C%90-%EA%B7%BC%EC%B2%98%EC%97%90-%EC%84%9C-%EC%9E%88%EB%8A%94-%EA%B2%80%EC%9D%80%EC%83%89-%EC%83%81%EC%9D%98%EB%A5%BC-%EC%9E%85%EC%9D%80-%EB%82%A8%EC%9E%90-h1itWfWeQM4)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""



Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
