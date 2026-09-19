<div align="center">

<!-- ============ TYPING + ORBS ============ -->
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=800&size=30&duration=2800&pause=700&color=22D3EE&center=true&vCenter=true&multiline=true&width=520&height=60&lines=ThomasArya%20%F0%9F%91%8B;typed.dev%20%7C%20owner" alt="Typing SVG" />

<svg width="240" height="36" viewBox="0 0 240 36" xmlns="http://www.w3.org/2000/svg">
  <circle cx="18" cy="18" r="6" fill="#22D3EE">
    <animate attributeName="r" values="6;9;6" dur="1.2s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="1;0.3;1" dur="1.2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="120" cy="18" r="6" fill="#A855F7">
    <animate attributeName="r" values="6;9;6" dur="1.2s" begin="0.3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="1;0.3;1" dur="1.2s" begin="0.3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="222" cy="18" r="6" fill="#22D3EE">
    <animate attributeName="r" values="6;9;6" dur="1.2s" begin="0.6s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="1;0.3;1" dur="1.2s" begin="0.6s" repeatCount="indefinite"/>
  </circle>
</svg>

<svg width="320" height="10" viewBox="0 0 320 10" xmlns="http://www.w3.org/2000/svg">
  <rect x="0" y="3" width="320" height="4" rx="2" fill="#0D1117">
    <animate attributeName="fill" values="#22D3EE;#A855F7;#22D3EE" dur="4s" repeatCount="indefinite"/>
  </rect>
</svg>

<br />

<!-- ============ GRAPH ============ -->
<img src="https://github-readme-activity-graph.vercel.app/graph?username=ThomasArya&theme=react-dark&bg_color=0D1117&hide_border=true&height=260" alt="Activity" />

<br />
<br />

<!-- ============ STATS ============ -->
<a href="https://github.com/ThomasArya">
  <img height="165em" src="https://github-readme-stats.vercel.app/api?username=ThomasArya&show_icons=true&theme=react&include_all_commits=true&count_private=true&hide_border=true&hide_title=true" alt="Stats" />
  <img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ThomasArya&layout=compact&langs_count=7&theme=react&hide_border=true&hide_title=true" alt="Languages" />
</a>

<br />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=ThomasArya&theme=react&hide_border=true&fire=22D3EE&ring=22D3EE&currStreakLabel=22D3EE" alt="Streak" />

<br />
<br />

<!-- ============ PROGRESS BARS ============ -->
<svg width="560" height="230" viewBox="0 0 560 230" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="neon" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#22D3EE"/><stop offset="100%" stop-color="#A855F7"/>
    </linearGradient>
  </defs>

  <rect x="0" y="0" width="540" height="16" rx="8" fill="#161B22"/>
  <rect x="0" y="0" width="0" height="16" rx="8" fill="url(#neon)">
    <animate attributeName="width" values="0;486;486" dur="2.5s" begin="0.2s" fill="freeze"/>
  </rect>

  <rect x="0" y="42" width="540" height="16" rx="8" fill="#161B22"/>
  <rect x="0" y="42" width="0" height="16" rx="8" fill="url(#neon)">
    <animate attributeName="width" values="0;432;432" dur="2.5s" begin="0.4s" fill="freeze"/>
  </rect>

  <rect x="0" y="84" width="540" height="16" rx="8" fill="#161B22"/>
  <rect x="0" y="84" width="0" height="16" rx="8" fill="url(#neon)">
    <animate attributeName="width" values="0;405;405" dur="2.5s" begin="0.6s" fill="freeze"/>
  </rect>

  <rect x="0" y="126" width="540" height="16" rx="8" fill="#161B22"/>
  <rect x="0" y="126" width="0" height="16" rx="8" fill="url(#neon)">
    <animate attributeName="width" values="0;351;351" dur="2.5s" begin="0.8s" fill="freeze"/>
  </rect>

  <rect x="0" y="168" width="540" height="16" rx="8" fill="#161B22"/>
  <rect x="0" y="168" width="0" height="16" rx="8" fill="url(#neon)">
    <animate attributeName="width" values="0;324;324" dur="2.5s" begin="1.0s" fill="freeze"/>
  </rect>
</svg>

<br />
<br />

<!-- ============ STACK ============ -->
<img src="https://skillicons.dev/icons?i=html,css,js,ts,react,nextjs,tailwind&perline=7" />
<br />
<img src="https://skillicons.dev/icons?i=nodejs,express,go,rust,docker,postgres,mongodb&perline=7" />

<br />
<br />

<!-- ============ TROPHY ============ -->
<img src="https://github-profile-trophy.vercel.app/?username=ThomasArya&theme=nord&no-frame=true&row=2&column=3" alt="Trophy" />

<br />
<br />

<!-- ============ SNAKE ============ -->
<img src="https://raw.githubusercontent.com/ThomasArya/ThomasArya/output/github-contribution-grid-snake-dark.svg" alt="Snake" />

<br />

<img src="https://komarev.com/ghpvc/?username=ThomasArya&color=22D3EE&style=flat-square" alt="Views" />

</div>

<details>
<summary><b>workflow</b></summary>

```yaml
name: snake

on:
  schedule: [{ cron: "0 */6 * * *" }]
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    permissions: { contents: write }
    steps:
      - uses: actions/checkout@v3
      - uses: Platane/snk@v3
        with:
          github_user_name: ThomasArya
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v3
        with: { target_branch: output, build_dir: dist }
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

</details>