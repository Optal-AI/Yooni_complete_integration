# Yooni - AI-Powered Research & Writing Assistant

<div align="center">

![Yooni Logo](https://img.shields.io/badge/Yooni-AI%20Research%20Assistant-blue?style=for-the-badge)

**An intelligent research paper evaluation and academic writing enhancement platform powered by AI**

[Features](#-features) • [Use Cases](#-use-cases) • [Benefits](#-benefits) • [Quick Start](#-quick-start) • [Documentation](#-documentation)

</div>

---

## 📖 Overview

Yooni is a comprehensive AI-powered platform designed to revolutionize academic research and writing workflows. It combines intelligent paper discovery, relevance evaluation, and AI-driven writing enhancement to help researchers, students, and academics work more efficiently and produce higher-quality work.

Whether you're conducting literature reviews, writing research papers, or evaluating academic content, Yooni provides the tools you need to streamline your workflow and improve your output quality.

---

## ✨ Features

### 🔍 Research Paper Discovery & Evaluation
- **Smart Paper Discovery**: Automatically find highly relevant papers from arXiv based on your research topic
- **Relevance Scoring**: AI-powered evaluation of papers against your research theme with detailed scoring
- **Visual Analytics**: Interactive charts and graphs showing how papers match your research criteria
- **Paper Upload & Analysis**: Upload PDFs and get instant relevance scores and evaluations
- **Session Management**: Organize your research with multiple search sessions
- **Favorites System**: Save and organize important papers for easy access

### ✍️ Academic Writing Enhancement
- **AI-Powered Writing Improvement**: Get intelligent suggestions to enhance your academic writing
- **Rubric-Based Evaluation**: Evaluate writing against custom or default academic rubrics
- **Real-time Feedback**: Receive detailed feedback on content, organization, and mechanics
- **Writing Projects**: Manage multiple writing projects with goals, deadlines, and progress tracking
- **Citation Management**: Generate and manage citations in APA, MLA, Chicago, and Harvard formats
- **Auto-save**: Never lose your work with automatic saving

### 📊 Advanced Analytics
- **Relevance Visualization**: Radar charts and comparison graphs showing paper relevance
- **Score Breakdowns**: Detailed analysis of evaluation criteria
- **Progress Tracking**: Monitor your writing goals and word counts
- **Performance Metrics**: Track improvements over time

### 🎯 Additional Capabilities
- **Multi-format Support**: Works with PDFs, DOCX, and web-based papers
- **Export Functionality**: Export research results in JSON and CSV formats
- **Search History**: Keep track of all your research sessions
- **Responsive Design**: Modern, intuitive interface that works on all devices

---

## 🎯 Use Cases

### 1. **Literature Review Research**
**Scenario**: You're writing a literature review and need to find and evaluate relevant papers quickly.

**How Yooni Helps**:
- Enter your research topic and Yooni finds the most relevant papers from arXiv
- Each paper is automatically evaluated for relevance, quality, and literature review suitability
- Visual charts help you quickly identify the best papers for your review
- Save papers to favorites and organize them by session

**Time Saved**: Reduces literature review time from days to hours

### 2. **Research Paper Evaluation**
**Scenario**: You have a collection of papers and need to determine which ones are most relevant to your research.

**How Yooni Helps**:
- Upload PDFs or provide URLs to papers
- Get instant relevance scores and detailed evaluations
- Compare multiple papers side-by-side with visual analytics
- Make informed decisions about which papers to include in your research

**Benefit**: Make data-driven decisions about paper relevance

### 3. **Academic Writing Improvement**
**Scenario**: You've written a draft and want to improve it according to academic standards.

**How Yooni Helps**:
- Upload a custom rubric or use the default academic rubric
- Get AI-powered suggestions to improve content, organization, and mechanics
- Receive detailed feedback on each aspect of your writing
- Track improvements and monitor your progress

**Result**: Higher-quality academic writing with less effort

### 4. **Thesis/Dissertation Writing**
**Scenario**: You're working on a long-form academic document and need to manage multiple sections.

**How Yooni Helps**:
- Create separate writing projects for each chapter
- Set goals, deadlines, and track word counts
- Get consistent feedback across all sections
- Manage citations and references efficiently

**Benefit**: Better organization and consistency across your entire document

### 5. **Grant Proposal Writing**
**Scenario**: You need to write a compelling grant proposal that meets specific evaluation criteria.

**How Yooni Helps**:
- Upload the grant's evaluation rubric
- Get targeted feedback aligned with the grant's criteria
- Improve your proposal's chances of success
- Track progress and meet deadlines

**Outcome**: More competitive grant proposals

### 6. **Peer Review Preparation**
**Scenario**: You want to ensure your paper meets publication standards before submission.

**How Yooni Helps**:
- Evaluate your paper against academic writing standards
- Identify areas for improvement before peer review
- Get suggestions for enhancing clarity, argumentation, and evidence
- Reduce the likelihood of rejection or major revisions

**Advantage**: Higher acceptance rates and fewer revision cycles

---

## 💡 Benefits of Using Yooni

### ⏱️ **Time Efficiency**
- **Automated Paper Discovery**: Find relevant papers in minutes instead of hours of manual searching
- **Quick Evaluations**: Get instant relevance scores and summaries
- **Streamlined Workflow**: All your research and writing tools in one place

### 🎓 **Quality Improvement**
- **AI-Powered Feedback**: Receive detailed, actionable feedback on your writing
- **Rubric-Based Evaluation**: Ensure your work meets academic standards
- **Consistent Quality**: Maintain high standards across all your writing projects

### 📈 **Better Decision Making**
- **Data-Driven Insights**: Visual analytics help you make informed choices about papers
- **Comparative Analysis**: Easily compare multiple papers side-by-side
- **Relevance Scoring**: Know exactly how relevant each paper is to your research

### 🗂️ **Organization**
- **Session Management**: Keep your research organized with multiple search sessions
- **Favorites System**: Save important papers for quick access
- **Project Management**: Track multiple writing projects with goals and deadlines

### 💰 **Cost Effective**
- **Free Paper Discovery**: Uses free arXiv API for paper search
- **Efficient API Usage**: Optimized prompts reduce OpenAI API costs
- **No Subscription Required**: Open-source and self-hosted

### 🔒 **Privacy & Control**
- **Self-Hosted**: Run everything on your own infrastructure
- **Data Privacy**: Your research and writing stays on your machine
- **Customizable**: Modify and extend to fit your specific needs

### 🚀 **Scalability**
- **Handles Large Projects**: Manage multiple papers and writing projects simultaneously
- **Export Capabilities**: Export data for further analysis or backup
- **Extensible Architecture**: Easy to add new features and integrations

---

## 🚀 Quick Start

### Prerequisites

- **Python 3.8+** installed
- **Node.js 16+** and npm installed
- **OpenAI API Key** ([Get one here](https://platform.openai.com/api-keys))

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/yooni.git
   cd yooni
   ```

2. **Install Python dependencies**
   ```bash
   pip3 install -r requirements.txt
   ```

3. **Install Node.js dependencies**
   ```bash
   npm install
   ```

4. **Set up your OpenAI API key**
   ```bash
   echo "OPENAI_API_KEY=your_api_key_here" > .env
   ```

### Running Yooni

**Easiest way - Use the start script:**
```bash
./start.sh
```

This automatically starts both:
- **Backend (Flask)** on port 5001
- **Frontend (React)** on port 3000

Then open: **http://localhost:3000**

**To stop both servers:**
```bash
./stop.sh
```

### Manual Start

**Terminal 1 - Backend:**
```bash
python3 app.py
```

**Terminal 2 - Frontend:**
```bash
npm run dev
```

Then open: **http://localhost:3000**

---

## 📚 Documentation

### API Endpoints

#### Research Paper Evaluation
- `POST /api/evaluate-paper` - Evaluate a paper from URL
- `POST /api/evaluate-pdf` - Evaluate an uploaded PDF
- `POST /api/find-papers` - Find relevant papers for a topic
- `POST /api/visualization-data` - Get visualization data for papers

#### Writing Enhancement
- `POST /api/upload-rubric` - Upload a custom rubric (PDF/DOCX)
- `POST /api/evaluate-writing` - Evaluate writing against a rubric
- `POST /api/improve-writing` - Get AI-powered writing improvements
- `GET /api/default-rubric` - Get the default academic rubric

### Example API Usage

```bash
# Evaluate a paper
curl -X POST http://localhost:5001/api/evaluate-paper \
  -H "Content-Type: application/json" \
  -d '{
    "url": "https://arxiv.org/pdf/2301.00001.pdf",
    "research_theme": "Machine Learning for Healthcare"
  }'

# Find relevant papers
curl -X POST http://localhost:5001/api/find-papers \
  -H "Content-Type: application/json" \
  -d '{
    "research_topic": "transformer models",
    "research_theme": "NLP research",
    "max_papers": 5
  }'
```

### Python API

```python
from research_agent import ResearchAgent

# Initialize agent
agent = ResearchAgent(research_theme="Machine Learning for Healthcare")

# Evaluate a paper
result = agent.evaluate_paper_from_url(
    "https://arxiv.org/pdf/2301.00001.pdf"
)

# Find relevant papers
papers = agent.find_and_evaluate_papers(
    "transformer models in NLP",
    max_papers=5
)
```

---

## 🏗️ Architecture

### Backend (Flask)
- `app.py` - Flask API server and routing
- `research_agent.py` - Main research agent orchestration
- `research_tools.py` - Paper evaluation, search, and summarization tools
- `writing_tools.py` - Writing evaluation and improvement tools
- `visualizations.py` - Data visualization utilities

### Frontend (React + TypeScript)
- `src/components/pages/` - Main application pages
  - `ResearchMatchPage.tsx` - Paper upload and evaluation
  - `SearchPapersPage.tsx` - Keyword-based paper discovery
  - `WritingProjectsPage.tsx` - Writing project management
  - `WritingProjectDetailPage.tsx` - Writing editor and improvement
- `src/services/` - API service layer
- `src/config/` - Configuration and API endpoints

### Key Technologies
- **Backend**: Python, Flask, OpenAI API, PyPDF2, arxiv
- **Frontend**: React, TypeScript, Vite, Tailwind CSS, Recharts
- **AI**: OpenAI GPT-4o-mini for evaluation and rewriting

---

## 📊 Evaluation Criteria

### Research Paper Evaluation
- **Relevance Score** (1-10): How relevant is the paper to your research theme?
- **Quality Score** (1-10): What is the quality and rigor of the paper?
- **Literature Review Score** (1-10): How useful is it for literature review?
- **Overall Recommendation**: Yes/No for including in your research

### Writing Evaluation (Default Rubric)
- **Content and Analysis**: Depth of understanding, originality, evidence quality
- **Organization**: Structure, transitions, coherence
- **Mechanics**: Grammar, spelling, punctuation, language precision

---

## 🔧 Configuration

### Environment Variables

Create a `.env` file in the root directory:

```env
OPENAI_API_KEY=your_openai_api_key_here
PORT=5001  # Optional: Backend port (default: 5001)
FLASK_DEBUG=False  # Optional: Enable Flask debug mode
```

### Frontend Configuration

Edit `src/config/api.ts` to customize API endpoints:

```typescript
const API_BASE_URL = import.meta.env.VITE_API_BASE_URL || 'http://localhost:5001';
```

---

## 🛠️ Development

### Project Structure
```
yooni/
├── app.py                 # Flask backend server
├── research_agent.py      # Research agent orchestration
├── research_tools.py      # Paper evaluation tools
├── writing_tools.py       # Writing enhancement tools
├── requirements.txt       # Python dependencies
├── src/                   # React frontend
│   ├── components/        # React components
│   ├── services/          # API services
│   └── config/            # Configuration
├── package.json           # Node.js dependencies
└── README.md             # This file
```

### Running in Development Mode

Backend with auto-reload:
```bash
FLASK_DEBUG=True python3 app.py
```

Frontend with hot-reload:
```bash
npm run dev
```

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## 🙏 Acknowledgments

- OpenAI for the GPT API
- arXiv for providing free access to research papers
- The open-source community for the amazing tools and libraries

---

## 📞 Support

- **Issues**: [GitHub Issues](https://github.com/yourusername/yooni/issues)
- **Documentation**: See `QUICK_START.md` for detailed setup instructions
- **Questions**: Open an issue or discussion on GitHub

---

## 🗺️ Roadmap

- [ ] Support for more paper sources (PubMed, Google Scholar)
- [ ] Collaborative features for research teams
- [ ] Advanced citation management
- [ ] Integration with reference managers (Zotero, Mendeley)
- [ ] Multi-language support
- [ ] Mobile app
- [ ] Browser extension

---

<div align="center">

**Made with ❤️ for researchers and academics**

⭐ Star this repo if you find it helpful!

</div>
