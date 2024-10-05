---
title: "slider"
date: 2024-10-04
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: slider
    content:
      slides:
        - title: 프로젝트
          content: '한동대 LLM 빅데이터 캠프'
          align: center
          background:
            image:
              filename: assets\media\bigdata.png
              filters:
                brightness: 0.5
            position: center
            color: '#333'
        - title: 프로젝트
          content: '자바 팀 프로그래밍'
          align: center
          background:
            image:
              filename: assets\media\java.png
              filters:
                brightness: 0.7
            position: right
            color: '#666'
        - title: 프로젝트
          content: '웹서비스 설계 팀프로젝트 '
          align: center
          background:
            image:
              filename: assets\media\htmlcssjs.png
              filters:
                brightness: 0.7
            position: center
            color: '#555'

    design:
      slide_height: '350px'
      is_fullscreen: false
      loop: true
      interval: 3000
---
