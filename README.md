# Hi, I'm Giorgi Apkhadze 👋

<div align="left">

[![Profile Views](https://komarev.com/ghpvc/?username=ApxoG&style=flat-square&color=0ea5e9)](https://github.com/ApxoG)
[![GitHub Followers](https://img.shields.io/github/followers/ApxoG?label=Followers&style=flat-square)](https://github.com/ApxoG?tab=followers)
[![GitHub Stars](https://img.shields.io/github/stars/ApxoG?label=Stars&style=flat-square)](https://github.com/ApxoG?tab=repositories)

[![X (Twitter)](https://img.shields.io/badge/X-@YOUR_TWITTER_HANDLE-111111?style=flat-square&logo=x)](https://x.com/YOUR_TWITTER_HANDLE)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Giorgi%20Apkhadze-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/giorgi-apkhadze-849b72163/)
[![Portfolio](https://img.shields.io/badge/Portfolio-apxo.netlify.app-22c55e?style=flat-square&logo=vercel&logoColor=white)](https://apxo.netlify.app/)

</div>

---

## 🚀 About Me

I’m a **Front-End Architect / Engineering Leader** focused on building **scalable, high-performance web applications** with strong UX and clean engineering standards.

- 🔭 Currently working on **frontend architecture**, **product UX/UI**, and **team leadership**
- 🧠 Strong focus on **React / Next.js ecosystems**, performance, and maintainable systems
- 👥 Experienced in **code reviews**, client communication, planning, and cross-functional collaboration
- 🎨 Comfortable bridging **engineering + design** (Figma, UI systems, polished product experiences)

---

## 🧩 What I’m Working On (Streaks + Focus)

- ⚡ Shipping **production-ready features** in **React / Next.js**
- 🏗️ Improving **frontend architecture**, code quality, and team workflows
- 🎯 Building better **UI systems / reusable components**
- 🤝 Combining **business goals + UX + engineering execution**
- 🌐 Expanding into **full-stack/backend integrations** for modern web apps

---

## 🛠️ Skills

### Frontend Development
<p>
  <img src="https://skillicons.dev/icons?i=html,css,js,ts,react,nextjs,sass,tailwind,chakraui,threejs" />
</p>

### Backend Development
<p>
  <img src="https://skillicons.dev/icons?i=nodejs,express,firebase" />
  <!-- Add more if needed: postgres,mongodb,supabase,graphql -->
</p>

### Frameworks / Libraries / Platforms
<p>
  <img src="https://skillicons.dev/icons?i=react,nextjs,nodejs,express,firebase" />
</p>

### Software / Tools
<p>
  <img src="https://skillicons.dev/icons?i=figma,git,github,vscode,notion" />
</p>

### Additional Exposure / Interests
- ✨ GSAP (animations)
- 🌐 Web3.js / Solana / Rust / Solidity
- ⚙️ Performance optimization
- 🧱 Frontend architecture & leadership

---

## 🏆 GitHub Trophy
<p>
  <img src="https://github-profile-trophy.vercel.app/?username=ApxoG&theme=onedark&no-frame=true&margin-w=10" />
</p>

---

## 📊 GitHub Stats

<p>
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=ApxoG&show_icons=true&include_all_commits=true&count_private=true" alt="GitHub Stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ApxoG&layout=compact&langs_count=10" alt="Top Languages" />
</p>

### 🔥 GitHub Streak
<p>
  <img height="170" src="https://streak-stats.demolab.com?user=ApxoG" alt="GitHub Streak" />
</p>

---

## 🌍 Socials

- 💼 LinkedIn: https://www.linkedin.com/in/giorgi-apkhadze-849b72163/
- 🌐 Portfolio: https://apxo.netlify.app/
- 🐦 X / Twitter: https://x.com/YOUR_TWITTER_HANDLE
- ✍️ Dev.to: https://dev.to/YOUR_DEVTO_USERNAME
- 📝 Medium: https://medium.com/@YOUR_MEDIUM_USERNAME

---

## 📚 Latest Dev.to Blogs
<!-- DEVTO-BLOG-LIST:START -->
Coming soon...
<!-- DEVTO-BLOG-LIST:END -->

## 📰 Latest Medium Blogs
<!-- MEDIUM-BLOG-LIST:START -->
Coming soon...
<!-- MEDIUM-BLOG-LIST:END -->

## 🧾 Latest Posts From My Personal Blog
<!-- PERSONAL-BLOG-LIST:START -->
Coming soon...
<!-- PERSONAL-BLOG-LIST:END -->

---

## ⚙️ Dynamic Blog Updates (GitHub Actions)

Create a workflow file at: `.github/workflows/blog-feeds.yml`

```yml
name: Update Blog Feeds in README
on:
  schedule:
    - cron: "0 */12 * * *" # every 12 hours
  workflow_dispatch:

permissions:
  contents: write

jobs:
  update-devto:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: gautamkrishnar/blog-post-workflow@v1
        with:
          feed_list: "https://dev.to/feed/YOUR_DEVTO_USERNAME"
          max_post_count: "5"
          comment_tag_name: "DEVTO-BLOG-LIST"
          commit_message: "chore(readme): update dev.to posts"

  update-medium:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: gautamkrishnar/blog-post-workflow@v1
        with:
          # Use ONE of these depending on your Medium setup:
          # https://medium.com/feed/@YOUR_MEDIUM_USERNAME
          # https://medium.com/feed/YOUR_PUBLICATION_NAME
          feed_list: "https://medium.com/feed/@YOUR_MEDIUM_USERNAME"
          max_post_count: "5"
          comment_tag_name: "MEDIUM-BLOG-LIST"
          commit_message: "chore(readme): update medium posts"

  update-personal-blog:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: gautamkrishnar/blog-post-workflow@v1
        with:
          feed_list: "https://yourdomain.com/rss.xml"
          max_post_count: "5"
          comment_tag_name: "PERSONAL-BLOG-LIST"
          commit_message: "chore(readme): update personal blog posts"
