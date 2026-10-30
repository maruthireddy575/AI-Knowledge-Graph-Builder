# AI-Knowledge-Graph-Builder

AI Knowledge Graph Builder is a full-stack web application that automatically transforms unstructured text content into interactive, structured knowledge graphs. It uses advanced NLP techniques to extract concepts, identify relationships, and visualize knowledge as an interactive graph.

Purpose: Help students, researchers, and educators convert raw text into structured, navigable knowledge maps.

Core Workflow:

Content Input → Concept Extraction → Relationship Mapping → Graph Building → Refinement → Validation → Visualization

## ✨ Features

- 🧠 **6 AI Agents**: Extraction, Relation, Graph Builder, Refinement, Validation, Diff
- 📊 **Interactive Visualization**: Force-directed graphs with zoom, pan, and node inspection
- 🔄 **Graph Comparison**: Side-by-side diff viewer for tracking changes
- ✅ **Validation Checklist**: Automated quality assessment with 7 metrics
- 📚 **Version History**: Store and compare multiple graph versions
- 🎨 **Modern UI**: React with lucide-react icons and smooth animations
- 🔌 **RESTful API**: Complete API documentation
- 🗄️ **MongoDB Storage**: Persistent graph storage with indexing


---

## 🚀 Quick Start

### Prerequisites

- Node.js 18+
- MongoDB 6+
- npm or yarn

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/ai-knowledge-graph-builder.git
cd ai-knowledge-graph-builder

# 2. Setup Backend
cd backend
npm install
cp .env.example .env
# Edit .env with your MongoDB URL
npm start

# 3. Setup Frontend (in new terminal)
cd frontend
npm install
cp .env.example .env
npm start
