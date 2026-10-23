<picture>
  <source media="(max-width: 600px)" srcset="https://monkeydcoder.github.io/readme/banner-mobile.png">
  <source media="(prefers-reduced-motion: reduce)" srcset="https://monkeydcoder.github.io/readme/banner.png">
  <img src="https://monkeydcoder.github.io/readme/banner.gif" width="100%" alt="Satyam Sharma. Reinforcement learning, Institute of Science Tokyo, MEXT Scholar. I build learning agents that work out what matters when the reward almost never comes. Animation: in a MiniGrid DoorKey grid, an agent picks up a key, unlocks a door and reaches the goal; the reward only arrives at the end.">
</picture>

<p align="center">
  <a href="https://monkeydcoder.github.io/"><img alt="Portfolio: monkeydcoder.github.io" src="https://img.shields.io/badge/Portfolio-monkeydcoder.github.io-ff6a4d?style=flat-square&labelColor=2a303d"></a>
  <a href="https://www.linkedin.com/in/satyam-sharma-24463522a/"><img alt="LinkedIn: Satyam Sharma" src="https://img.shields.io/badge/LinkedIn-Satyam%20Sharma-0a66c2?style=flat-square&labelColor=2a303d"></a>
  <a href="mailto:satyamsharma3002@gmail.com"><img alt="Email: satyamsharma3002@gmail.com" src="https://img.shields.io/badge/Email-satyamsharma3002%40gmail.com-5fbf8f?style=flat-square&labelColor=2a303d"></a>
  <a href="https://monkeydcoder.github.io/Satyam_Sharma_Resume.pdf"><img alt="Résumé (PDF)" src="https://img.shields.io/badge/R%C3%A9sum%C3%A9-PDF-f2b84b?style=flat-square&labelColor=2a303d"></a>
</p>

I'm a first-year master's student at the **Institute of Science Tokyo**, researching reinforcement learning in [Prof. Ryutaro Ichise's lab](https://www.ai.iee.eng.isct.ac.jp/), and a **MEXT scholar** (one of 25 Indian nationals selected in 2025).

My research asks what an agent should remember when rewards are rare, and whether it can find the important steps by itself, without anyone telling it what matters.

### Research

<sub>Ongoing master's thesis. The code and data stay private until publication.</sub>

- **Memory as a learning signal.** PPO with swappable memories (a knowledge graph, an episodic memory and a visit counter) behind one potential-based reward-shaping interface. A memory bonus took MiniGrid DoorKey-8x8 from **3 to 22+ successful runs** out of 24 seeds.
- **Finding the important events automatically.** A detector that knows nothing about keys or doors recovered **7 of 7** ground-truth event chains, with **zero false chains** on the control environments.
- **Using discovered chains in training.** A pre-registered test of **3,552 runs**. The detector found the correct chain in **48 of 48 runs** in each of five environments, with no false chain in 432 control runs, and the chain cut PPO's learning time **roughly in half** in UnlockPickup and ObstructedMaze.
- **Now:** closing the gap to a perfect chain, which made PPO **6.5x to 7.5x faster** in those same environments.

[Read the full story on my site →](https://monkeydcoder.github.io/#research)

### Selected projects

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/monkeydcoder/EduMind-AI"><img src="https://monkeydcoder.github.io/readme/edumind.jpg" width="100%" alt="EduMind AI home screen"></a>
      <br><b>EduMind AI</b>
      <br>Exam-prep platform on LLaMA 3 running locally.
      <br><a href="https://github.com/monkeydcoder/EduMind-AI">Code</a> · <a href="https://www.loom.com/share/e604337fc4cf4cd2932a9fc64e80a56c">Demo</a>
    </td>
    <td width="50%" valign="top">
      <a href="https://monkeydcoder.github.io/#projects"><img src="https://monkeydcoder.github.io/readme/reel-vault.jpg" width="100%" alt="Reel Vault pipeline: reel, items, categories, map"></a>
      <br><b>Reel Vault</b>
      <br>Saved Instagram reels turned into mapped, searchable place cards.
      <br><a href="https://monkeydcoder.github.io/#projects">Details</a> · code private
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/monkeydcoder/researchmate-ai"><img src="https://monkeydcoder.github.io/readme/researchmate.jpg" width="100%" alt="ResearchMate AI landing page"></a>
      <br><b>ResearchMate AI</b>
      <br>Research assistant that runs fully locally on Llama 3.
      <br><a href="https://github.com/monkeydcoder/researchmate-ai">Code</a> · <a href="https://www.loom.com/share/f0cf23e5e03546e5875df76d9d26199b">Demo</a>
    </td>
    <td width="50%" valign="top">
      <a href="https://monkeydcoder.github.io/#projects"><img src="https://monkeydcoder.github.io/readme/earth-docker.jpg" width="100%" alt="Earth Docker classifier predicting a diseased cotton leaf"></a>
      <br><b>Earth Docker</b>
      <br>Farm robot with a 98%-accurate disease classifier. Won institute funding.
      <br><a href="https://drive.google.com/file/d/1Da1-jJAbpxZg9HS9e9umZE9I9zp_5iUM/view">Video</a> · <a href="https://monkeydcoder.github.io/#projects">Details</a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/monkeydcoder/KanjiPath"><img src="https://monkeydcoder.github.io/readme/kanjipath.jpg" width="100%" alt="KanjiPath dashboard"></a>
      <br><b>KanjiPath</b>
      <br>JLPT N5 and N4 study app with spaced repetition.
      <br><a href="https://github.com/monkeydcoder/KanjiPath">Code</a>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/monkeydcoder/3js_Portfolio"><img src="https://monkeydcoder.github.io/readme/anime-village.jpg" width="100%" alt="Night-time 3D anime village with a torii gate"></a>
      <br><b>3D Anime Village</b>
      <br>A Three.js walk through an anime village at dusk.
      <br><a href="https://github.com/monkeydcoder/3js_Portfolio">Code</a>
    </td>
  </tr>
</table>

More, including an optimisation course project and my NLP notebooks, on [my portfolio](https://monkeydcoder.github.io/#projects).

### Tools

<p>
  <img src="https://skillicons.dev/icons?i=py,pytorch,tensorflow,sklearn,opencv,linux,docker,git,githubactions&theme=dark&perline=9" alt="Python, PyTorch, TensorFlow, scikit-learn, OpenCV, Linux, Docker, Git, GitHub Actions">
  <br>
  <img src="https://skillicons.dev/icons?i=fastapi,react,ts,nodejs,express,nextjs,tailwind,threejs,raspberrypi&theme=dark&perline=9" alt="FastAPI, React, TypeScript, Node.js, Express, Next.js, Tailwind CSS, Three.js, Raspberry Pi">
</p>

Reinforcement learning: PPO, DQN, SAC, reward shaping, Stable-Baselines3, Gymnasium, MiniGrid.

### Background

- **M.S., Industrial Engineering and Economics**, Institute of Science Tokyo · since April 2026 · GPA 3.83 / 4.5
- **Research student (MEXT)**, Ichise Laboratory · October 2025 to March 2026
- **B.E. (Honours), Computer Science and Engineering**, SLIET, Punjab · 2021 to 2025 · CGPA 8.9 / 10

Off the clock I'm learning Japanese (around JLPT N4), hiking, skiing, and keeping up with One Piece.
