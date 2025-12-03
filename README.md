# 🎬 ANADAFUS-STUDIO
## **Ana**lyzing • **Da**ta • **Fus**ion

AI-powered multimedia content studio that transforms narratives, data, and trends into stunning visual stories. 

---
## 📺 Content Universe

**ANADAFUS-STUDIO** creates interconnected video content exploring a unified narrative universe:

### 1️⃣ **Microbiological Series: The Epic Saga**
Research-driven microbiological documentaries with epic storytelling, featuring intense conversations between Samir (Titan scientist) and Adi (Titan NCC operator). Foundation of the universe.
- **26 videos** | [Watch Playlist](https://www.youtube.com/playlist?list=PLp3Q4cfSW3KB-Ee1-OHjwugIViLpMv-Xa)

### 2️⃣ **Genior: The Birth of Adi & Samir's Tale**
Prequel & world-building content introducing the first-ever characters in the genior series. Follow Adi and Samir's journey as they embark on the grand adventure that shapes the entire narrative arc.
- **9 videos** | [Watch Playlist](https://www.youtube.com/playlist?list=PLp3Q4cfSW3KD9QluJ-ANb7prmg_tEgQY9)

### 3️⃣ **The Genior Resurgence**
Narrative sci-fi storytelling exploring digital resurrection and the aftermath of Genior's final transmission. The ultimate convergence where echoes become reality and fractured gates reveal new paths forward.
- **7 videos** | [Watch Playlist](https://www.youtube.com/playlist?list=PLp3Q4cfSW3KDnGyHF2TIYd3y5gbWIhmYR)

## ⚙️ **Tech Stack**

- **Mootion AI API**: Text-to-video generation with AI voiceovers and animations
- **Perplexity AI**: Script generation, research, and content refinement
- **YouTube Data API**: Automated video uploads and playlist management
- **GitHub Workflows**: CI/CD automation for content scheduling and deployment
- **Python**: Core orchestration and API integration

---

## 🚀 **Features**

✨ **Automated Video Generation**
- Convert narratives/scripts into fully animated videos
- Multi-language support (English, Arabic, Spanish, Japanese, etc.)
- Realistic AI voiceovers with character consistency
- Customizable visual styles (dramatic, cinematic, photorealistic, etc.)

✨ **Smart Content Pipeline**
- Script generation from prompts or data inputs
- Automatic scene storyboarding and composition
- Batch video processing for multiple episodes
- Async rendering with background job tracking

✨ **YouTube Integration**
- Auto-upload with metadata, thumbnails, and descriptions
- Community tab posting via Perplexity integration
- Playlist organization and scheduling
- Analytics dashboard integration

✨ **DevOps Ready**
- GitHub Actions workflows for automated releases
- Environment-based configuration (dev/staging/prod)
- API key management via GitHub Secrets
- Version control for all video configs

---

## 📁 **Project Structure**

```
ANADAFUS-STUDIO/
├── src/
│   ├── mootion_client.py          # Mootion API wrapper
│   ├── youtube_manager.py         # YouTube upload automation
│   ├── content_generator.py       # Script & narrative generation
│   └── perplexity_integration.py  # Perplexity AI integration
├── scripts/
│   ├── generate_episode.py        # CLI for episode creation
│   ├── batch_process.py          # Batch rendering
│   └── schedule_release.py       # Release scheduling
├── .github/workflows/
│   ├── tgr-episode-generator.yml # TGR release automation
│   ├── trend-analysis.yml        # Trend video pipeline
│   └── auto-upload.yml           # YouTube deployment
├── config/
│   ├── video_templates.yaml      # Style & composition presets
│   └── release_schedule.yaml     # Premiere times & dates
├── docs/
│   ├── SETUP.md                 # Installation & setup
│   ├── API_KEYS.md              # API configuration guide
│   └── WORKFLOW.md              # Content creation workflow
└── requirements.txt              # Python dependencies
```

---

## 🎯 **Current Projects**

### The Genior Resurgence (TGR Saga)
7-episode narrative sci-fi series about humanity's final stand in a fractured universe.
- **Episode 7**: "Echoes of the Final Resonance" (Latest Release)
- Format: 1-3 min cinematic episodes
- Release: Ceremonial premiere times with community announcements

### Trend Analysis Videos
Data-driven analysis of AI, tech, and industry trends.
- Compiles research from multiple sources
- Generates visual infographics via Mootion
- Auto-publishes to YouTube weekly

---

## 🔧 **Quick Start**

### Prerequisites
- Python 3.9+
- Mootion AI API key
- YouTube Data API credentials
- Perplexity API access
- GitHub account (for workflows)

### Installation

```bash
# Clone repository
git clone https://github.com/ADIVIDAN1012/ANADAFUS-STUDIO.git
cd ANADAFUS-STUDIO

# Install dependencies
pip install -r requirements.txt

# Configure environment
cp config/.env.example .env
# Edit .env with your API keys
```

### Generate Your First Video

```python
from src.content_generator import TGRGenerator

generator = TGRGenerator(api_key="your_mootion_key")
video_task = generator.create_episode(
    episode_num=8,
    narrative="Your story here...",
    style="cinematic"
)
print(f"Video generating: {video_task.id}")
```

---

## 📊 **Workflow**

1. **Content Ideation** → Perplexity generates script/narrative
2. **Video Generation** → Mootion API creates animated video
3. **Quality Check** → Review and refine (optional)
4. **Upload** → YouTube Data API publishes with metadata
5. **Announce** → Community tab post via automation
6. **Archive** → Store config in GitHub for version control

---

## 🌟 **Why ANADAFUS-STUDIO?**

**Analyzing** diverse content types (narrative, data, trends)  
**Data** drives every decision (analytics, scheduling, optimization)  
**Fusion** of AI tools (Mootion + Perplexity + YouTube APIs)  

This studio is a bridge between creative vision and automated production—enabling one creator to produce cinematic-quality content at scale.

---

## 📝 **License**

MIT License - See LICENSE file for details

---

## 🤝 **Contributing**

Contributions welcome! Feel free to open issues or submit PRs for:
- New content templates
- API optimizations
- Workflow automations
- Documentation improvements

---

## 📬 **Contact**

- **GitHub**: [@ADIVIDAN1012](https://github.com/ADIVIDAN1012)
- **YouTube**: [Anadafus](https://www.youtube.com/@ANADAFUS-1012)
- **Email**: sadhuadividan@gmail.com
---

**Building the future of automated storytelling. One echo at a time. 🚀**
