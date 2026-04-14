# Hi, I'm Prasad 👋

> **AOSP & Android Framework Engineer** · Kernel · BSP · System Services · CS Grad @ UB

I've been taking Android apart since I got my first Nexus device in eighth grade. What started as flashing ROMs turned into maintaining full custom AOSP builds from scratch: kernel bring-up, device trees, HAL integration, SELinux policies, and everything the BSP layer demands.

Currently an **Android Developer Intern at Elo Touch Solutions** (Buffalo, NY), customizing AOSP firmware for enterprise POS touchscreen terminals. Previously spent nearly two years at **MahiTech** as an Associate AOSP Engineer doing BSP bring-up and platform-level work across **Qualcomm** and **Rockchip** hardware.

🔍 **Open to full-time AOSP / Android Platform Engineering roles, available June 2026**

---

## 🛠️ What I Work With

<p align="left">
  <img src="https://img.shields.io/badge/AOSP-3DDC84?style=for-the-badge&logo=android&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux_Kernel-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/Android_Framework-3DDC84?style=for-the-badge&logo=android&logoColor=white"/>
  <img src="https://img.shields.io/badge/SELinux-CC0000?style=for-the-badge&logo=redhat&logoColor=white"/>
  <img src="https://img.shields.io/badge/HAL-FF6F00?style=for-the-badge&logo=android&logoColor=white"/>
  <img src="https://img.shields.io/badge/Qualcomm_SDM660-3253DC?style=for-the-badge&logo=qualcomm&logoColor=white"/>
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black"/>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Shell-121011?style=for-the-badge&logo=gnu-bash&logoColor=white"/>
</p>

---

## 💻 AOSP Work

### Device Bring-up · ASUS MAX Pro M2 (Qualcomm SDM660 · Android 14)

Full boot-to-UI AOSP 14 bring-up on a Qualcomm device: kernel configs, SELinux policy, HAL declarations, Treble compliance, init.rc, and everything in between.

| Repo | Layer | What it covers |
|------|-------|----------------|
| [android_kernel_asus_sdm660](https://github.com/PrasadParulkar/android_kernel_asus_sdm660) | Kernel | Driver patches, defconfig tuning, bring-up fixes for Android 14 |
| [android_device_asus_X01BD](https://github.com/PrasadParulkar/android_device_asus_X01BD) | Device | init scripts, overlays, HAL declarations, Treble configuration |
| [android_device_asus_sdm660-common](https://github.com/PrasadParulkar/android_device_asus_sdm660-common) | Common | Platform configs, vendor interface, shared overlays |

### 🔧 Framework Engineering Highlights

- Customized and debugged multiple Android Framework system services across different Android versions, tracing issues through service lifecycles, Binder IPC boundaries, and cross-service dependencies
- Ported discontinued framework components across major Android version gaps, adapting to undocumented internal rearchitecture between releases
- Debugged multi-layer system service breakage by instrumenting full call chains with targeted logs and building execution flow diagrams before touching a single line of code
- Authored SELinux policies, integrated HAL interfaces, and handled BSP bring-up across **Qualcomm** and **Rockchip** chipsets at MahiTech
- Maintained **Maru OS** (dual Android + full Linux desktop via LXC) and **LineageOS** for ASUS MAX Pro M2

---

## 🎓 Masters Capstone · University at Buffalo

### Multimodal AAC Chatbot · Bucketed RAG with Gesture-Driven Cue Fusion

> *A training-free multimodal communication assistant for people with severe speech or motor disabilities*

AAC users communicate intent through **gestures and facial expressions**. This system detects those cues on an Android device and generates contextually appropriate spoken responses in real time.

- 📱 **Android client (Java + MediaPipe)** · on-device gesture/facial cue detection, partner speech via STT
- ⚡ **FastAPI + ChromaDB** · bucket-aware memory retrieval using `all-MiniLM-L6-v2` embeddings
- 🤖 **Cross-encoder reranking** · `ms-marco-MiniLM-L-6-v2`, achieving **77.8% Bucket Accuracy**
- 🧠 **LLM generation** · Gemma 3 27B (Google AI Studio) with auto-failover to Llama 3.1 8B (Groq)

**Stack:** Python · Java · Android · FastAPI · ChromaDB · MediaPipe · SentenceTransformers · Gemma 3 · GCP

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=PrasadParulkar&theme=tokyonight" width="100%"/>
</p>
<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=PrasadParulkar&theme=tokyonight" height="165"/>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=PrasadParulkar&theme=tokyonight" height="165"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=PrasadParulkar&theme=tokyonight&hide_border=true"/>
</p>

---

## 📱 Other Projects

| Repo | Stack | About |
|------|-------|-------|
| [A1News](https://github.com/PrasadParulkar/A1News) | Java · Android | News aggregator Android app |
| [ColorSetterDialog_Rings_Framelayout](https://github.com/PrasadParulkar/ColorSetterDialog_Rings_Framelayout) | Java · Android | Custom color-ring picker UI component |
| [DigitalWellBeingAnalysis](https://github.com/PrasadParulkar/DigitalWellBeingAnalysis) | Python | Data analysis of Android Digital Wellbeing usage patterns |

---

## 📫 Reach Me

<p align="left">
  <a href="mailto:parulkarprasad@gmail.com"><img src="https://img.shields.io/badge/Email-parulkarprasad@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/prasad-parulkar-b36515180/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-Prasad_Parulkar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://github.com/PrasadParulkar" target="_blank"><img src="https://img.shields.io/badge/GitHub-PrasadParulkar-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=PrasadParulkar&style=flat-square&color=3DDC84" alt="Profile views"/>
</p>
