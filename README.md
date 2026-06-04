# Valezo AI Chatbot

## Overview
Valezo AI Chatbot is an AI-powered restaurant assistant that allows users to interact with a digital menu using natural language. The system uses LLMs to understand user queries and retrieve relevant menu items, recommendations, and contextual answers.

The goal is to simulate a real-world AI-first application with retrieval, prompt engineering, and optional vector search.

---

## Problem Statement
Users struggle to quickly find relevant food items or recommendations from traditional menus. This system solves that by enabling conversational search and intelligent recommendations.

---

## Core Features (MVP)

### 1. Chat Interface
- User can ask questions in natural language
- AI responds in a conversational format

### 2. Menu-based Knowledge
- AI only answers based on provided restaurant menu data
- Prevent hallucination (no fake items)

### 3. Recommendations
- Suggest food based on:
  - preferences (spicy, cheap, vegetarian)
  - ingredients
  - user intent

### 4. Basic Retrieval (Phase 1)
- JSON-based menu search
- Keyword matching or simple filtering

---

## Advanced Features (Phase 2)
- Embeddings-based semantic search (pgvector)
- Context-aware conversation memory
- Better ranking of menu items

---

## Tech Stack

### Frontend
- React (Vite)
- Chat UI (ChatGPT-style interface)

### Backend
- Node.js / NestJS
- REST API

### Database
- PostgreSQL
- Optional: pgvector extension for embeddings

### AI Layer
- Claude or OpenAI API
- Prompt engineering for controlled responses

### DevOps
- Docker + Docker Compose

---

## Architecture

User → Frontend → Backend API → Menu Data / Vector DB → LLM → Response → User

---

## Constraints
- AI must not invent menu items
- Responses must be grounded in provided data
- System should prioritize accuracy over creativity

---

## Goal


Build a production-style AI assistant that demonstrates:
- LLM integration
- retrieval systems
- structured prompt engineering
- full-stack architecture


test
