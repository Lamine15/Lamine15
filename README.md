# Mamadou Lamine DIATTA

**Cybersécurité · Supervision · Agents IA**

Master Réseaux, Sécurité et Systèmes Distribués, Université Gaston Berger (Saint-Louis, Sénégal), 2026.
Basé à Dakar. Je recherche un stage ou un premier emploi en SOC, en administration systèmes et réseaux ou en sécurité, à partir de décembre 2026.

## Mon projet principal

**Agent IA de supervision et de sécurité** (mémoire de Master, stage au CCOS de l'UGB). Un agent orchestré avec LangGraph collecte les signaux d'une infrastructure Linux (journaux, services, disque, certificats, vulnérabilités publiées dans la NVD), les fait interpréter par un modèle de langage local (Qwen3 via Ollama) et alerte l'administrateur par courriel et Telegram.

Principe directeur : le modèle interprète, il ne détecte pas. Chaque constat est établi par les outils, et des garde-fous déterministes bornent la criticité et les blocages proposés. L'agent supervise aussi des serveurs distants, avec une collecte répartie et une analyse centrale.

*Code privé, présentation sur demande.*

## Projets publics

| Projet | En bref | Technologies |
|---|---|---|
| [Sunu Santé](https://github.com/Lamine15/sunu-sante) | Télémédecine résiliente : 5 microservices, réplication par quorum, disjoncteurs | Java, Spring Boot, RabbitMQ, Docker, Prometheus |

Autres projets, code privé :
- **Antivol PC** : alarme et alerte Telegram si le PC verrouillé est débranché ou reçoit un périphérique USB (Python, API Windows)
- **PapisAyo** : application de pilotage d'arrosage connecté (Flutter, Supabase, ESP32)

## Compétences

- **Cybersécurité :** Lynis, RKHunter, ClamAV, fail2ban, UFW, NVD et CVE, durcissement SSH et sudoers
- **Systèmes et DevOps :** Linux (Ubuntu), Windows, Docker, RabbitMQ, Prometheus, VMware, Git, cron
- **Réseaux :** TCP/IP, HTTP, DNS, routage et commutation, Wireshark, sockets
- **IA appliquée :** LangGraph, LangChain, Ollama, RAG, ChromaDB
- **Développement :** Python, Java (Spring Boot), Flutter
- **IoT :** Arduino, ESP32

Langues : français, anglais, wolof.

## In English

Master's in Networks, Security and Distributed Systems (Gaston Berger University, Senegal, 2026), based in Dakar. I am looking for an internship or a junior role in SOC, systems and network administration or security, from December 2026.

My Master's project is an AI agent for the security monitoring of Linux infrastructure: LangGraph orchestration, a small local LLM to interpret the evidence, and deterministic guardrails so that the model never decides alone what is detected or blocked. Public project: a resilient telemedicine platform built with Spring Boot microservices ([Sunu Santé](https://github.com/Lamine15/sunu-sante)).
