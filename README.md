![GitHub](https://img.shields.io/github/license/DataForScience/LLMsForDataScience)
[![Twitter @data4sci](https://img.shields.io/twitter/follow/data4sci)](https://twitter.com/intent/follow?screen_name=data4sci)
![GitHub top language](https://img.shields.io/github/languages/top/DataForScience/LLMsForDataScience)
![GitHub repo size](https://img.shields.io/github/repo-size/DataForScience/LLMsForDataScience)
![GitHub last commit](https://img.shields.io/github/last-commit/DataForScience/LLMsForDataScience)

[![Data For Science Substack](https://img.shields.io/badge/Data_For_Science-Subscribe-blue)](https://graphs4sci.substack.com/)
	[![Data Science Briefing](https://img.shields.io/badge/Data_Science_Briefing-Subscribe-blue)](https://data4science.kit.com/a63d4cc8d9)

# LLMs for Data Science

Repository for the "LLMs for Data Science" course by Bruno Gonçalves (Data For Science, Inc). 

Large Language Models (LLMs) are powerful tools that put state-of-the-art AI capabilities at the tip of our fingers. They can process large amounts of data, understand nuance and context, and perform complex tasks at our request. Over the past few years, LLMs have multiplied as have the tools specially built to leverage their capabilities.

In this course, you will learn how to use large language models to perform data science tasks such as summarization, translation, named entity recognition, audio generation, and data processing. We’ll explore the possibilities afforded by the tools and APIs developed by OpenAI, Hugging Face, LangChain, and Pandas AI and how best to apply them to our data science work.

## Contents

This tutorial is divided into four parts:


### 1. **Generative AI for Data Science**
_Introduction to the fundamental concepts of Generative AI._
  - Generative AI
  - Large Language Models
  - OpenAI
  - Hugging Face
  - LangChain


### 2. **Prompt Engineering**
_Techniques and best practices for designing effective prompts to guide Large Language Models._
  - Output formatting
  - Prompt Techniques
  - Zero-Shot and Few-Shot Prompting
  - Chain of Thought


### 3. **NLP with HuggingFace**
_Practical examples of using the HuggingFace `transformers` library for Natural Language Processing tasks._
  - Named-Entity Recognition
  - Part-of-Speech Tagging
  - Summarization
  - Question Answering


### 4. **Text to Speech with Open AI**
_Working with Audio: Speech-to-Text and transcription using OpenAI's Whisper model._
  - The Whisper model
  - Generating audio from text
  - Audio transcription
  - Automatic Translation

## Environment Setup

This project manages dependencies using `uv` (recommended) or standard `pip`.

### Prerequisites

- Python 3.13 or higher (as specified in `pyproject.toml`)

### Option 1: Using `uv` (Recommended)

This repository includes a `uv.lock` file for reproducible environments.

1. **Install uv**: Follow instructions at [docs.astral.sh/uv](https://docs.astral.sh/uv/).
2. **Sync dependencies**:
   ```bash
   uv sync
   ```
3. **Run Jupyter**:
   ```bash
   uv run jupyter notebook
   ```

### Option 2: Using `pip`

You can install the dependencies directly from the `pyproject.toml` file.

```bash
pip install .
```
## Data

The `data/` directory contains datasets and media files used in the notebooks, including:
- **Datasets**: `Apple-Twitter-Sentiment-DFE.csv`, `Northwind_small.sqlite`
- **Audio**: `gettysburg10.wav`, `pratchett.mp3`
- **Scripts**: `EpiModel.py`
- **Images**: Logo and other assets.

## Author

<table border="0">
 <tr>
    <td>
      <img src="data/bgoncalves.png" alt="Bruno Gonçalves" width="150" height="150" style="border-radius: 50%; object-fit: cover;">
    </td>
    <td>
      <h2>Bruno Gonçalves</h2>
      <h3>Data For Science, Inc.</h3>
      <p>
            Web: <a href="http://www.data4sci.com/">www.data4sci.com</a><br>
            Twitter/X: <a href="https://twitter.com/bgoncalves">@bgoncalves</a><br>
            LinkedIn: <a href="https://www.linkedin.com/in/bmtgoncalves/">@bmtgoncalves</a><br>
            Email: <a href="info@data4sci.com">info@data4sci.com</a><br>
            Schedule a Call: <a href="https://data4sci.com/call">https://data4sci.com/call</a>
      </p>
    </td>
 </tr>
</table>
