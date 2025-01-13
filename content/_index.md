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
  content:
  title: "📚 My Portfolio"
  subtitle: "Mahasiswa Rekayasa Perangkat Lunak"
  text: |-
    Selamat datang di portofolio saya! Saya seorang mahasiswa Rekayasa Perangkat Lunak di ITESA Muhammadiyah. Saya memiliki minat mendalam dalam pengembangan perangkat lunak, web development, dan teknologi informasi.

    Saya antusias mempelajari teknologi baru, membangun solusi inovatif, dan berkolaborasi dalam proyek berdampak positif. Jangan ragu untuk menghubungi saya untuk diskusi atau peluang kerja sama! 😊
  design:
    columns: "1"

- block: collection
  id: featured-projects
  content:
    title: "🎯 Featured Projects"
    text: "Proyek unggulan yang saya kerjakan dengan fokus pada solusi kreatif dan inovatif."
    filters:
      folders:
        - project
      featured_only: true
  design:
    view: article-grid
    columns: 2

- block: collection
  id: recent-projects
  content:
    title: "🛠 Recent Projects"
    text: "Proyek-proyek terbaru yang telah saya selesaikan."
    filters:
      folders:
        - project
      exclude_featured: true
  design:
    view: citation
    columns: 1

- block: collection
  id: activities
  content:
    title: "📅 Recent Activities"
    text: "Kegiatan terbaru saya, termasuk seminar, lomba, dan kolaborasi."
    filters:
      folders:
        - activity
  design:
    view: article-grid
    columns: 1

- block: collection
  id: blog
  content:
    title: "📝 Blog"
    subtitle: "Pandangan dan wawasan saya tentang teknologi."
    text: "Baca artikel terbaru saya untuk mengetahui lebih banyak tentang pengalaman, tutorial, dan cerita menarik di dunia teknologi."
    page_type: post
    count: 5
    filters:
      exclude_featured: false
  design:
    view: date-title-summary

- block: cta-card
  demo: false
  content:
    title: "👉 Hubungi Saya"
    text: |-
      Apakah Anda tertarik untuk berkolaborasi atau sekadar berdiskusi? Hubungi saya melalui:
      
      - 📧 Email: [email@example.com](mailto:email@example.com)
      - 💼 LinkedIn: [linkedin.com/in/username](https://linkedin.com/in/username)
      - 🌐 GitHub: [github.com/username](https://github.com/username)
    button:
      text: "Hubungi Sekarang"
      url: "mailto:email@example.com"
  design:
    card:
      css_class: "bg-primary-700"
      css_style: ""


---
