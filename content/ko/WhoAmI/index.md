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

  - block: features
    id: features
    content:
      title: "<span style=\"font-size:75%\">제 몇가지 다른 취미는</span>"
      items:
        - name: 축구
          icon: running
          icon_pack: fas
          description: "<span style=\"font-size:90%\">용대FC의 LW/LB</span>"
        - name: 대안 데이터를 활용한 투자 전략
          icon: chart-line
          icon_pack: fas
          description: "<span style=\"font-size:90%\">인간 지표가 존재한다고 믿습니다.</span>"
        - name: 페퍼톤스
          icon: music
          icon_pack: fas
          description: "<span style=\"font-size:90%\">Superfantastic</span>"


  - block: experience
    content:
      title: Education
      items:
        - title: 전북대학교 컴퓨터인공지능학부(재학)
          description: 전북대학교 컴퓨터인공지능학부(it정보공학과)
          date_start: '2020-03-02'
        - title: 고등학교(졸업)
          description: 대전가오고등학교
          date_start: '2016-03-02'
          date_end: '2019-12-31'


    design:
      slide_height: '350px'
      slide_width: '100%'
      is_fullscreen: false
      loop: true
      interval: 3000


---
