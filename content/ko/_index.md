---
# Leave the homepage title empty to use the site title
title: 메인페이지
date: 2024-03-25
type: landing
sections:

  - block: about.biography
    id: about
    content:
      title: ''
      username: admin
    design:
      background:
        image:
          filename: 18216.jpg
          # Optional: Set background image options
          size: cover
          position: center
          parallax: false


  - block: collection
    content:
      id: section-1
      title: 내 프로젝트
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - field
    design:
      view: community/custom_card
      columns: '2'

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

  - block: slider
    content:
      slides:
        - title: "<span style=\"font-size:70%\">공모전</span>"
          content: "<span style=\"font-size:70%\">다양한 공모전에 관심있으십니까?</span>"
          align: center
          background:
            image:
              filename: forest.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'
          link:
            icon: external-link-alt
            icon_pack: fas
            text: "Image 출처: Unsplash"
            text-color: '#fff'
            url: "https://unsplash.com/ko/%EC%82%AC%EC%A7%84/%EC%88%B2-%EC%86%8D-%EC%98%A4%EC%86%94%EA%B8%B8-GraajutbJHE"

        - title: "<span style=\"font-size:70%\">아웃소싱(외주)</span>"
          content: "<span style=\"font-size:70%\">크몽이나 기타 외주를 받고싶으십니까?</span>"
          align: center
          background:
            image:
              filename: forest1.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'
          link:
            icon: external-link-alt
            icon_pack: fas
            text: "Image 출처: Unsplash"
            text-color: '#fff'
            url: "https://unsplash.com/ko/%EC%82%AC%EC%A7%84/foggy-mountain-summit-1Z2niiBPg5A"

        - title: "<span style=\"font-size:70%\">코딩</span>"
          content: "<span style=\"font-size:70%\">컴퓨터 과학이나 코딩에 관심있으십니까?</span>"
          align: center
          background:
            image:
              filename: forest2.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'
          link:
            icon: external-link-alt
            icon_pack: fas
            text: "Image 출처: Unsplash"
            text-color: '#fff'
            url: "https://unsplash.com/ko/%EC%82%AC%EC%A7%84/%ED%91%B8%EB%A5%B8-%EB%B3%84%EC%9D%B4-%EB%B9%9B%EB%82%98%EB%8A%94-%EB%B0%A4-1OtUkD_8svc"

        - title: "<span style=\"font-size:70%\">런닝</span>"
          content: "<span style=\"font-size:70%\">매일 10km씩 뛰면서 다이어트 하고싶으세요?</span>"
          align: center
          background:
            image:
              filename: 런닝.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'
          link:
            icon: external-link-alt
            icon_pack: fas
            text: "Image 출처: Unsplash"
            text-color: '#fff'
            url: "https://unsplash.com/ko/%EC%82%AC%EC%A7%84/%EC%BD%98%ED%81%AC%EB%A6%AC%ED%8A%B8-%EB%8F%84%EB%A1%9C%EB%A5%BC-%EB%8B%AC%EB%A6%AC%EB%8A%94-%EC%82%AC%EB%9E%8C-Apj4nSemkzk"

        - title: "<span style=\"font-size:70%\">대학원</span>"
          content: "<span style=\"font-size:70%\">학부 공부를 넘어서 대학원진학에 관심있으세요?</span>"
          align: center
          background:
            image:
              filename: 공부.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'
          link:
            icon: external-link-alt
            icon_pack: fas
            text: "Image 출처: Unsplash"
            text-color: '#fff'
            url: "https://unsplash.com/ko/%EC%82%AC%EC%A7%84/%ED%9D%B0%EC%83%89-%EC%84%B8%EB%9D%BC%EB%AF%B9-%EB%A8%B8%EA%B7%B8%EC%9E%94-%EA%B7%BC%EC%B2%98%EC%9D%98-%EA%B0%88%EC%83%89-%EB%82%98%EB%AC%B4-%ED%85%8C%EC%9D%B4%EB%B8%94%EC%97%90-%EA%B8%80%EC%9D%84-%EC%93%B0%EB%8A%94-%EC%82%AC%EB%9E%8C-s9CC2SKySJM"

    design:
      slide_height: '350px'
      slide_width: '100%'
      is_fullscreen: false
      loop: true
      interval: 3000


---
