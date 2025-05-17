Sure! Below is a clean, well-structured **Markdown (.md)** documentation of your HTML layout. It breaks down the structure into nested sections with classes, IDs (if available), and common elements like `<h1>`, `<div>`, `<button>`, etc., clearly noted. This will help developers or WordPress integrators quickly identify and copy the class structures for styling or templating.

---

## 📄 HTML Structure Documentation (for WordPress Conversion)

```md
# Wrapper
<section>  
- classes: `wrapper-atom-animation`

  ## Main Screen
  <section>
  - classes: `main-screen`

    ### Main Content
    <div>  
    - classes: `main-content`

      - `<h1>`: 高品質の開発による信頼と安心  
      - `<div class="sub-text">`  
        - `<div class="text-white">`: ・低コスト、高品質を実現するオフショア開発ソリューション  
        - `<div class="text-white">`: ・プロフェッショナルオフショア開発チーム  
      - `<button class="animated-button">`  
        - Contains `<marquee>`: ご相談はこちらまで...

    ### Glass Background
    <div>  
    - classes: `glass`  
    - inline styles: `top`, `left`, `width`, `height`

    ### Second Content
    <section>  
    - classes: `second-content`  
      - `<h4 class="text-white second-content-text">`: お客様のニーズに合わせた柔軟なソリューションを提供します

  ## Atom Animation
  <div>  
  - classes: `atom-position`

    - `.atom-container.large-atom > .atom > .atom-image`  
    - `.atom-container.small-atom > .atom > .atom-image`  

  ## Software Section
  <section>  
  - classes: `software-section`

    ### Title
    <div>  
    - classes: `title-section flex FY-center`  
      - `<img>`: Circle icon  
      - `<h4>`: ソフトウエアソリューション

    ### Cards Grid
    <section>  
    - classes: `cards flex FW`  
      - Multiple `.card` (12 times)  
        - `<a>` → `javascript:alert('clicked')`  
          - `<div class="card-body">`  
            - `<div class="logo">` → `<img>`  
            - `<h4>`: Webアプリケーション開発

  ## Software Security Container
  <section>  
  - classes: `software-security-container flex FY-center F-space`

    ### Left Security List
    <div class="left">
    - multiple `.security MB` / `.security`

      - `<h5>`: 機密情報漏洩対策ソリューション  
      - `<h5>`: 安全なVPNソリューション  
      - `<h5>`: DDOS Attackソリューション  

    ### Center Animation
    <div class="animation flex F-center">
      - `<a>`: セキュリティ title  
        - `<div class="ss-shild flex">` → `<h3>` セキュリティ  
      - `<section class="svg-animation-container">`: 2x rotating `<svg>` animations

    ### Right Security List
    <div class="right">
    - multiple `.security MB` / `.security`

      - `<h5>`: 脅威認識･データ保護ソリューション  
      - `<h5>`: 脆弱性診断ソリューション  
      - `<h5>`: Cyberセキュリティソリューション  

---

## 📰 News Section

<section>  
- classes: `news-update-container`

  <div class="news-custom-container">
  - classes: `news-custom-container`

    ### Title
    <div class="title-section flex FY-center">
    - `<img>`: circle icon  
    - `<h4>`: ニュース

    ### News Card
    <div class="update-news">
      - `.card > a[href="/jp/news-update"]`  
        - `<img>`: news image  
        - `<h4>`: オフショア開発の現状を学ぶ...  
        - `<h5>`: プレスリリース  
        - `<p>`: 日付 2024年4月16日火曜日

---

## 🦶 Footer CTA Section

<section>  
- classes: `first-fotter`

  ### Title
  <div class="title-fotter">
  - `<h4>`: プロジェクトの成功に貢献いたします。

  ### Contact Box
  <div class="contectus_herosection">
    - `.chs_content > h4`: お見積り・ご要望・...  
    - `.chs_number > a`: 03-6722-0631  
    - `.chs_number > h5`: 平日9:00-18:00  
    - `.chs_button > a[href="/contact-us"] > button.animated-button`
      - Contains `<marquee>`: ご相談はこちらまで...

  - `<div class="fotter-animation">`: background animation

---

## 🦶 Footer Links

<section>  
- classes: `fotter flex F-center`

  ### Footer Container
  <div class="fotter-container flex F-space">

    #### Footer Info
    <section class="fotter-info">
    - `<img>`: footer logo  
    - `<p class="fotter-text">`: 日本企業による安心...

    #### Footer Links
    <section class="fotter-links">
    - `<ul>` > `<li>` > `<a>`  
      - ご挨拶 / 開発実績 / ソリューション / ... など

    #### Page Top Link
    <p class="on-click-top" onclick="goHome()">ページのトップへ</p>

---

## 📜 Script

- `<script src="./main.js">`
