# Hugging Face Course

This is a practical course on using the Hugging Face ecosystem for machine learning. You'll learn how to use the Hugging Face Hub, debug and troubleshoot machine learning models, and build interactive demos with Gradio.

<a href="http://hf.co/join/discord">
<img src="https://img.shields.io/badge/Discord-7289DA?&logo=discord&logoColor=white"/>
</a>

## Course Outline

This course provides a practical, hands-on approach to working with the Hugging Face ecosystem for machine learning.

| Chapter | Description | Status |
|---------|-------------|---------|
| [Chapter 0: Introduction](./chapters/en/chapter0/) | Set up your environment and get started with the course | ✅ Ready |
| [Chapter 1: The Hugging Face Hub](./chapters/en/chapter1/) | Learn about the Hub, sharing models, and building model cards | ✅ Ready |
| [Chapter 2: Debugging and Troubleshooting](./chapters/en/chapter2/) | Handle errors, ask for help, and debug training pipelines | ✅ Ready |
| [Chapter 3: Building ML Demos with Gradio](./chapters/en/chapter3/) | Create interactive demos with Gradio and share them | ✅ Ready |

## Why Learn the Hugging Face Ecosystem?

The Hugging Face ecosystem has become the standard for machine learning practitioners working with transformer models and beyond. Learning these tools offers several advantages:

- **Industry Standard**: Hugging Face tools are widely used in industry and research
- **Comprehensive Platform**: From model hosting to deployment, everything in one ecosystem
- **Community**: Access to thousands of pre-trained models and datasets
- **Ease of Use**: Simplified APIs for complex ML tasks
- **Collaboration**: Built-in tools for sharing and collaborating on ML projects
- **Production Ready**: Tools designed for both research and production deployment
- **Open Source**: Free to use with active community support

## Prerequisites

Before starting, ensure you have the following:
- Basic understanding of machine learning concepts
- Familiarity with Python programming
- A Hugging Face account (create one at [huggingface.co](https://huggingface.co/join))
- Basic knowledge of Git (helpful but not required)

## Getting Started

This course is designed to be followed along with hands-on coding. You can choose from several approaches:

### Option 1: Google Colab (Recommended for beginners)

The easiest way to get started is using Google Colab notebooks. Simply:

1. Open a new [Google Colab notebook](https://colab.research.google.com)
2. Install the required libraries as you go through each chapter
3. No local setup required!

### Option 2: Local Python Environment

If you prefer to work locally, set up a Python environment:

```bash
# Create a virtual environment
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate

# Install core dependencies
pip install transformers datasets huggingface_hub gradio
```

### Option 3: Using requirements.txt

If there's a requirements.txt file in this repository:

```bash
pip install -r requirements.txt
```

Each chapter will guide you through installing any additional dependencies you need for that specific section.

