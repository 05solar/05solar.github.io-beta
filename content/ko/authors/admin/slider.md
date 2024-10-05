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
        - title: AI
          content: '의료/항공우주/컨텐츠 등 특성화 분야에 적용 가능한 AI 기술 개발'
          align: center
          background:
            image:
              filename: ai.jpg
              filters:
                brightness: 0.5
            position: center
            color: '#333'
        - title: Medical AI
          content: '의료 AI를 통한 질병 진단 및 환경 개선'
          align: center
          background:
            image:
              filename: medical_ai.jpg
              filters:
                brightness: 0.7
            position: right
            color: '#666'
        - title: Development
          content: '지식을 공유하고 새로운 주제를 함께 탐구해보세요!'
          align: center
          background:
            image:
              filename: development.jpg
              filters:
                brightness: 0.7
            position: center
            color: '#555'
        - title: Mathematics
          content: '수학적 알고리즘 연구를 위한 최신 자료'
          align: center
          background:
            image:
              filename: mathematics.jpg
              filters:
                brightness: 0.5
            position: center
            color: '#333'
          link:
            icon: graduation-cap
            icon_pack: fas
            text: 'Join Us'
            url: ../contact/
    design:
      slide_height: '350px'
      is_fullscreen: true
      loop: true
      interval: 3000
---
