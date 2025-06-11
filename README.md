# Fastly Pricing Calculator: AI Tool Comparison

A comprehensive comparison of 5 different AI coding tools building identical Fastly pricing calculators from the same prompt. This project demonstrates the capabilities, strengths, and limitations of modern AI coding assistants when given a real-world web development task.

## 🎯 The Challenge

All tools were given the identical prompt:

> "Given https://www.fastly.com/pricing I want you to build a web-based interactive, easy to use, visually simple, user friendly and appealing, modern, pricing calculator for Fastly services."

**Constraints:**
- Maximum 5 follow-up prompts allowed
- Stock configuration (no MCP servers or custom tweaks)
- Zero manual code edits
- Same premium models used across all tools

## 📁 Project Structure

```
fastly-cost-simulator/
├── tool-1/          # Single-file HTML implementation
├── tool-2/          # Vite + React + TypeScript build
├── tool-3/          # Vite + React + TypeScript build  
├── tool-4/          # Vite + React + TypeScript build
├── tool-5/          # Single-file HTML implementation
└── README.md        # This file
```

## 🔍 Key Findings

### Performance Metrics
- **Development Time**: Ranged from 5 minutes to 2 hours
- **User Interaction**: Varied dramatically between tools
  - Some required minimal interaction
  - Others needed extensive back-and-forth
- **Question Quality**: 
  - One tool asked many basic questions
  - Another asked only insightful questions and worked autonomously

### Technical Observations
- **Framework Choice**: All tools selected similar modern web frameworks
- **Implementation Success**: 3 out of 5 tools struggled with framework usage initially
- **Common Pitfall**: All tools misunderstood the same specific feature from Fastly's pricing page
- **Architecture Differences**: 
  - Tool 1: Pure HTML/CSS/JS with inline styling
  - Tools 2-4: Modern React + TypeScript + Vite stack

### Testing & Quality
- One tool performed thorough real-world testing autonomously
- Others required manual verification and debugging

## 🚀 Getting Started

Each tool's implementation can be viewed by opening the respective `index.html` file:

```bash
# Tool 1 - Pure HTML/CSS/JS
open tool-1/index.html

# Tools 2-4 - Built React applications
open tool-2/index.html
open tool-3/index.html
open tool-4/index.html

# Tool 5 - Pure HTML/CSS/JS
open tool-5/index.html
```

## 📊 Implementation Details

### Tools 1 & 5
- **Architecture**: Single-file HTML with embedded CSS and JavaScript
- **Approach**: Monolithic, self-contained implementation
- **Styling**: Extensive inline CSS

### Tools 2-4
- **Architecture**: Modern React + TypeScript + Vite build system
- **Assets**: Compiled JavaScript and CSS in `assets/` directories
- **Build Output**: Optimized static files ready for deployment

## 🔬 Analysis

This comparison reveals significant differences in:
- **Speed of delivery**
- **Quality of user interaction**
- **Autonomous problem-solving capabilities**
- **Code architecture decisions**
- **Error handling and edge case consideration**

## 📝 Blog Post

Detailed analysis with performance metrics, user experience comparisons, and technical deep-dives coming soon.
