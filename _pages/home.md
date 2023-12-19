---
layout: splash
permalink: /
hidden: false
header:
  overlay_color: "#000"
  overlay_filter: "0.6"
  overlay_image: /assets/images/home-page-feature.jpg
excerpt: "여러분의 노래를 믹싱으로 남겨보세요"
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
intro_feature_row:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "customizable"
    title: "Commision"
    excerpt: "믹싱 의뢰하기"
    url: "/commision/"
    btn_class: "btn--primary"
    btn_label: "이동하기"
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "customizable"
    title: "Portfolio"
    excerpt: "믹스 작업물들과 제작한 플러그인들"
    url: "/portfolio/"
    btn_class: "btn--primary"
    btn_label: "보러가기"
---

{% include feature_row id="intro_feature_row" %}

{% include feature_row id="knowledge-base_feature_row" %}

<div class="page__hero--overlay" style="background-color: #000; background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('/mix_commision/assets/images/home-page-feature.jpg');">
  <div class="wrapper">
    <h1 id="page-title" class="page__title" itemprop="headline">믹스 커미션
    </h1>
    <p class="page__lead">여러분의 노래를 믹싱으로 남겨보세요
    </p>
    <p>
      <a href="/mix_commision/commision/" class="btn btn--light-outline btn--large">의뢰하기</a>
    </p>
  </div>
</div>
