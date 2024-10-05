---
# Leave the homepage title empty to use the site title
title: Who Am I
type: landing
sections:

  - block: about.biography
    id: about
    content:
      title: ''
      username: admin
      
  - block: experience
    content:
      title: Work
      items:
        - title: 주식회사 디프리
          description: 소프트웨어 엔지니어
          date_start: '2024-01-01'
        - title: 주식회사 하이컨시
          description: 법무팀
          date_start: '2020-01-01'
          date_end: '2021-03-01'

  - block: features
    id: features
    content:
      title: "<span style=\"font-size:75%\">제 몇가지 다른 취미는</span>"
      items:
        - name: 축구
          icon: running
          icon_pack: fas
          description: "<span style=\"font-size:90%\">용대FC의 영원한 LW</span>"
        - name: 대안 데이터를 활용한 투자 전략
          icon: chart-line
          icon_pack: fas
          description: "<span style=\"font-size:90%\">인간 지표가 존재한다고 믿습니다.</span>"
        - name: 페퍼톤스
          icon: music
          icon_pack: fas
          description: "<span style=\"font-size:90%\">인생은 Superfantastic</span>"


    design:
      slide_height: '350px'
      slide_width: '100%'
      is_fullscreen: false
      loop: true
      interval: 3000


---
