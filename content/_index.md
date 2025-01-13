---

# Leave the homepage title empty to use the site title

title: ""
date: 2022-10-24
type: landing

design:

# Default section spacing

spacing: "6rem"

sections:

- block: resume-biography-3
  content:
     # Choose a user profile to display (a folder name within `content/authors/`)
    username: admin
    text: ""
    # Show a call-to-action button under your biography? (optional)
    button:
      text: Download CV
      url: https://drive.google.com/file/d/1Ri2df2VMjTj-9ztWO64kVHH3XQX4b4kp/view?usp=sharing
    design:
      css_class: dark
      background:
      color: black
     image:
     # Add your image background to `assets/media/`.
      filename: stacked-peaks.svg
      filters:
      brightness: 1.0
      size: cover
      position: center
      parallax: false
- block: markdown
  content:

content:
  title: "📚 My Portfolio"
  subtitle: ""
  text: |-
    Selamat datang di portofolio saya! Saya seorang mahasiswa Rekayasa Perangkat Lunak di ITESA Muhammadiyah yang memiliki minat di bidang pengembangan perangkat lunak, web development, dan teknologi informasi.

    Saya senang mempelajari teknologi baru, membangun solusi inovatif, dan berkolaborasi dalam proyek-proyek yang berdampak positif. Jika Anda tertarik untuk bekerja sama, jangan ragu untuk menghubungi saya! 😊
  design:
    columns: "1"
- block: collection
  id: projects
  content:
    title: Featured Projects
    filters:
      folders:
        - project
      featured_only: true
  design:
    view: article-grid
    columns: 2
- block: collection
  content:
    title: Recent Projects
    text: ""
    filters:
      folders:
        - project
      exclude_featured: false
  design:
    view: citation
- block: collection
  id: talks
  content:
    title: Recent Activities
    filters:
      folders:
        - activity
  design:
    view: article-grid
    columns: 1
- block: collection
  id: blog
  content:
    title: Blog
    subtitle: ""
    text: ""
    page_type: post
    count: 5
    filters:
      author: ""
      category: ""
      tag: ""
      exclude_featured: false
      exclude_future: false
      exclude_past: false
      publication_type: ""
    offset: 0
    order: desc
  design:
    view: date-title-summary
    spacing:
      padding: [0, 0, 0, 0]
- block: cta-card
  demo: true
  content:
    title: 👉 Bangun Website Portofoliomu Sendiri
    text: |-
      Situs ini dibuat dengan Hugo Blox Builder - alat pembuat situs open source yang sederhana dan gratis!

      <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

      Buat situs profesional tanpa perlu menulis banyak kode.
    button:
      text: Pelajari Lebih Lanjut
      url: https://hugoblox.com/templates/
  design:
    card:
      css_class: "bg-primary-700"
      css_style: ""

---
