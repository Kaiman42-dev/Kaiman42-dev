# Salut, je suis Salman 👋

### Étudiant à [42 Perpignan](https://42perpignan.fr/) · Développement, systèmes, infrastructure et IA

Je construis des programmes de bout en bout, du C bas niveau (threads, mémoire, algorithmique) jusqu'aux infrastructures conteneurisées et aux agents LLM. J'aime comprendre comment les choses fonctionnent sous le capot et les rendre fiables : isolation, sécurisation, tests et code typé.

---

## 🛠️ Stack

**Langages**

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Systèmes, infrastructure et sécurité**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Debian](https://img.shields.io/badge/Debian-A81D33?style=flat-square&logo=debian&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![NGINX](https://img.shields.io/badge/NGINX-009639?style=flat-square&logo=nginx&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)
![WordPress](https://img.shields.io/badge/WordPress-21759B?style=flat-square&logo=wordpress&logoColor=white)
![Make](https://img.shields.io/badge/Make-427819?style=flat-square&logo=gnu&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**IA et données**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)

**Qualité et outillage Python** : uv, mypy (strict), flake8, Pygame

---

## 🚀 Projets

### 🤖 IA et agents LLM

| Projet | Description | Technos |
|---|---|---|
| [**Agent Smith**](https://github.com/Kaiman42-dev/agent_smith_git) | Agent de code évalué sur MBPP et SWE-bench Verified : boucle d'agent écrite sans framework, sandbox sécurisée (liste blanche d'imports et de fichiers, pas de réseau, limites de temps et de mémoire), outils exposés par nos propres serveurs MCP, multi-fournisseurs LLM avec rotation de clés et bascule automatique. *En binôme.* | Python, Docker, MCP |
| **RAG against the machine** | Questions-réponses sur le code source de vLLM : ingestion et découpage, index BM25 persistant, génération avec Qwen3-0.6B, évaluation de la recherche par Recall@k. | Python, LangChain, Transformers, Docker |
| **Call Me Maybe** | Function calling par décodage contraint, implémenté à la main au niveau des tokens (sans outlines ni dspy) : la sortie du modèle est toujours un JSON valide. | Python, Qwen3-0.6B, Pydantic |
| [**HackerRank Orchestrate**](https://github.com/Kaiman42-dev/Orchestrate-September-26) | Hackathon de 24 h (septembre 2026) : agent financier qui décide si un utilisateur peut se permettre une dépense (paiement complet, partiel, en plusieurs fois, attendre ou renoncer), à partir de messages et d'images. | Python, LLM |

### 🐳 Infrastructure et sécurité

| Projet | Description | Technos |
|---|---|---|
| **Inception** | Infrastructure web conteneurisée construite sans image toute faite : NGINX seul point d'entrée en HTTPS (TLS), WordPress avec php-fpm, MariaDB, réseau Docker privé, volumes persistants et secrets. | Docker, Compose, NGINX, MariaDB |
| **Born2beRoot** | Serveur Debian sous VM : partitionnement LVM chiffré, SSH durci, pare-feu UFW, politique sudo et mots de passe, script de supervision planifié par cron. | Linux, sécurité système |

### ⚙️ C, systèmes et algorithmique

| Projet | Description | Technos |
|---|---|---|
| **Codexion** | Simulation de concurrence inspirée des philosophes : threads POSIX, prévention des interblocages et de la famine, ordonnancement FIFO et EDF par tas de priorité, journalisation sans data race. | C, pthreads |
| **push_swap** | Tri d'une pile avec un jeu d'instructions limité, en un minimum de coups (Radix Sort). | C |
| **libft · ft_printf · get_next_line** | Réimplémentation de la libc, d'un `printf` variadique et d'une lecture ligne par ligne avec buffer. | C |
| **fly_in** | Simulateur de routage de drones sur un graphe pondéré : Dijkstra, capacités des zones et des liaisons, résolution des conflits tour par tour. | Python, mypy strict |
| **Pac-Man** | Recréation du jeu d'arcade en architecture orientée objet : fantômes autonomes, niveaux, highscores, configuration JSON validée. *En binôme.* | Python, Pygame |

### 🧪 Projets personnels

| Projet | Description | Technos |
|---|---|---|
| [**Albion Market Spotter**](https://github.com/Kaiman42-dev/Albion_market_spoted) | Détection d'opportunités d'achat et revente à partir d'une API publique, en tenant compte des taxes, de la fraîcheur des prix et des distances : CLI, dashboard web local, mode surveillance et export CSV. Aucune dépendance. | Python |
| **Gatherer Vision** | Détection d'objets à l'écran en temps réel avec un modèle YOLO exporté en ONNX. | Python, ONNX, OpenCV |
| [**Fokus**](https://github.com/Kaiman42-dev/Fokus) | Met une vidéo en pause quand on détourne le regard de l'écran, par estimation de l'orientation de la tête. | Python, MediaPipe, OpenCV |

---

## 📊 Statistiques GitHub

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Kaiman42-dev&show_icons=true&count_private=true&locale=fr" alt="Statistiques GitHub" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Kaiman42-dev&layout=compact&locale=fr" alt="Langages les plus utilisés" />
</p>

---

## 📫 Contact

[![Email](https://img.shields.io/badge/Email-salman.aziev%40outlook.fr-0078D4?style=flat-square&logo=microsoft-outlook&logoColor=white)](mailto:salman.aziev@outlook.fr)
