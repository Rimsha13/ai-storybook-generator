# AI Storybook Generator

## Overview

AI Storybook Generator is an end-to-end automation workflow built using n8n and Large Language Models (LLMs). The system transforms a simple Google Sheets entry containing a character name and story description into a complete illustrated storybook.

The workflow automatically generates a structured story, creates AI-generated illustrations for every scene, uploads the assets to Google Drive, and assembles a professional slide-by-slide storybook without manual intervention.

## Problem

Creating illustrated children's storybooks manually requires significant time for writing, designing, and formatting. Businesses and content creators often need a faster and more scalable solution.

## Solution

This automation pipeline eliminates manual work by combining workflow automation, AI text generation, image generation, and presentation automation into a single end-to-end process.

A single Google Sheets entry automatically triggers the complete workflow and produces a ready-to-use illustrated storybook within minutes.

## Features

- Automated workflow using n8n
- Story generation with LLMs
- Structured scene generation
- AI illustration generation
- Google Drive integration
- Automatic Google Slides creation
- End-to-end workflow automation

  Google Sheets

↓

n8n Trigger

↓

Story Generation (LLM)

↓

Scene Extraction

↓

AI Image Generation

↓

Upload Images

↓

Create Google Slides

↓

Final Storybook

## Tech Stack

### Automation
- n8n

### AI
- OpenAI
- LLMs

### Programming
- Python

### Integrations
- Google Sheets API
- Google Drive API
- Google Slides API

### Image Generation
- Kling AI

## Screenshots

### Workflow Overview

![Workflow](assets/workflow.png)

### Architecture

![Architecture](assets/architecture.png)

### Generated Storybook

![Output](assets/output.png)

## 🎥 Project Demonstration

### Complete Workflow

[▶ Watch Complete Workflow](assets/Youseef_Workflow.mp4)

This video demonstrates the complete end-to-end automation workflow.

---

### AI Image Generation

[▶ Watch Image Generation](assets/image-generation-demo.mp4)

Shows how AI illustrations are generated for every scene.

---

### Automated Google Slides Creation

[▶ Watch Slide Creation](assets/slide-creation-demo.mp4)

Demonstrates automatic slide generation and presentation assembly.

## Challenges

- Managing multiple AI API calls
- Handling long-form story generation
- Coordinating image generation
- Error handling and retries
- Maintaining workflow reliability

## Results

- Fully automated story generation
- AI-generated illustrations
- Automatic slide creation
- Reduced manual effort from hours to minutes
- Scalable workflow for repeated use

## Note

This repository showcases the architecture and implementation approach of the project.

The production workflow, source code, and client-specific assets are intentionally excluded to respect client confidentiality.
