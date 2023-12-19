---
layout: splash
permalink: /
hidden: false
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/home-page-feature.jpg
  actions:
    - label: "<i class='fas fa-download'></i> 의뢰하기"
      url: "/about/"
excerpt: >
  믹스 커미션을 시작하기<br />
knowledge-base_feature_row:
  - image_path: /assets/images/mm-customizable-feature.png
    alt: "customizable"
    title: "녹음하는 방법"
    excerpt: "커미션을 의뢰하기 위해 녹음하는 방법을 알아보자"
    url: "/knowledge-base/how-to-record/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/images/mm-responsive-feature.png
    alt: "fully responsive"
    title: "파일 보내기"
    excerpt: "녹음 후 알맞게 파일을 보내는 방법을 알아보자"
    url: "/about/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/images/mm-free-feature.png
    alt: "100% free"
    title: "의뢰하는 방법"
    excerpt: "믹스 진행을 위해 필요한 의사소통 방법을 알아보자"
    url: "/about/"
    btn_class: "btn--primary"
    btn_label: "Learn more" 
portfolio_feature_row:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "customizable"
    title: "Portfolio"
    excerpt: "Bacon ipsum dolor sit amet salami ham hock ham, hamburger corned beef short ribs kielbasa biltong t-bone drumstick tri-tip tail sirloin pork chop."
    url: "/portfolio/"
    btn_class: "btn--primary"
    btn_label: "보러가기"
---

{% include feature_row id="portfolio_feature_row" type="left" %}

{% include feature_row id="knowledge-base_feature_row" %}
