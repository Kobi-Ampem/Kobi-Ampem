<p align="center">
  <img src="./assets/banner.svg" width="100%" alt="A waving purple robot next to a terminal booting kobi.os: Kobi Ampem Afriyie, Intelligent Systems Engineer"/>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/kobi-ampem-afriyie/"><img src="https://img.shields.io/badge/LinkedIn-7C3AED?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:afriyieampemkobi@gmail.com"><img src="https://img.shields.io/badge/Email-A855F7?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://img.shields.io/badge/Open%20to-Summer%202027%20internships-5B21B6?style=for-the-badge" alt="Open to summer 2027 internships"/>
</p>

## 💜 What I do

| 🤖 AI × Robotics | ⚙️ Backend | ☁️ Cloud |
|---|---|---|
| Fine-tuned transformers, LLM agents with tools, retrieval and evaluation; computer vision; Arduino, Raspberry Pi, LEGO EV3, SPIKE Prime and ESP32 builds | FastAPI and Django services on PostgreSQL, with tests in CI | AWS Certified Cloud Practitioner. Docker, Linux. Lambda, DynamoDB, Cognito, CDK and SAM, deployed from GitHub Actions over OIDC |

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,cpp,ts,fastapi,django,react,postgres,docker,aws,linux,raspberrypi,arduino,git&perline=13" alt="Python, C++, TypeScript, FastAPI, Django, React, PostgreSQL, Docker, AWS, Linux, Raspberry Pi, Arduino, Git"/>
</p>

## ✨ Quick facts

- 🎓 **MSc Data & Artificial Intelligence** at JUNIA ISEN, France (Erasmus+ Scholar)
- 🎓 **BSc Computer Engineering** at KNUST, Ghana (First Class so far; FFAF Scholar)
- 🏆 **Ghana Robotics Competition** winner as team lead, and robotics teacher to 1,000+ students

## ⭐ Featured: Nwoma

### [Nwoma](https://github.com/Kobi-Ampem/nwoma) · [live demo](https://kobi-ampem.github.io/nwoma/)

Reads lab reports and referral letters in English or French, scanned or digital, suggests LOINC
and ICD-10-CM codes, and exports a FHIR R4 record that shows which fields a person verified.
*Nwoma* is Asante Twi for document.

- **Cascade:** a fine-tuned XLM-R model handles most documents on CPU; a code validator sends only the doubtful third to Gemini
- **Coding agent:** Gemini with four tools assigns codes where search alone fails
- **MCP server:** extraction, coding and FHIR export available to AI assistants

| On 500 held-out synthetic documents | Result |
|---|---|
| Field F1 (cascade) | **0.955** |
| Documents sent to the LLM | **33%** |
| ICD-10-CM top-1 with the coding agent | **49% → 93%** |
| LOINC top-1 with the coding agent | **64% → 85%** |

`Python` `XLM-R` `Gemini` `FastAPI` `MCP` `AWS Lambda` `FHIR R4`

## 🛠️ Also built

| Project | What it does | Stack |
|---|---|---|
| [AsaaseTom Guard](https://github.com/Kobi-Ampem/asaase-tom-guard) | Tomato disease detection robot. Two YOLOv8 detectors (leaf mAP50 0.93), a Raspberry Pi patrol and Arduino firmware with safety reflexes over a checksummed UART link. 1st place (JHS category), RAIL Robotics Challenge, KNUST 2026; I trained and mentored the team | Python, YOLOv8, C++, Arduino, Raspberry Pi |
| [Resume–Job Matcher](https://github.com/kose-labs/p1-resume-job-matcher) · [demo](https://kose-labs.github.io/p1-resume-job-matcher/) | Scores a CV against a job description. I led the ML: six embedding models tested against TF-IDF on 120 hand-rated pairs; none beat it, so TF-IDF stayed. Built at KoSe Labs | Python, scikit-learn, FastAPI, React |
| [AgriConnect](https://github.com/AgriKorn/AgricConnect) | Farm marketplace, 10-person team. My backend work: PostgreSQL migration, AES-256-GCM encryption of payment numbers, a CI test gate on 164 tests, load testing to 150 concurrent users | TypeScript, Node.js, PostgreSQL |
| [Mini Search Engine](https://github.com/Kobi-Ampem/mini-search-engine-dsa) | Coursework project: document search on an inverted index, with ranked keyword search, boolean AND / OR / NOT queries and highlighted snippets | Python, Streamlit |

**Hackathons:** 3rd place, Claude Hackathon KNUST ([RouteMate](https://route-mate-two.vercel.app/)) · Best All-Female Team, Cursor Hackathon KNUST ([ClinikLane](https://cliniklane.vercel.app/)) · Winner, SHECodes Challenge, RAIL KNUST ([EduPath](https://edupathaii.netlify.app/))

<br/>

<p align="center">
  <img height="120" src="https://streak-stats.demolab.com/?user=Kobi-Ampem&background=12081F&ring=C084FC&fire=F0ABFC&currStreakNum=F5D0FE&sideNums=E9D5FF&currStreakLabel=F0ABFC&sideLabels=C4B5FD&dates=A78BFA&stroke=7C3AED&border=7C3AED&border_radius=12" alt="Kobi's GitHub streak"/>
</p>

<p align="center">
  <i>Building something with AI, robots or the cloud? Let's talk</i> 💜
</p>
