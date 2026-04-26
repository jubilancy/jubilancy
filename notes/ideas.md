# Sofa Markdown Export - 3/14/26
## The Pile
- [ ] Stuff You Should Know (Podcast)
- [ ] The Mel Robbins Podcast (Podcast)
- [ ] Pod Save America (Podcast)
- [ ] Candace (Podcast)
- [ ] Good Hang with Amy Poehler (Podcast)
- [ ] Up First from NPR (Podcast)
- [ ] The Daily (Podcast)

---

## My Lists

### Apps to Check Out

### Books to Read

### Games to Play

### Movies & Shows to Watch
- [ ] Dexter (TV Show)
- [ ] Dexter: Resurrection (TV Show)

### Things to Listen To

### test

---

## Activity




- 👋 Hi, I’m @CelloSerenity
- 👀 I’m interested in ... AppleOS sideloading, emulation, repurposing tech, writing documentation
- 🌱 I’m currently learning ... whatever comes up on GitHub, working on CompTIA certification
- 💞️ I’m looking to collaborate on ... any of my PRs
- 📫 How to reach me ... drop an issue [here](https://github.com/CelloSerenity/GetInTouch/issues/new)
- 😄 Pronouns: ... he/him

Languages:
- Python
- HTML/CSS
- Markdown
- SQLLite
- Git

My iOS/iPadOS recommended sideloading setup:

Free Edition (Requires a PC):

App Signer/Sideloader: SideStore. Sideloaded apps: LiveContainer, StikDebug.

Visuals (because why not):
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=CelloSerenity&theme=github_dark" />
    <img src="http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=CelloSerenity&theme=github" width="66%" />
  </picture>
  
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="http://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=CelloSerenity&theme=github_dark&exclude=mdx" />
  <img src="http://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=CelloSerenity&theme=github&exclude=mdx" width="32%" />
</picture>
</div>


—-

## Welcome to Kanaries Open Source Community 👋

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->


Kanaries is an open source startup that focus on data exploration and data visualization. We build softwares that automates the workflow of data exploration to help users to understand data better and faster.

### AI Agent For Jupyter

https://github.com/user-attachments/assets/412111f6-74f7-4029-9de8-5235cd6b4e47

[runcell.dev](https://www.runcell.dev) is an AI Code Agent for Jupyter built by Kanaries. It can understand your code, cells and visuals in jupyter and then generate code / run cells for you in your jupyter.



### Open Source Family

| Solution | Description | Image |
| - | - | - |
| [runcell](https://runcell.dev) | Jupyter AI Code Agent (Cursor for Jupyter) | ![Jupyter AI Agent](https://jqrndeeuvnuryysu.public.blob.vercel-storage.com/assets/runcell-cover-gGf9HQ1LvgfLSkyIfEx47xlj2zeoe5.png) |
| [Graphic Walker](https://kanaries.net/graphic-walker) | Embeddable analytic solution, embed an interactive visual analytic component in your system. | ![graphic-walker-banner](https://pub-8e7aa5bf51e049199c78b4bc744533f8.r2.dev/graphic-walker-banner202402.png) |
| [PyGWalker](https://kanaries.net/pygwalker) | Turn your data into an interactive UI for data exploration. It allows you to visualize your data with simple drag-and-drop operations. | ![pygwalker-banner-gh](https://github.com/Kanaries/.github/assets/22167673/427e5ded-f6a7-407e-9312-d439319c6fb0) |
| [Rath](https://kanaries.net/rath) | An automatic Exploratory Data Analysis(auto-EDA) system which helps extract insights and generate charts and interactive dashboard. | ![](https://docs-us.oss-us-west-1.aliyuncs.com/images/readme/rath-main-banner2.png) |



### Social Media
[![](https://img.shields.io/badge/twitter-kanaries_data-03A9F4?style=flat-square&logo=twitter)](https://twitter.com/kanaries_data)
[![](https://img.shields.io/discord/987366424634884096?color=%237289da&label=Discord&logo=discord&logoColor=white&style=flat-square)](https://discord.gg/WWHraZ8SeV)
[![](https://img.shields.io/badge/YouTube-red?style=flat-square&logo=youtube&logoColor=white)](https://www.youtube.com/@kanaries_data)
[![](https://img.shields.io/badge/LinkedIn-blue?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/company/kanaries-data/)

### Resources

+ [Kanaries Website](https://kanaries.net)
+ [Kanaries PyGWalker](https://kanaries.net/pygwalker)
+ [Kanaries Docs](https://docs.kanaries.net)



—--

# lowlighter plugins list
## visit https://github.com/lowlighter/metrics#-documentation for full reference
name: Metrics
on:
  schedule: [{cron: "0 * * * *"}]
  workflow_dispatch:
  push: {branches: ["master", "main"]}
jobs:
  github-metrics:
    runs-on: ubuntu-latest
    permissions:
      contents: write
    steps:
      - uses: lowlighter/metrics@latest
        with:
          token: ${{ secrets.METRICS_TOKEN }}
          user: jubilancy
          template: terminal
          base: header, activity, community, repositories, metadata
          
          # 🗃️ Base Content & 🧱 Core
          base_indepth: yes
          
          # 🏆 Achievements
          plugin_achievements: yes
          
          # 📰 Recent activity
          plugin_activity: yes
          
          # 📆 Commit calendar
          plugin_calendar: yes
          
          # ♐ Random code snippet
          plugin_code: yes
          
          # 🏅 Repository contributors
          plugin_contributors: yes
          
          # 💬 Discussions
          plugin_discussions: yes
          
          # 🎟️ Follow-up
          plugin_followup: yes
          
          # 🎫 Gists
          plugin_gists: yes
          
          # 💡 Coding habits
          plugin_habits: yes
          plugin_habits_charts: yes
          
          # 🙋 Introduction
          plugin_introduction: yes
          
          # 📅 Isometric commit calendar
          plugin_isocalendar: yes
          
          # 🈷️ Languages activity
          plugin_languages: yes
          
          # 📜 Repository licenses
          plugin_licenses: yes
          
          # 👨‍💻 Lines of code changed
          plugin_lines: yes
          
          # 🎩 Notable contributions
          plugin_notable: yes
          
          # 🧑‍🤝‍🧑 People
          plugin_people: yes
          
          # 🗂️ GitHub projects
          plugin_projects: yes
          
          # 🎭 Comment reactions
          plugin_reactions: yes
          
          # 📓 Featured repositories
          plugin_repositories: yes
          
          # 🌇 GitHub Skyline
          plugin_skyline: yes
          
          # 💕 GitHub Sponsors
          plugin_sponsors: yes
          
          # 💝 GitHub Sponsorships
          plugin_sponsorships: yes
          
          # ✨ Stargazers
          plugin_stargazers: yes
          
          # 💫 Star lists
          plugin_starlists: yes
          
          # 🌟 Recently starred
          plugin_stars: yes
          
          # 💭 GitHub Community Support (⚠️ Deprecated)
          plugin_support: yes
          
          # 📌 Starred topics
          plugin_topics: yes
          
          # 🧮 Repositories traffic
          plugin_traffic: yes
          
          # 🌸 Anilist (Public)
          plugin_anilist: yes
          plugin_anilist_user: jubilancy
          
          # 🗳️ Leetcode (Public)
          plugin_leetcode: yes
          plugin_leetcode_user: jubilancy
          
          # 🎼 Music (Requires Spotify/Lastfm Secret)
          # plugin_music: yes
          # plugin_music_provider: spotify
          
          # ⏱️ Google PageSpeed (Requires API Key)
          # plugin_pagespeed: yes
          
          # ✒️ Recent posts (Public)
          plugin_posts: yes
          plugin_posts_source: dev.to
          plugin_posts_user: jubilancy
          
          # 🗼 Rss feed (Public)
          plugin_rss: yes
          plugin_rss_source: https://www.etymonline.com/feed/columns.xml
          
          # 🗨️ Stack Overflow (Public ID)
          plugin_stackoverflow: yes
          plugin_stackoverflow_user: 1
          
          # 🕹️ Steam (Public ID)
          plugin_steam: yes
          plugin_steam_user: "76561198034505678"
          
          # 🐤 Latest tweets (⚠️ Deprecated/Requires Twitter Secret)
          # plugin_tweets: yes
          # plugin_tweets_token: ${{ secrets.TWITTER_TOKEN }}
          
          # ⏰ WakaTime (Requires API Key)
          # plugin_wakatime: yes
          # plugin_wakatime_token: ${{ secrets.WAKATIME_TOKEN }}
          
          # 🧠 16personalities (Public)
          plugin_16personalities: yes
          
          # ♟️ Chess (Public)
          plugin_chess: yes
          plugin_chess_user: jubilancy
          
          # 🪙 Crypto (Public)
          plugin_crypto: yes
          
          # 🥠 Fortune (Public)
          plugin_fortune: yes
          
          # 💉 Nightscout (Requires Instance URL/Secret)
          # plugin_nightscout: yes
          # plugin_nightscout_url: ${{ secrets.NIGHTSCOUT_URL }}
          
          # 💩 PoopMap (Public Username)
          plugin_poopmap: yes
          plugin_poopmap_user: jubilancy
          
          # 📸 Website screenshot (Public)
          plugin_screenshot: yes
          plugin_screenshot_url: https://eliana.lol
          
          # 🦑 Splatoon (Requires Session Secret)
          # plugin_splatoon: yes
          
          # 💹 Stock prices (Requires API Key)
          # plugin_stock: yes
          # plugin_stock_token: ${{ secrets.STOCK_TOKEN }}
          
          # 🧪 Support (Public)
          plugin_support: yes
<br>
🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️🗂️
<br>

# hello world!



<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=astro,cloudflare,codepen,golang,html,css,js,py,markdown,obsidian,r,react,svg,npm&perline=7" />
  </a>
</p>

<table><tbody><tr><td><a href="https://octo-ring.com/"><img src="https://octo-ring.com/static/img/widget/top.png" width="99%" alt="Octo Ring logo" align="top"></a><br><a href="https://octo-ring.com/p/jubilancy/prev"><img src="https://octo-ring.com/static/img/widget/prev.png" width="33%" alt="previous" align="top" title="previous profile"></a><a href="https://octo-ring.com/p/jubilancy/random"><img src="https://octo-ring.com/static/img/widget/random.png" width="33%" alt="random" align="top" title="random profile"></a><a href="https://octo-ring.com/p/jubilancy/next"><img src="https://octo-ring.com/static/img/widget/next.png" width="33%" alt="next" align="top" title="next profile"></a><br><a href="https://octo-ring.com/"><img src="https://octo-ring.com/static/img/widget/bottom.png" width="99%" alt="check out other GitHub profiles in the Octo Ring" align="top"></a></td></tr></tbody></table>


<p align="left"> <img src="https://komarev.com/ghpvc/?username=jubilancy&label=Profile%20views&color=0e75b6&style=flat" alt="jubilancy" /> </p>

<p align="left"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=jubilancy" alt="jubilancy" /></a> </p>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=jubilancy&show_icons=true&locale=en&layout=compact" alt="jubilancy" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=jubilancy&show_icons=true&locale=en" alt="jubilancy" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=jubilancy&" alt="jubilancy" /></p>
