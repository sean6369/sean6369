<h2 align="center">👋 Hi there, I’m Sean</h2>

<p align="center">
I’m a <b>Computer Engineering</b> student at <b>National University of Singapore (NUS)</b> who builds AI agents, retrieval systems, and the self-hosted infrastructure they run on.
</p>

<p align="center">
🌐 <a href="https://seanlsk.com">seanlsk.com</a>
</p>

Here are my public projects, from personal builds and hackathons to school work and client websites:

---

## 🧱 Personal Projects

[**A Calmer News**](https://github.com/sean6369/newsapp) · [Live](https://news.seanlsk.com)  
A self-hosted news archive for one reader. It pulls feeds hourly, clips the full text, scores stories against my interests, and groups outlets covering the same event. Everything lives in one Postgres table with both a full-text and a vector index, and each page queries it a different way. An Ask page lets an LLM answer from the archive using hybrid (full-text + vector) search, citing the articles it used.

[**homelab**](https://github.com/sean6369/homelab)  
A two-machine homelab: a home server for the services, and an Oracle Cloud instance that holds the backups and monitors it from outside. Rebuilt after an SSD failure in August 2026 around one rule: backups and external monitoring are built and restore-tested before the services they protect come back. Deployed as Docker Compose stacks with SOPS-encrypted secrets, Borg backups, and Uptime Kuma, connected over Tailscale.

---

## 💡 Hackathons

[**SigmaGuide**](https://github.com/Path-yang/SigmaGuide)  
*@NUS Hack&Roll 2026*  
A desktop assistant that watches your screen with GPT-4o vision, breaks any software task into step-by-step instructions, and detects automatically when each step is done.

[**SigmaPay**](https://github.com/Path-yang/SigmaPay) · [Live](https://sigma-pay-ten.vercel.app)  
*@NUS Fintech Summit 2026*  
Cross-border payments on the XRP Ledger, with instant transfers, escrow, asset tokenisation, and the RLUSD stablecoin. On-chain identity verification sets transfer limits for compliance.

[**PSA L2 Ops AI Co-Pilot**](https://github.com/Path-yang/PSA-Code-Sprint-25) · [Live](https://psa-code-sprint-25-frontend.vercel.app/)  
*🏆 3rd Runner-up (of 400+ teams) @PSA Code Sprint 2025*  
An AI diagnostic assistant with ticketing for Level 2 product operations. It parses incoming alerts, searches application logs, knowledge-base articles, and past cases, then proposes a root cause and resolution steps.

[**SilverSigma**](https://github.com/Path-yang/SilverSigma) · [Live](https://silver-sigma.vercel.app)  
*@SUTD What the Hack 2025*  
A web app for seniors with a multilingual AI avatar companion, a hobby hub with local classes, and a private social feed for family.

[**SigmaHealth**](https://github.com/clemenong1/SigmaHealth)  
*🏆 Finalist (top 10 of 60+ teams), Most Impressive Usage of Data, and Best team for Theme 1 (Health and Wellbeing) @NUS Lifehack 2025*  
A multilingual React Native app combining real-time Singapore health data, GPT-based health guidance, and community reporting for crowdsourced public-health monitoring.

[**SigmaShield**](https://github.com/Path-yang/DSTA-Code-Exp-2025)  
*🏆 Finalist (top 20 of 80+ teams) @DSTA Brainhack-Code EXP 2025*  
A mobile app that helps users detect and prevent online scams, with real-time URL analysis, scam analytics, and a community forum.

[**NoFap**](https://github.com/Path-yang/Hackomania_2025)  
*@Hackomania 2025*  
A web app that helps people overcoming addiction stay motivated through progress tracking and community support, with micro-donations through the Open Payments API.

[**Ship Vessel Risk Detection**](https://github.com/Path-yang/Maritime-Hackathon-2025)  
*🏆 Called for Top 3 @Maritime Hackathon 2025*  
A two-stage pipeline that consolidates inspection annotations into one severity label, then fine-tunes DistilBERT to classify vessel deficiency severity.

---

## 🎓 School & Team Projects

[**SentinelAI**](https://github.com/Path-yang/SentinelAI) · [Live](https://sentinel-ai-web-ll3v.vercel.app)  
Turns ordinary IP cameras into real-time detectors for falls, medical emergencies, and safety hazards, streaming to the cloud and pushing alerts to web and mobile.

[**GymFit**](https://github.com/WangZX2001/GymFit)  
*NUS Orbital 2025*  
A Flutter and Firebase fitness app with workout tracking, calorie calculations, muscle recovery monitoring, and personalised workout recommendations.

---

## 💼 Client Websites

[**Oxley Pawnshop**](https://oxleypawnshop.com)  
As a solo software engineer, I designed and launched the website for a Singapore pawnshop, with an email-integrated contact form and auto-replies, live gold prices, and company email accounts for the team.

[**GoldJewel**](https://goldjewel.sg) & [**CMS**](https://cms.goldjewel.sg)  
As a solo software engineer, I built a jewellery website and a custom CMS, with image cropping and real-time updates to the site whenever a product changes.

---

## 🛠 Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![C/C++](https://img.shields.io/badge/C/C++-00599C?style=flat-square&logo=c%2b%2b&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black) ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Oracle Cloud](https://img.shields.io/badge/Oracle_Cloud-F80000?style=flat-square&logo=oracle&logoColor=white) ![Tailscale](https://img.shields.io/badge/Tailscale-242424?style=flat-square&logo=tailscale&logoColor=white) ![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)

---

<h3>📫 Let’s Connect</h3>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lee-su-kiat-sean-19211a33b) [![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:seanleesukiat@gmail.com)
