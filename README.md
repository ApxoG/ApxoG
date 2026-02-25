<h1 align="center">Hi 👋, I'm Giorgi Apkhadze</h1>
<h3 align="center">Frontend Architect • Engineering Leader • Product-Minded Builder</h3>
<p align="center">
  <a href="https://apxo.netlify.app/" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-apxo.netlify.app-0A0A0A?style=for-the-badge&logo=netlify&logoColor=00C7B7" alt="portfolio" />
  </a>
  <a href="https://www.linkedin.com/in/giorgi-apkhadze-849b72163/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Giorgi%20Apkhadze-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin" />
  </a>
  <a href="https://x.com/YOUR_TWITTER_HANDLE" target="_blank">
    <img src="https://img.shields.io/badge/X-@YOUR_TWITTER_HANDLE-111111?style=for-the-badge&logo=x&logoColor=white" alt="x/twitter" />
  </a>
</p>
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=apxo&label=Profile%20Views&color=0e75b6&style=flat" alt="visitor badge" />
  <img src="https://img.shields.io/github/followers/apxo?label=Followers&style=flat" alt="followers" />
  <img src="https://img.shields.io/github/stars/apxo?affiliations=OWNER%2CCOLLABORATOR&style=flat" alt="stars" />
</p>
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3000&pause=900&center=true&vCenter=true&width=900&lines=Building+scalable+web+experiences+with+React+%2F+Next.js;Leading+frontend+teams+and+shipping+production+features;Bridging+UX%2C+design+systems%2C+and+engineering+execution" alt="Typing SVG" />
</p>
***👨‍💻 About Me
🔭 I’m currently working on frontend architecture, scalable UI systems, and product delivery workflows
🌱 Expanding deeper into backend integrations / full-stack systems for modern apps
👥 Strong in team leadership, code review, mentoring, and cross-functional collaboration
🎨 I enjoy the intersection of design systems + product thinking + engineering quality
🌐 Portfolio: apxo.netlify.app
***🔥 Current Focus (Streaks / What I'm Working On)
⚡ Shipping production-ready features in React / Next.js
🧱 Improving frontend architecture and codebase maintainability
🎯 Building reusable UI components and design system patterns
🚀 Optimizing performance, responsiveness, and user experience
🤝 Aligning business goals + UX + engineering execution
🔌 Strengthening backend/API integrations (Node.js, services, data flows)
***🛠️ Skills
Frontend Development
<p align="left">
  <img src="https://skillicons.dev/icons?i=html,css,js,ts,react,nextjs,vue,angular,sass,tailwind,chakraui,redux" alt="frontend skills" />
</p>
Backend Development
<p align="left">
  <img src="https://skillicons.dev/icons?i=nodejs,express,firebase,supabase,postgres,mongodb" alt="backend skills" />
</p>
Frameworks / Platforms
<p align="left">
  <img src="https://skillicons.dev/icons?i=react,nextjs,nodejs,express,firebase,supabase,vercel,netlify" alt="frameworks platforms" />
</p>
Software / Tools
<p align="left">
  <img src="https://skillicons.dev/icons?i=figma,ps,ai,git,github,vscode,postman,notion" alt="software tools" />
</p>
Additional Strengths
🧠 Frontend architecture & technical leadership
✨ UX/UI collaboration and product polish
🧪 Code reviews, planning, and delivery processes
📈 Performance optimization & maintainability
***🌐 Connect With Me
<p align="left">
<a href="https://www.linkedin.com/in/giorgi-apkhadze-849b72163/" target="_blank">
  <img src="https://skillicons.dev/icons?i=linkedin" alt="linkedin" />
</a>
<a href="https://x.com/YOUR_TWITTER_HANDLE" target="_blank">
  <img src="https://img.shields.io/badge/X/Twitter-Follow-black?style=for-the-badge&logo=x&logoColor=white" alt="twitter badge" />
</a>
<a href="https://apxo.netlify.app/" target="_blank">
  <img src="https://img.shields.io/badge/Website-Visit%20Portfolio-0A0A0A?style=for-the-badge&logo=google-chrome&logoColor=white" alt="website badge" />
</a>
</p>
***🏆 GitHub Trophy
<p align="left">
  <img src="https://github-profile-trophy.vercel.app/?username=apxo&theme=algolia&no-frame=true&no-bg=true&margin-w=8&row=1" alt="github trophy" />
</p>
***📊 GitHub Stats (Profile / Top Skills / Streak)
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=apxo&show_icons=true&locale=en&theme=transparent&hide_border=true&count_private=true" alt="GitHub profile stats card" height="170" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=apxo&show_icons=true&locale=en&layout=compact&theme=transparent&hide_border=true" alt="Top skills / languages" height="170" />
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com?user=apxo&theme=transparent&hide_border=true" alt="GitHub streak stats" />
</p>
***📚 Latest Dev.to Posts
<!-- DEVTO-BLOG-LIST:START -->
Coming soon...
<!-- DEVTO-BLOG-LIST:END -->
📰 Latest Medium Posts
<!-- MEDIUM-BLOG-LIST:START -->
Coming soon...
<!-- MEDIUM-BLOG-LIST:END -->
🧾 Latest Posts From My Personal Blog
<!-- PERSONAL-BLOG-LIST:START -->
Coming soon...
<!-- PERSONAL-BLOG-LIST:END -->
***⚙️ GitHub Action (Dynamic Blogs)
Create .github/workflows/blog-feeds.yml:
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
          # Replace with your actual RSS feed. Common options:
          # https://apxo.netlify.app/rss.xml
          # https://apxo.netlify.app/feed.xml
          feed_list: "https://apxo.netlify.app/rss.xml"
          max_post_count: "5"
          comment_tag_name: "PERSONAL-BLOG-LIST"
          commit_message: "chore(readme): update personal blog posts"
***✨ Optional Add-ons (Nice Extras)
📈 GitHub activity graph
[![Giorgi's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=apxo&theme=github-compact)](https://github.com/apxo)
🐍 Contribution snake animation (via GitHub Action)
🎵 Spotify “Now Playing” card
⏱️ WakaTime coding stats
📌 Pinned project cards (manual or dynamic)
☕ Support / Buy Me a Coffee badge
***✅ Quick Setup (Replace These)
YOUR_TWITTER_HANDLE
YOUR_DEVTO_USERNAME
YOUR_MEDIUM_USERNAME
https://apxo.netlify.app/rss.xml (if your actual feed path is different)
apxo (only if your GitHub username is different)
***<p align="center">Made with ❤️ and lots of shipped UI.</p>
