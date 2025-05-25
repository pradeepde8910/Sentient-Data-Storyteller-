# 📊 Sentient Data Storyteller

An AI-powered analytics companion that transforms raw data into compelling, multi-modal narratives.

## 🚀 Overview

The Sentient Data Storyteller is a cutting-edge platform built to turn complex datasets into human-centric stories, visualizations, and debates. It harnesses the power of Groq's ultra-fast LLMs, Hugging Face embeddings, and a modular AI architecture to democratize data insights for executives, analysts, and non-technical users alike.

From automated data profiling to real-time TTS debates, this tool is designed to deliver sub-second analytics at scale — supporting datasets with up to 500,000 rows.

## 🧠 Key Features

- 📦 **Data Upload & Profiling**: Upload CSV, Excel, or JSON files for automated schema detection and profiling.
- 🔍 **Automated Insight Generation**: Statistical summaries, clustering, and correlations with confidence scores.
- 📊 **Visualization Builder**: Supports 12+ chart types with AI-recommended plot suggestions.
- 🧑‍💼 **Persona-Based Narratives**: Executive, analytical, and technical storytelling formats.
- 🎙️ **AI Debate Mode**: Multi-perspective (optimistic, pessimistic, contrarian) debates with TTS playback.
- 🧬 **Context-Aware Prompt Engineering**: Continuous refinement of prompts based on user feedback.
- 🎧 **Text-to-Speech (TTS)**: Narrated stories and debates for multi-modal delivery.
- ⚙️ **Modular Architecture**: Supports real-time diagnostics, anomaly detection, caching, and parallel processing.

## 🏗️ Architecture

### 🔢 LLM Models Used

| Model Name           | Architecture       | Context Window | Description                              |
|----------------------|-------------------|----------------|------------------------------------------|
| llama3-70b-8192      | LLaMA 3 (70B)     | 8192 tokens    | Best for deep analysis and debates       |
| llama3-8b-8192       | LLaMA 3 (8B)      | 8192 tokens    | Balanced for speed and capability        |
| mixtral-8x7b-32768   | Mixtral 8x7B MoE  | 32768 tokens   | High-context, efficient expert routing   |

### 🔡 Embedding Model

| Model Name         | Architecture  | Output Dim | Description                          |
|--------------------|--------------|------------|--------------------------------------|
| all-MiniLM-L6-v2   | MiniLM-6     | 384        | Lightweight, fast transformer embeddings |

### 🛠️ System Architecture
User Interaction → Data Ingestion → Preprocessing → Profiling & Feature Engineering → Insight Generator → AI/ML Narrative Generation → Visualization Recommender → UI Dashboard → Storytelling & TTS Debate → Feedback Loop & Redis Caching

![image](https://github.com/user-attachments/assets/153f3597-29af-46f3-8d30-6589667c004f)


Each component works in harmony, ensuring a seamless, scalable, and insightful user experience.

### 🔄 Control Flow

1. **Data Ingestion**: Upload data → Validate & clean → Profile & summarize
2. **Insight Generation**: Perform statistical analysis and clustering
3. **Narrative Creation**: AI crafts a story or initiates a persona-based debate
4. **Visualization**: Suggests and renders charts with annotations
5. **Debate Mode**: Generates and reads out multiple viewpoints using TTS
6. **Feedback Loop**: User input improves insights, prompts, and UX over time

![image](https://github.com/user-attachments/assets/29e12a95-60ec-4fbc-b7dc-3f6a6673e198)


## 📦 Code Structure (Modules)

### Core Services

- **AppConfig**: Loads application settings and prompt templates
- **AIService**: Manages all LLM interactions
- **DataService**: Handles data loading, cleaning, profiling
- **VisualizationService**: Generates recommended plots and annotations
- **StorytellingService**: Creates narratives and debates using personas
- **InsightGenerator**: Produces statistical insights and clustering
- **PromptEngineer**: Refines prompts using AI
- **TTSService**: Converts text to speech for audio narratives

### Main Flow

1. Data upload triggers profiling and insight generation
2. Visualizations are recommended and rendered
3. Stories and debates are dynamically generated and optionally narrated
4. Feedback is cached and used to refine future outputs

## 🧪 Example Outputs

- ✅ Data Preview and Profiling
  ![image](https://github.com/user-attachments/assets/0dcf068c-f8b5-4506-9145-d7bd2092cbb2)

- 📈 AI-Recommended Visualizations
  ![image](https://github.com/user-attachments/assets/4768871d-5b35-45af-b973-507445d75b08)

- 🧠 Insight Cards with Confidence Scores
 ![image](https://github.com/user-attachments/assets/e301d38c-49ea-4f3c-96f2-5915e976c701)

- 🗣️ Executive Summaries and Analyst Narratives
 ![image](https://github.com/user-attachments/assets/5bfb60b4-36b1-4ddf-a16e-f9f0e3acc654)

- ⚖️ Contrasting Debates on Key Metrics
- ![image](https://github.com/user-attachments/assets/86ca621e-aa0b-44aa-9e18-6b83f3daeb21)

- 🔊 Narrated Data Stories
 ![image](https://github.com/user-attachments/assets/12626d1e-1b80-44ec-b0e6-34063fc70702)
 ![image](https://github.com/user-attachments/assets/848bcd25-3960-4226-b178-15c64709bda4)

## 📍 Tech Stack

- **LLMs**: LLaMA 3, Mixtral (via Groq)
- **Embeddings**: Hugging Face MiniLM
- **Interface**: Gradio + Python
- **Data Layer**: Pandas, Redis Cache
- **Visualization**: Plotly, Matplotlib
- **Speech**: Text-to-Speech (TTS) Engine

## 🏁 Getting Started

1. Clone the repository
2. Install required dependencies
3. Run the application and start uploading your data
4. Choose a persona or debate style and generate narratives
5. Interact with AI-generated charts, audio, and story summaries

## 🌟 Future Enhancements

- Real-time team collaboration
- Predictive modeling and forecasting
- Voice-controlled interactions
- Full cloud deployment (Streamlit, Hugging Face Spaces)

## 📣 Conclusion

The Sentient Data Storyteller reimagines how insights are consumed and delivered — not just through charts, but via voices, personas, and stories. It brings clarity to complexity and empowers users to make informed decisions, regardless of their technical background.

**Data isn't just numbers. It's a story waiting to be told.**
