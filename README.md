# 🔍 Named Entity Recognition (NER) with LLMs on Kaggle

This notebook demonstrates how to perform **Named Entity Recognition (NER)** using **Large Language Models (LLMs)**. It extracts structured entities from text, categorizing them into predefined types such as **persons, organizations, locations, and products**.

---

## 🏗️ Model Overview
- ✅ Uses **LLMs for entity extraction** instead of traditional NER models.
- ✅ Extracts **named entities and their types** from unstructured text.
- ✅ Processes long-form text efficiently by **chunking** before inference.

---

## 📥 Setup & Dependencies
- Installs required libraries:  
pip install torch transformers pandas openai

- ✅ Loads a **pretrained LLM** from Hugging Face.
- ✅ Configures **GPU acceleration** for faster inference.

---

## 🔄 Named Entity Extraction Process
- ✅ Reads input text from a file.
- ✅ **Chunks text** for efficient processing.
- ✅ Runs entity extraction using an **LLM-based NER approach**.
- ✅ Parses and structures the extracted entities.

---

## 📊 Output & Data Processing
- ✅ Converts extracted entities into a **structured DataFrame**.
- ✅ Saves the results in an **Excel file** for further analysis.
- ✅ Displays a preview of the **final extracted entities**.

---

## 💾 Cleanup & Resource Management
- ✅ Clears **GPU cache** to free memory.
- ✅ Deletes unnecessary variables to optimize execution.

---

## 🎯 Conclusion
This notebook provides a **practical guide** to performing **NER using LLMs**, showcasing their ability to extract structured information from unstructured text.

🚀 *Ideal for applications in text analytics, information retrieval, and AI-driven knowledge extraction!*

