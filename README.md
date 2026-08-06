<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:38bdf8,100:764ABC&height=200&section=header&text=Fatma%20Gamal&fontSize=45&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Frontend%20Developer%20%7C%20Angular%20%26%20React%20%7C%20Full%20Stack%20with%20Node.js&descAlignY=55&descSize=18" width="100%"/>

<a href="https://github.com/fatmaindex">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=22&duration=3000&pause=800&color=38BDF8&center=true&vCenter=true&width=600&lines=Turning+designs+into+real-time+web+experiences;Clean+Code+%7C+SOLID+Principles+%7C+Scalable+Architecture;Angular+18%2B+%7C+React.js+%7C+Node.js+%2B+Express" alt="Typing SVG" />
</a>

</div>

---

## 👩‍💻 About Me

🎯 Frontend Developer specialized in **Angular 18+** and **React.js**, with a Full Stack layer built on **Node.js** and **Express**.

Clean, maintainable code and **SOLID principles** are non-negotiable — every project is built to be read and extended by someone else, not just to work. Most of the work lives at the intersection of frontend polish and real-time systems: **REST APIs, WebSockets, and live data flows** that actually hold up under bad network conditions.

**Currently exploring:**
- 🏙️ Real-time dashboards powered by WebSocket & Socket.io
- 🎨 Scalable, reusable UI components across Angular & React
- 🔗 End-to-end integration with Node.js & Express backends
- 🤖 AI tools & prompt engineering to build faster, smarter

---

## 🚀 Tech Stack

### Languages
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### Frontend
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![RxJS](https://img.shields.io/badge/RxJS-B7178C?style=for-the-badge&logo=reactivex&logoColor=white)
![Redux Toolkit](https://img.shields.io/badge/Redux%20Toolkit-764ABC?style=for-the-badge&logo=redux&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack%20Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-000000?style=for-the-badge)

### Styling
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Sass](https://img.shields.io/badge/SASS-CC6699?style=for-the-badge&logo=sass&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![Angular Material](https://img.shields.io/badge/Angular%20Material-FF6F00?style=for-the-badge&logo=angular&logoColor=white)

### Backend
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socket.io&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

### Tools
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

<img height="165em" src="https://github-readme-stats.vercel.app/api?username=fatmaindex&show_icons=true&theme=tokyonight&hide_border=true&count_private=true"/>
<img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=fatmaindex&layout=compact&theme=tokyonight&hide_border=true"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=fatmaindex&theme=tokyonight&hide_border=true" width="65%"/>

</div>

> ⚠️ Replace `fatmaindex` above with your exact GitHub username if it's different — these widgets pull live data straight from your GitHub account, no setup needed.

---

## 🐍 Contribution Snake (optional, animated)

A nice extra touch: a snake that "eats" your contribution graph, generated automatically by a GitHub Action.

1. Add this workflow file to your profile repo at `.github/workflows/snake.yml`:

```yaml
name: Generate Snake
on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
  push:
    branches: [ main ]

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-snake.svg
            dist/github-snake-dark.svg?palette=github-dark
      - uses: actions/upload-artifact@v4
        with:
          name: github-snake
          path: dist/*.svg
      - uses: peaceiris/actions-gh-pages@v3
        with:
          github_token: ${{ secrets.GITHUB_TOKEN }}
          publish_branch: output
          publish_dir: ./dist
```

2. Then embed it here:

```md
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/fatmaindex/fatmaindex/output/github-snake-dark.svg" />
  <img alt="snake" src="https://raw.githubusercontent.com/fatmaindex/fatmaindex/output/github-snake.svg" />
</picture>
```

Once the Action runs once, the snake animates automatically every day — no manual updates needed.

---

## 🎓 Education

**Bachelor of Engineering — Systems & Computer Engineering** (2021–2026)
**Al-Azhar University, Cairo**

---

## 📫 Connect with Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](http://linkedin.com/in/fatma-gamal-dev)
[![Gmail](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:fatmagamal.webdev@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](http://fatmaindex.github.io/My-Portfolio)

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:764ABC,100:38bdf8&height=100&section=footer" width="100%"/>
