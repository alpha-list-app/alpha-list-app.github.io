---
layout: blocks
title: Homepage
date: 2017-11-22T23:00:00.000+00:00
page_sections:
  - template: navigation-header-w-button
    block: header-2
    logo: "/uploads/2018/06/21/alphalist_logo.png"
    navigation:
      - link: "/"
        link_text: Ubuild
      - link: "#swap"
        link_text: Swap
      - link: "#customize"
        link_text: Customize
      - link: "#responsive"
        link_text: Responsive
      - link: "#blocks"
        link_text: Blocks
    cta:
      url: https://app.forestry.io/quick-start?repo=forestryio/ubuild-jekyll&provider=github&engine=jekyll
      button_text: Import
  - template: hero-banner-w-image
    block: hero-2
    slug: features
    headline: 나의 합리적 투자 <br><strong>Alphalist</strong>
    content:
      아직도 이 회사가 뭐하는 회사인지도 모르고 투자하나요?<br>
      주식은 어렵고 공부를 하라고 하는데 도대체 뭘 공부해야 하는지도 모르겠고
      알파리스트는 기업의 재무건전성, 성장가능성, 시장전망을 분석하여 여러분에게 
      종목을 추천하고 가치평가를 통해 적정주가 기반의 매매 시나리오까지 알려드립니다.<br> 
      이제 깜깜이 투자말고 알파리스트와 함께 합리적으로 현명한 투자를 해보세요 
    cta:
      enabled: true
      url: https://github.com/forestryio/ubuild-jekyll
      button_text: "See on GitHub "
    image:
      image: "/uploads/2018/06/21/alphalist_concept.png"
      alt_text: Product Shot
    background_image: "/uploads/2018/06/21/hero-2-bg.png"
  - template: content-feature
    block: feature-1
    media_alignment: Left
    slug: swap
    headline:
      <strong>Swap &amp; Switch<span class="light">&nbsp;</span></strong><span
      class="light">the Blocks to create sites quickly</span>
    content:
      Quickly assemble and create custom sites with 16 design blocks for seven
      different sections.
    media:
      image: "/uploads/2018/06/21/blocks-split.png"
      alt_text: uBuild Blocks Mock-Up
  - template: content-feature
    block: feature-1
    media_alignment: Right
    slug: customize
    headline:
      <strong>Customize Blocks</strong><span class="light">&nbsp;to make quick
      edits throughout your new site</span>
    content:
      Each block comes with custom Front Matter that can be edited in
      Forestry CMS.
    media:
      image: "/uploads/2018/06/21/edit.gif"
      alt_text: Customize Blocks
  - template: 1-column-text
    block: one-column-1
    slug: responsive
    headline: 16 Fully Responsive Design Blocks
    content: |
      The Design Blocks can be used without Forestry but to harness the power
      of Blocks we recommend using <a href="https://forestry.io">Forestry</a>. Once the site is imported you can immediately
      create new sites and make them fully customizable.
  - template: full-width-media-element
    block: media-1
    image: "/uploads/2018/06/21/theme.png"
    caption: All Available Blocks
    slug: blocks
  - template: detail-content
    block: text-1
    headline: Steps to Build a Site!
    content:
      <p>uBuild is an open-source Jekyll based demo that doubles as a builder tool inside the Forestry content manager.</p><ol><li><p><a href="https://app.forestry.io/quick-start?repo=forestryio/ubuild-jekyll&provider=github&engine=jekyll">Import this demo in Forestry</a>.</p></li><li><p>Read <a href="https://forestry.io/blog/ubuild-a-new-theme-for-static-sites-using-blocks/">our
      article</a> and create your own Blocks.</p></li><li><p>Add and customize the available Blocks and preview them as you go along.</p></li></ol>
  - template: simple-footer
    block: footer-1
    content: Made with ❤︎ in Canada
---
