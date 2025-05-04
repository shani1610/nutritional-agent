# Nutritional Agent

An AI nutritional assistant leveraging LLMs and vision-language models to analyze your profile and meal photos, then recommend your next meals.

## Background

This project was born within the Data Science "Baot" group, a cohort of data scientists collaborating on side projects to learn new skills and share knowledge. Our team explored the fundamentals of large language models using LangChain Academy’s [Introduction to LangGraph course](https://academy.langchain.com/courses/take/intro-to-langgraph/texts/58238105-getting-set-up).

## Overview

Nutritional Agent is a multimodal AI assistant that:

Ingests: Your personal details (e.g., age, dietary preferences, goals) and your meal photographs.

Understands: Uses an LLM to interpret goals and nutritional constraints, and a vision-language model (e.g., LLaVA) to identify foods and portion sizes from images.

Recommends: Suggests personalized next meals that align with your objectives (weight loss, muscle gain, balanced diet, etc.).

Learns: Incorporates your feedback in a human-in-the-loop loop to refine future recommendations.

## Usage

Configure your profile:
```
age: 30
height_cm: 170
weight_kg: 65
goals:
  - weight_loss
  - balanced_macros
dietary_preferences:
  - vegetarian
```

