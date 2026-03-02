<style>
  @keyframes shimmer {
    0% { background-position: -200% 0; }
    100% { background-position: 200% 0; }
  }
  @keyframes fadeIn {
    from { opacity: 0; transform: translateY(10px); }
    to { opacity: 1; transform: translateY(0); }
  }
  .skeleton {
    background: linear-gradient(90deg, #1a1a1a 25%, #2a2a2a 50%, #1a1a1a 75%);
    background-size: 200% 100%;
    animation: shimmer 1.5s infinite, fadeIn 0.5s ease-out forwards;
    border-radius: 20px;
  }
  .skeleton-1 { width: 90.5%; height: 70px; }
  .skeleton-2 { width: 50%; height: 240px; display: inline-block; margin-right: 10px; }
  .skeleton-3 { width: 40%; height: 300px; display: inline-block; }
  .skeleton-4 { width: 45%; height: 200px; display: inline-block; margin-right: 10px; }
  .skeleton-5 { width: 45%; height: 200px; display: inline-block; }
  .content { opacity: 0; animation: fadeIn 0.5s ease-out 0.3s forwards; }
</style>

<h1> Hi there 👋</h1>

<div class="skeleton skeleton-1"></div>
<div class="content">
  <a href="https://spotistats.gomes.lol/">
    <img width="90.5%" style="border-radius:20px;" loading="lazy" onload="this.style.opacity=1;this.previousElementSibling.remove()" src="https://spotistats.gomes.lol/api/now-playing/j97132y5xqh58cwkpzrb4qj7qh822n9e?theme=claude"/>
  </a>
</div>

<div class="content">
  <a href="https://ghs.gomes.lol">
   <img width="50%" style="border-radius:20px;" loading="lazy" onload="this.style.opacity=1;this.previousElementSibling.remove()" src="https://ghs.gomes.lol/api/banner?username=mhfgomes&range=lastmonth&title=ME&subtitle=Last+Month+Stats&show_title=1&show_subtitle=1&items=commits%2Cadditions%2Cdeletions&top=0&w=900&h=240&bg1=%23B05730&bg2=%239C87F5&dir=to-br&text=%23C3C0B6&muted=%23B7B5A9&accent=%23D97757"/>
  </a>
  <a href="https://ghs.gomes.lol/">
    <img width="40%" style="border-radius:20px;" loading="lazy" onload="this.style.opacity=1" src="https://ghs.gomes.lol/api/languages-banner?username=mhfgomes&top=8&w=900&h=300&bg1=%23B05730&bg2=%239C87F5&dir=to-br&text=%23C3C0B6&muted=%23B7B5A9" />
  </a>
</div>

<div class="content">
  <a href="https://spotistats.gomes.lol/">
    <img width="45%" style="border-radius:20px;" loading="lazy" onload="this.style.opacity=1" src="https://spotistats.gomes.lol/api/card/j97132y5xqh58cwkpzrb4qj7qh822n9e?type=artists&theme=claude&range=long_term" />
  </a>
  <a href="https://spotistats.gomes.lol/">
    <img width="45%" style="border-radius:20px;" loading="lazy" onload="this.style.opacity=1" src="https://spotistats.gomes.lol/api/card/j97132y5xqh58cwkpzrb4qj7qh822n9e?type=tracks&theme=claude&range=long_term"/>
  </a>
</div>

<div class="content">
<h3>My favourites</h3>
<div style="display: inline_block"><br>
  <strong>Languages</strong><br>
  <a href="https://dotnet.microsoft.com/en-us/languages/csharp" target="_blank">
    <img
      alt="C#"
      height="30"
      width="40"
      loading="lazy"
      src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-plain.svg"
  /></a>
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank"
    ><img
      alt="JavaScript"
      height="30"
      width="40"
      loading="lazy"
      src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg"
  /></a>
  <a href="https://www.typescriptlang.org/" target="_blank"
    ><img
      alt="TypeScript"
      height="30"
      width="40"
      loading="lazy"
      src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-plain.svg"
  /></a>
  <a href="https://www.python.org/" target="_blank"
    ><img
      alt="Python"
      height="30"
      width="40"
      loading="lazy"
      src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg"
  /></a>
</div>
<div style="display: inline_block"><br>
  <strong>Runtime / Platform</strong><br>
  <a href="https://bun.sh/" target="_blank"
    ><img
      alt="Bun"
      height="30"
      width="40"
      loading="lazy"
      src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/bun/bun-original.svg"
  /></a>
  <a href="https://nodejs.org/" target="_blank"
    ><img
      alt="Node.js"
      height="30"
      width="40"
      loading="lazy"
      src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg"
  /></a>
</div>
<div style="display: inline_block"><br>
  <strong>Frontend</strong><br>
  <a href="https://react.dev/" target="_blank"
    ><img
      alt="React"
      height="30"
      width="40"
      loading="lazy"
      src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg"
  /></a>
  <a href="https://nextjs.org/" target="_blank"
    ><img
      alt="Next.js"
      height="30"
      width="40"
      loading="lazy"
      src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nextjs/nextjs-original.svg"
  /></a>
  <a href="https://tailwindcss.com/" target="_blank"
    ><img
      alt="Tailwind CSS"
      height="30"
      width="40"
      loading="lazy"
      src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/tailwindcss/tailwindcss-original.svg"
  /></a>
</div>
<div style="display: inline_block"><br>
  <strong>Databases</strong><br>
  <a href="https://www.postgresql.org/" target="_blank"
    ><img
      alt="PostgreSQL"
      height="30"
      width="40"
      loading="lazy"
      src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original.svg"
  /></a>
  <a href="https://www.mongodb.com/" target="_blank"
    ><img
      alt="MongoDB"
      height="30"
      width="40"
      loading="lazy"
      src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mongodb/mongodb-original.svg"
  /></a>
  <a href="https://www.mysql.com/" target="_blank"
    ><img
      alt="MySQL"
      height="30"
      width="40"
      loading="lazy"
      src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original.svg"
  /></a>
  <a href="https://mariadb.org/" target="_blank"
    ><img
      alt="MariaDB"
      height="30"
      width="40"
      loading="lazy"
      src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mariadb/mariadb-original.svg"
  /></a>
</div>
<div style="display: inline_block"><br>
  <strong>DevOps</strong><br>
  <a href="https://www.docker.com/" target="_blank"
    ><img
      alt="Docker"
      height="30"
      width="40"
      loading="lazy"
      src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-original.svg"
  /></a>
  <a href="https://kubernetes.io/" target="_blank"
    ><img
      alt="Kubernetes"
      height="30"
      width="40"
      loading="lazy"
      src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/kubernetes/kubernetes-plain.svg"
  /></a>
  <a href="https://github.com/features/actions" target="_blank"
    ><img
      alt="GitHub Actions"
      height="30"
      width="40"
      loading="lazy"
      src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/githubactions/githubactions-original.svg"
  /></a>
</div>
<div style="display: inline_block"><br>
  <strong>OS</strong><br>
  <a href="https://ubuntu.com/" target="_blank"
    ><img
      alt="Ubuntu"
      height="30"
      width="40"
      loading="lazy"
      src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/ubuntu/ubuntu-plain.svg"
  /></a>
  <a href="https://www.debian.org/" target="_blank"
    ><img
      alt="Debian"
      height="30"
      width="40"
      loading="lazy"
      src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/debian/debian-plain.svg"
  /></a>
  <a href="https://www.linux.org/" target="_blank"
    ><img
      alt="Linux"
      height="30"
      width="40"
      loading="lazy"
      src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/linux/linux-original.svg"
  /></a>
</div>
<div style="display: inline_block"><br>
  <strong>Tools</strong><br>
  <a href="https://git-scm.com/" target="_blank"
    ><img
      alt="Git"
      height="30"
      width="40"
      loading="lazy"
      src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg"
  /></a>
</div>
</div>
<br>
<div class="content">
<h3>My Socials</h3>
<div>
  <a href="https://instagram.com/mario.hfg/" target="_blank"><img src="https://img.shields.io/badge/-Instagram-ED088E?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a> 
  <a href="https://discord.com/users/569221225130491905/" target="_blank"><img src="https://img.shields.io/badge/-Discord-7289da?style=for-the-badge&logo=discord&logoColor=white" target="_blank"></a> 
</div>
</div>
