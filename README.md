# Hi, I'm Salman 👋

### Student at [42 Perpignan](https://42perpignan.fr/) · Software development, systems, infrastructure and AI

I build programs end to end, from low-level C (threads, memory, algorithms) to containerized infrastructure and LLM agents. I like understanding how things work under the hood and making them reliable: isolation, hardening, testing and typed code.

---

## 🛠️ Stack

**Languages**

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Systems, infrastructure and security**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Debian](https://img.shields.io/badge/Debian-A81D33?style=flat-square&logo=debian&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![NGINX](https://img.shields.io/badge/NGINX-009639?style=flat-square&logo=nginx&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)
![WordPress](https://img.shields.io/badge/WordPress-21759B?style=flat-square&logo=wordpress&logoColor=white)
![Make](https://img.shields.io/badge/Make-427819?style=flat-square&logo=gnu&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**AI and data**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)

**Python quality and tooling**: uv, mypy (strict), flake8, Pygame

---

## 🚀 Projects

### 🤖 AI and LLM agents

| Project | Description | Tech |
|---|---|---|
| [**Agent Smith**](https://github.com/Kaiman42-dev/agent_smith_git) | Coding agent evaluated on MBPP and SWE-bench Verified: agent loop written without a framework, secure sandbox (import and file allowlists, no network, time and memory limits), tools exposed through our own MCP servers, multi-provider LLM support with key rotation and automatic failover. *Pair project.* | Python, Docker, MCP |
| **RAG against the machine** | Question answering over the vLLM source code: ingestion and chunking, persistent BM25 index, generation with Qwen3-0.6B, retrieval evaluation with Recall@k. | Python, LangChain, Transformers, Docker |
| **Call Me Maybe** | Function calling through constrained decoding, implemented by hand at the token level (no outlines or dspy): the model's output is always valid JSON. | Python, Qwen3-0.6B, Pydantic |
| [**HackerRank Orchestrate**](https://github.com/Kaiman42-dev/Orchestrate-September-26) | 24-hour hackathon (September 2026): a financial agent that decides whether a user can afford an expense (pay in full, pay partially, pay in installments, wait or skip it), based on messages and images. | Python, LLM |

### 🐳 Infrastructure and security

| Project | Description | Tech |
|---|---|---|
| **Inception** | Containerized web infrastructure built without ready-made images: NGINX as the single HTTPS (TLS) entry point, WordPress with php-fpm, MariaDB, private Docker network, persistent volumes and secrets. | Docker, Compose, NGINX, MariaDB |
| **Born2beRoot** | Debian server in a VM: encrypted LVM partitioning, hardened SSH, UFW firewall, sudo and password policies, monitoring script scheduled with cron. | Linux, system security |

### ⚙️ C, systems and algorithms

| Project | Description | Tech |
|---|---|---|
| **Codexion** | Concurrency simulation inspired by the dining philosophers: POSIX threads, deadlock and starvation prevention, FIFO and EDF scheduling with a priority heap, data-race-free logging. | C, pthreads |
| **push_swap** | Sorting a stack with a limited instruction set in as few moves as possible (Radix Sort). | C |
| **libft · ft_printf · get_next_line** | Reimplementation of the libc, a variadic `printf` and buffered line-by-line reading. | C |
| **fly_in** | Drone routing simulator on a weighted graph: Dijkstra, zone and link capacities, turn-by-turn conflict resolution. | Python, mypy strict |
| **Pac-Man** | Recreation of the arcade game with an object-oriented architecture: autonomous ghosts, levels, highscores, validated JSON configuration. *Pair project.* | Python, Pygame |

### 🧪 Personal projects

| Project | Description | Tech |
|---|---|---|
| [**Albion Market Spotter**](https://github.com/Kaiman42-dev/Albion_market_spoted) | Finds buy-and-resell opportunities from a public API, accounting for taxes, price freshness and travel distances: CLI, local web dashboard, watch mode and CSV export. Zero dependencies. | Python |
| **Gatherer Vision** | Real-time on-screen object detection with a YOLO model exported to ONNX. | Python, ONNX, OpenCV |
| [**Fokus**](https://github.com/Kaiman42-dev/Fokus) | Pauses a video when you look away from the screen, using head pose estimation. | Python, MediaPipe, OpenCV |

---

## 📊 GitHub stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Kaiman42-dev&show_icons=true&count_private=true" alt="GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Kaiman42-dev&layout=compact" alt="Most used languages" />
</p>

---

## 📫 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Salman%20Aziev-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/salman-aziev-773a55159/)
