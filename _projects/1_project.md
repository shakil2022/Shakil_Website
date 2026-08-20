---
layout: page
title: Multilingual RAG System – Bangla Textbook Pipeline
description: A sophisticated RAG system for Bengali textbook question answering.
img: assets/img/12.jpg
importance: 1
category: work
related_publications: false
---

<style>
.project-card {
  position: relative;
  padding: 28px 30px;
  margin: 20px 0 35px 0;
  border: 1px solid rgba(255, 255, 255, 0.15);
  border-radius: 18px;
  background: linear-gradient(
    135deg,
    rgba(38, 65, 105, 0.95),
    rgba(25, 48, 82, 0.95)
  );
  box-shadow: 0 8px 25px rgba(0, 0, 0, 0.15);
  color: #ffffff;
}

.project-header {
  display: flex;
  align-items: center;
  gap: 14px;
  margin-bottom: 18px;
}

.project-icon {
  width: 58px;
  height: 72px;
  border: 1px solid rgba(180, 200, 240, 0.8);
  border-radius: 14px;
  background: rgba(35, 65, 100, 0.8);
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 30px;
  flex-shrink: 0;
}

.project-title {
  margin: 0 !important;
  font-size: 22px;
  font-weight: 700;
  color: #ffffff !important;
}

.project-subtitle {
  margin: 5px 0 0 0;
  font-size: 15px;
  font-weight: 500;
  color: #dce5f5;
}

.project-description {
  margin-top: 18px;
  font-size: 15px;
  line-height: 1.65;
  color: #e8edf7;
  text-align: justify;
  text-justify: inter-word;
}

.project-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin-top: 18px;
}

.project-tag {
  display: inline-block;
  padding: 6px 11px;
  border-radius: 20px;
  background: rgba(255, 255, 255, 0.12);
  border: 1px solid rgba(255, 255, 255, 0.15);
  color: #eef3fc;
  font-size: 12px;
  font-weight: 500;
}

.project-buttons {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
  margin-top: 20px;
}

.project-button {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  padding: 9px 16px;
  border-radius: 8px;
  border: 1px solid rgba(255, 255, 255, 0.18);
  text-decoration: none !important;
  font-size: 13px;
  font-weight: 600;
  transition: all 0.2s ease;
}

.project-button.primary {
  background: #aebce8;
  color: #172746 !important;
}

.project-button.secondary {
  background: transparent;
  color: #e8edf7 !important;
}

.project-button:hover {
  transform: translateY(-2px);
  text-decoration: none !important;
}

.project-button.primary:hover {
  background: #c2cdf0;
}

.project-button.secondary:hover {
  background: rgba(255, 255, 255, 0.08);
}

.project-content {
  margin-top: 35px;
}

.project-section-title {
  font-size: 22px;
  font-weight: 700;
  margin-top: 30px;
  margin-bottom: 15px;
}

.project-content p {
  text-align: justify;
  text-justify: inter-word;
  line-height: 1.7;
}

@media (max-width: 576px) {
  .project-card {
    padding: 20px;
  }

  .project-title {
    font-size: 19px;
  }

  .project-description {
    font-size: 14px;
  }

  .project-icon {
    width: 50px;
    height: 62px;
    font-size: 25px;
  }
}
</style>


<div class="project-card">

  <div class="project-header">

    <div class="project-icon">
      <i class="fas fa-flask"></i>
    </div>

    <div>
      <h1 class="project-title">
        Multilingual RAG System – Bangla Textbook Pipeline
      </h1>

      <p class="project-subtitle">
        A sophisticated RAG system for Bengali textbook question answering.
      </p>
    </div>

  </div>


  <div class="project-description">

    Built a complete <strong>Retrieval-Augmented Generation (RAG)</strong>
    system that understands both English and Bengali. The system incorporates
    a dual embedding strategy using <strong>Cohere</strong> and
    <strong>OpenAI</strong>, advanced document reranking, OCR processing for
    Bengali text, and a <strong>FastAPI</strong> backend integrated with a
    <strong>Streamlit</strong> interface.

    The system ingests HSC Bangla textbooks and provides intelligent,
    context-aware question answering capabilities. It was successfully
    deployed on <strong>AWS EC2</strong> using <strong>Nginx</strong> as a
    reverse proxy.

  </div>


  <div class="project-tags">

    <span class="project-tag">RAG</span>
    <span class="project-tag">Multilingual AI</span>
    <span class="project-tag">FastAPI</span>
    <span class="project-tag">Streamlit</span>
    <span class="project-tag">Docker</span>
    <span class="project-tag">AWS EC2</span>
    <span class="project-tag">ChromaDB</span>
    <span class="project-tag">OCR</span>
    <span class="project-tag">Bengali NLP</span>

  </div>


  <div class="project-buttons">

    <a
      href="https://github.com/yourusername/your-repository"
      class="project-button primary"
      target="_blank"
      rel="noopener noreferrer"
    >
      <i class="fab fa-github"></i>
      View Code
    </a>

    <a
      href="https://your-live-demo-url.com"
      class="project-button secondary"
      target="_blank"
      rel="noopener noreferrer"
    >
      <i class="fas fa-play-circle"></i>
      Live Demo
    </a>

  </div>

</div>


<div class="project-content">

  <h2 class="project-section-title">
    Project Overview
  </h2>

  <p>
    This project presents a multilingual Retrieval-Augmented Generation
    pipeline designed specifically for question answering over Bengali
    educational textbooks. The system combines document processing,
    multilingual embeddings, vector search, reranking, and large language
    model-based generation into a complete end-to-end question answering
    pipeline.
  </p>


  <h2 class="project-section-title">
    Key Features
  </h2>

  <ul>
    <li>
      Multilingual question answering supporting both English and Bengali.
    </li>

    <li>
      Dual embedding strategy using Cohere and OpenAI embeddings.
    </li>

    <li>
      Advanced document retrieval and reranking.
    </li>

    <li>
      OCR processing for Bengali textbook content.
    </li>

    <li>
      ChromaDB-based vector storage and retrieval.
    </li>

    <li>
      FastAPI backend for serving the RAG pipeline.
    </li>

    <li>
      Streamlit-based interactive user interface.
    </li>

    <li>
      Docker-based deployment.
    </li>

    <li>
      AWS EC2 deployment with Nginx reverse proxy.
    </li>
  </ul>


  <h2 class="project-section-title">
    Technology Stack
  </h2>

  <p>
    <strong>AI / NLP:</strong> Retrieval-Augmented Generation, multilingual
    embeddings, Bengali NLP, OCR
  </p>

  <p>
    <strong>Backend:</strong> FastAPI
  </p>

  <p>
    <strong>Frontend:</strong> Streamlit
  </p>

  <p>
    <strong>Database:</strong> ChromaDB
  </p>

  <p>
    <strong>Deployment:</strong> Docker, AWS EC2, Nginx
  </p>

</div>