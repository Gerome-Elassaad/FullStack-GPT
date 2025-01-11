<p align="center">
</p>
<p align="center">
  <em>🤖 Assemble, configure, and deploy autonomous AI Agent(s) in your browser. 🤖   </em>
</p>
<p align="center">
    <img alt="Node version" src="https://img.shields.io/static/v1?label=node&message=%20%3E=18&logo=node.js&color=2334D058" />
      <a href="https://github.com/Repo_Booster/Repo-Booster/blob/master/README.md"><img src="https://img.shields.io/badge/lang-English-blue.svg" alt="English"></a>
  <a href="https://github.com/Repo_Booster/Repo-Booster/blob/master/docs/README.zh-HANS.md"><img src="https://img.shields.io/badge/lang-简体中文-red.svg" alt="简体中文"></a>
  <a href="https://github.com/Repo_Booster/Repo-Booster/blob/master/docs/README.hu-Cs4K1Sr4C.md"><img src="https://img.shields.io/badge/lang-Hungarian-red.svg" alt="Hungarian"></a>
</p>

<p align="center">
<a href="https://Repo-Booster.Repo_Booster.ai">🔗 Short link</a>
<span>&nbsp;&nbsp;•&nbsp;&nbsp;</span>
<a href="https://docs.Repo_Booster.ai/">📚 Docs</a>
<span>&nbsp;&nbsp;•&nbsp;&nbsp;</span>
<a href="https://docs.Repo_Booster.ai/essentials/contributing">🤝 Contribute</a>
<span>&nbsp;&nbsp;•&nbsp;&nbsp;</span>
<a href="https://twitter.com/Repo_Boosterai">🐦 Twitter</a>
<span>&nbsp;&nbsp;•&nbsp;&nbsp;</span>
<a href="https://discord.gg/gcmNyAAFfV">📢 Discord</a>
</p>

Repo-Booster allows you to configure and deploy Autonomous AI agents.
Name your own custom AI and have it embark on any goal imaginable.
It will attempt to reach the goal by thinking of tasks to do, executing them, and learning from the results 🚀.

---

## ✨ Demo
For the best demo experience, try [our site](https://Repo-Booster.Repo_Booster.ai) directly :)

[Demo Video](https://github.com/Repo_Booster/Repo-Booster/assets/50181239/5348e44a-29a5-4280-a06b-fe1429a8d99e)


## 👨‍🚀 Getting Started

The easiest way to get started with Repo-Booster is automatic setup CLI bundled with the project.
The cli sets up the following for Repo-Booster:
- 🔐 [Environment variables](https://github.com/Repo_Booster/Repo-Booster/blob/main/.env.example) (and API Keys)
- 🗂️ [Database](https://github.com/Repo_Booster/Repo-Booster/tree/main/db) (Mysql)
- 🤖 [Backend](https://github.com/Repo_Booster/Repo-Booster/tree/main/platform) (FastAPI)
- 🎨 [Frontend](https://github.com/Repo_Booster/Repo-Booster/tree/main/next) (Nextjs)

## Prerequisites :point_up:

Before you get started, please make sure you have the following installed:

- An editor of your choice. For example, [Visual Studio Code (VS Code)](https://code.visualstudio.com/download)
- [Node.js](https://nodejs.org/en/download)
- [Git](https://git-scm.com/downloads)
- [Docker](https://www.docker.com/products/docker-desktop). After installation, please create an account, open up the Docker application, and sign in.
- An [OpenAI API key](https://platform.openai.com/signup)
- A [Serper API Key](https://serper.dev/signup) (optional)
- A [Replicate API Token](https://replicate.com/signin) (optional)

## Getting Started :rocket:
1. **Open your editor**

2. **Open the Terminal** - Typically, you can do this from a 'Terminal' tab or by using a shortcut
   (e.g., `Ctrl + ~` for Windows or `Control + ~` for Mac in VS Code).

3. **Clone the Repository and Navigate into the Directory** - Once your terminal is open, you can clone the repository and move into the directory by running the commands below.

   **For Mac/Linux users** :apple: :penguin:
   ```bash
   git clone https://github.com/Repo_Booster/Repo-Booster.git
   cd Repo-Booster
   ./setup.sh
   ```
   **For Windows users** :windows:
   ```bash
   git clone https://github.com/Repo_Booster/Repo-Booster.git
   cd Repo-Booster
   ./setup.bat
   ```
4. **Follow the setup instructions from the script** - add the appropriate API keys, and once all of the services are running, travel to [http://localhost:3000](http://localhost:3000) on your web-browser.

Happy hacking! :tada:

## 🎉 Roadmap

This platform is currently in beta, a full list of completed and planed features can be found on
our [public roadmap](https://docs.Repo_Booster.ai/essentials/roadmap).


## 🚀 Tech Stack

- ✅ **Bootstrapping**: [create-t3-app](https://create.t3.gg) + [FastAPI-template](https://github.com/s3rius/FastAPI-template).
- ✅ **Framework**: [Nextjs 13 + Typescript](https://nextjs.org/) + [FastAPI](https://fastapi.tiangolo.com/)
- ✅ **Auth**: [Next-Auth.js](https://next-auth.js.org)
- ✅ **ORM**: [Prisma](https://prisma.io) & [SQLModel](https://sqlmodel.tiangolo.com/).
- ✅ **Database**: [Planetscale](https://planetscale.com/).
- ✅ **Styling**: [TailwindCSS + HeadlessUI](https://tailwindcss.com).
- ✅ **Schema Validation**: [Zod](https://github.com/colinhacks/zod) + [Pydantic](https://docs.pydantic.dev/).
- ✅ **LLM Tooling**: [Langchain](https://github.com/hwchase17/langchain).
