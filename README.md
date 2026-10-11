# Kushik S K

**Applied AI Engineer & Systems Builder**  
📍 Dubai, UAE & Mysuru, India · 🎓 MSc in Artificial Intelligence @ **Heriot-Watt University (Dubai Campus)**  
📫 `kushik8055@gmail.com` · 🌐 [Live Production Platform](https://www.srisaihomeappliancesandfurnitures.in/) · 💻 [GitHub @Kushik18](https://github.com/Kushik18)

---

### Engineering Narrative

I build applied AI and software systems that run reliably under real-world constraints—whether that's achieving sub-millisecond neural retrieval across dense vector spaces on CPU, deploying zero-latency computer vision pipelines on edge streams, orchestrating autonomous multi-agent workflows, or launching full-stack production platforms serving active commercial clients.

Currently pursuing my **MSc in Artificial Intelligence at Heriot-Watt University, Dubai**, my technical focus bridges mathematical foundations (vector algebra, cosine distance, deep learning inference) with practical systems engineering (multi-agent coordination, local-first LLMs, spatial web experiences, and automated audit pipelines).

---

### Featured Systems & Architecture

#### 1. [Neural Vector Search & Semantic Recommendation Engine](https://github.com/Kushik18/neural-vector-search-engine)
*An end-to-end multi-domain semantic retrieval platform across heterogeneous catalog data (Jobs, Courses, and Products).*
* **Core Architecture**: Sentence-Transformers (`all-MiniLM-L6-v2`) generating 384-dimensional dense vectors indexed via FAISS `IndexFlatIP`.
* **Empirical Benchmarks**: Tested across 3,800+ embeddings; achieved **0.006 ms to 0.378 ms** query latency on CPU.
* **Algorithmic Rigor**: Enforces strict L2 unit-norm normalization for exact cosine inner-product calculations. Validated with self-retrieval sanity checks achieving **77.78% Top-1 accuracy** on cross-catalog item queries.
* **Stack**: Python, FAISS, Sentence-Transformers, NumPy, Pandas.

#### 2. [Real-Time YOLOv8 Vision & Spatial Analytics Suite](https://github.com/Kushik18/YOLO)
*Industrial-grade edge computer vision pipeline for real-time detection, tracking, and spatial counting.*
* **Origin**: Developed and deployed during my Summer Internship at **IVIS LABS**, then hardened into a production-ready suite.
* **Capabilities**:
  * Multi-class object detection across all 80 COCO categories with real-time bounding overlays.
  * Direction-aware virtual tripwires and polygonal spatial zone counting for pedestrian and vehicular traffic.
  * Multi-threaded Flask streaming dashboard with audio/visual threshold alerting.
* **System Hardening**: Re-engineered telemetry logging to eliminate cross-platform Windows CP1252 encoding crashes under continuous high-frame-rate inference.
* **Stack**: Ultralytics YOLOv8s, OpenCV, Python, Flask, PyTorch.

#### 3. [Sri Sai Home Appliances & Furnitures — Production Platform](https://github.com/Kushik18/Sri_Sai_Home_Appliances_-_Furnitures)
*A commercial e-commerce web platform engineered and deployed for a real retail business in Mysuru.*
* **Live Deployment**: 🔗 [www.srisaihomeappliancesandfurnitures.in](https://www.srisaihomeappliancesandfurnitures.in/)
* **Architectural Decisions**:
  * *The 3D vs Performance Trade-off*: Initial prototyping explored interactive 3D WebGL product viewers (Three.js). However, field profiling showed 85%+ of local shoppers browse via mobile devices on variable network connections. Deliberately prioritized a sub-second Next.js 16 + React 19 + Cloudinary CDN architecture to eliminate mobile shader lag, ensure instant page loads, and streamline WhatsApp lead funnels.
  * *AI Product Ingestion*: Engineered a custom Groq LLM pipeline (`scripts/enrichProducts.ts`) that ingests raw physical showroom invoice and Tally data, filters non-product line items, and generates structured JSON specifications (wattage, dimensions, verified category).
* **Stack**: Next.js 16, React 19, TypeScript, PostgreSQL, Prisma ORM, Cloudinary, Upstash Redis Rate Limiting, Tailwind CSS 4.

#### 4. [JARVIS — Multi-Modal AI Desktop Assistant](https://github.com/Kushik18/jarvis-ai-assistant)
*A privacy-first, low-latency multi-modal desktop assistant with voice control and local inference.*
* **Dual-Brain Architecture**:
  * Primary engine runs on local Ollama (`llama3.2`) for complete offline privacy and zero telemetry leakage.
  * Gracefully transitions to Google Gemini Cloud when deep reasoning or external knowledge is requested.
* **Capabilities**: Hands-free voice wake loop, system hardware telemetry (CPU, RAM, battery), 22 desktop application shortcuts, and PyQt5 HUD.
* **Stack**: Python, PyQt5, Ollama, Google Gemini API, pyttsx3, SpeechRecognition, psutil.

#### 5. [Payana — AI Travel & Spatial Itinerary Planner](https://github.com/Kushik18/payana-travel-planner)
*A full-stack itinerary intelligence platform generating multi-day travel itineraries based on budget and spatial constraints.*
* **Architecture**: Decoupled microservices architecture with a Java 17 Spring Boot backend, React 19 UI, and interactive Leaflet GIS route mapping across regional district points of interest.
* **Stack**: Java 17, Spring Boot, React 19, Leaflet GIS, Recharts, Maven.

---

### Technical Toolkit

| Domain | Core Stack & Tools |
|---|---|
| **Deep Learning & Vision** | PyTorch, Ultralytics YOLOv8, OpenCV, FAISS, Sentence-Transformers, Hugging Face, Scikit-Learn |
| **Autonomous Agents & GenAI** | Autonomous Multi-Agent Workflows, Ollama (Llama 3.2), Groq Cloud API, Google Gemini API, Prompt Design |
| **Backend & Systems** | Python 3.13, Java 17 (Spring Boot), Next.js Server Components, Flask, Prisma ORM, PostgreSQL |
| **Frontend, 3D & GIS** | React 19, Next.js 16, TypeScript, Three.js / WebGL, Tailwind CSS 4, Leaflet GIS, Shadcn UI |
| **Infrastructure & Caching** | Upstash Redis (Distributed Rate Limiting), Cloudinary CDN, Git, GitHub CLI, Linux/Windows CLI |

---

### Academic Background

- **MSc in Artificial Intelligence** — **Heriot-Watt University** (Dubai Campus, UAE)
- **B.E. in Artificial Intelligence and Machine Learning** — **University of Mysore** (School of Engineering), CGPA: 8.0 / 10.0

---

### Contact

- **Email**: [kushik8055@gmail.com](mailto:kushik8055@gmail.com)
- **GitHub**: [github.com/Kushik18](https://github.com/Kushik18)
- **Commercial Site**: [srisaihomeappliancesandfurnitures.in](https://www.srisaihomeappliancesandfurnitures.in/)
