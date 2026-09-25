<p align="center">
  <img src="./assets/header.svg" alt="Ekansh Goyal — Distributed systems, NLP research, Computational linguistics" width="100%">
</p>

<p align="center">
  <a href="https://ekanshgoyal.vercel.app"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-ekanshgoyal.vercel.app-0d1117?style=for-the-badge&logo=vercel&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/ekansh-goyal-cs"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Ekansh%20Goyal-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:ekansh0301@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-ekansh0301%40gmail.com-238636?style=for-the-badge&logo=gmail&logoColor=white"></a>
</p>

---

### Hi, I'm Ekansh

I work where systems engineering meets language. Most of what I build starts from first principles: a Dynamo-style store to understand consistency, an xv6 scheduler to understand the kernel, a Mixture-of-Experts transformer to understand routing. My research looks at how language models pick up meaning that is spread across long, complex text rather than sitting in a few words.

- **Now**: Undergraduate researcher at the Language Technologies Research Centre (LTRC), IIIT Hyderabad
- **Studying**: B.Tech in Computer Science + MS in Computational Linguistics
- **Building**: distributed systems, low-level C, and ML that runs on constrained hardware
- **Ask me about**: replication and consistency, OS internals, RL fine-tuning for LLMs, computational narrative

---

### Selected work

<table>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/Ekansh0301/QuorumKV">QuorumKV</a></h4>
      Leaderless, Dynamo-style key-value store. Gossip membership over a consistent hash ring, tunable N/R/W quorums, vector clocks, hinted handoff and Merkle-tree anti-entropy keep it available through network partitions.
      <br><br><code>Python</code> <code>Redis</code> <code>Distributed Systems</code>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/Ekansh0301/Fault-Tolerant-Distributed-Storage-System">Distributed File System</a></h4>
      Concurrent DFS in C that splits metadata and data planes: a trie-indexed naming server behind an LRU cache, direct client-to-storage TCP streaming, and 3-way async replication for zero data loss on crash.
      <br><br><code>C</code> <code>POSIX Threads</code> <code>TCP/IP</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/Ekansh0301/Voxd">Voxd</a></h4>
      Fully offline voice assistant for Ubuntu. Whisper speech-to-text, Ollama tool calling and Piper speech synthesis share a 4GB laptop GPU, with a deterministic router that skips the LLM for frequent commands.
      <br><br><code>Python</code> <code>Ollama</code> <code>Whisper</code>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/Ekansh0301/Dropout-Squad">Multi-Critic RL for LLMs</a></h4>
      Fine-tunes Phi-2 into a Dungeon Master with PPO and 4-bit QLoRA, scored by four specialized critics with intent-conditioned reward weighting. Cuts GPU memory from 11GB to 3.5GB and beats the supervised baseline by 48.3%.
      <br><br><code>PyTorch</code> <code>PPO</code> <code>QLoRA</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/Ekansh0301/CryptoStack">CryptoStack</a></h4>
      Twenty cryptographic primitives on the Python standard library alone, from AES and RSA up to 2-party MPC via oblivious transfer, behind a 50-endpoint sandbox for running real attacks against each one.
      <br><br><code>Python</code> <code>FastAPI</code> <code>React</code>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/Ekansh0301/XV6-and-C-Shell">xv6 Kernel + C Shell</a></h4>
      xv6 RISC-V kernel extended with an MLFQ scheduler, lazy copy-on-write fork and user-level alarms, alongside a POSIX-style shell with pipelines, I/O redirection and signal handling.
      <br><br><code>C</code> <code>RISC-V</code> <code>Operating Systems</code>
    </td>
  </tr>
</table>

<p align="center"><sub>More in <a href="https://github.com/Ekansh0301/sparse-moe-summarization">sparse-moe-summarization</a> · <a href="https://github.com/Ekansh0301?tab=repositories">all repositories</a></sub></p>

---

### Publications

<img alt="EMNLP 2026" src="https://img.shields.io/badge/EMNLP-2026%20Main-8957e5?style=flat-square"> **An Interpretable Linguistically-Grounded Analysis of Scene Saliency in Movie Screenplays**
<br><sub>Dual-stream model fusing a frozen BERT encoder with psycholinguistic and discourse features through adaptive gating. Salient-scene recall 51.6% → 68.3%, +3.67 ROUGE-1 on downstream summarization.</sub>

<img alt="SemEval 2026" src="https://img.shields.io/badge/SemEval-@ACL%202026-8957e5?style=flat-square"> **Truth Gradient: Mean Pooling and Narrative Density for Conspiracy Belief Detection** · [code](https://github.com/Ekansh0301/conspiracy-belief-detection)
<br><sub>Shows that belief is spread across a whole post rather than in a few lexical cues. Mean-pooled DeBERTa-v3-large ensemble, 0.829 macro F1 on dev.</sub>

---

### Toolkit

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,c,cpp,ts,js,bash,pytorch,react,nodejs,fastapi,docker,redis,mongodb,postgres,linux,git&theme=dark&perline=8" alt="Python, C, C++, TypeScript, JavaScript, Bash, PyTorch, React, Node.js, FastAPI, Docker, Redis, MongoDB, PostgreSQL, Linux, Git">
</p>

---

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Ekansh0301/Ekansh0301/output/github-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Ekansh0301/Ekansh0301/output/github-snake.svg">
    <img alt="Contribution graph being eaten by a snake" src="https://raw.githubusercontent.com/Ekansh0301/Ekansh0301/output/github-snake.svg">
  </picture>
</p>
