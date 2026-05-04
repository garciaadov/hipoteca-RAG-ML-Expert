# Asistente RAG Inteligente: Consultoria de Hipotecas y Prestamos en España

Este proyecto es el resultado de mi Trabajo Fin de Master (TFM). Se trata de un ecosistema avanzado de Inteligencia Artificial que actua como asistente experto en el mercado hipotecario español, combinando el procesamiento de lenguaje natural con la precision del Machine Learning.

## Objetivo del Proyecto
El objetivo principal es proporcionar respuestas veraces y contextualizadas sobre hipotecas y prestamos, eliminando las alucinaciones de los modelos de lenguaje genericos mediante una arquitectura RAG (Retrieval-Augmented Generation). El sistema esta anclado a la normativa vigente y a la logica financiera de un modelo de prediccion de solvencia.

## Arquitectura y Metodologia
El proyecto se ha dividido en tres partes fundamentales:

1. Fase ML (Machine Learning): Creacion y entrenamiento del modelo predictivo para el analisis de variables de solvencia.
2. Fase RAG (Retrieval-Augmented Generation): Implementacion de la base de datos vectorial con informacion multiformato.
3. Fase de Integracion Final: Union del modelo RAG + ML para una explicabilidad completa de las predicciones.

## Fuentes de Datos (Multi-Format Support)
El sistema integra informacion proveniente de cinco tipos de archivos distintos:
* PDF
* DOC / DOCX
* JSON
* CSV
* TXT

## Tecnologias Utilizadas
* LLM Engine: Ollama (Open Source).
* Vector Database: ChromaDB.
* Embeddings: FastEmbed.
* Lenguaje: Python 3.12.
* Frameworks: LangChain.

## Entrega de Modelos
El archivo que contiene el estado final del modelo y la base de datos es:

> 📁 **rag_tfm_final.zip**

## Instalacion y Uso
1. Instalar Ollama y descargar el modelo Llama3.
2. Descomprimir rag_tfm_final.zip.
3. Instalar dependencias:
   pip install langchain-community fastembed chromadb langchain-ollama
4. Ejecutar el notebook principal.
---
---
# Intelligent RAG Assistant: Mortgage and Loan Consultancy in Spain

This project is the result of my Master's Final Project (TFM). It is an advanced Artificial Intelligence ecosystem that acts as an expert assistant for the Spanish mortgage market, combining natural language processing with Machine Learning precision.

## Project Objective
The main goal is to provide accurate and contextualized answers regarding mortgages and loans, eliminating hallucinations common in generic language models through a RAG (Retrieval-Augmented Generation) architecture. The system is anchored to current regulations and the financial logic of a creditworthiness prediction model.

## Architecture and Methodology
The project has been divided into three fundamental parts:

1. ML Phase (Machine Learning): Creation and training of the predictive model for solvency variable analysis.
2. RAG Phase (Retrieval-Augmented Generation): Implementation of the vector database using multi-format information.
3. Final Integration Phase: Merging the RAG + ML models for full explainability of the predictions.

## Data Sources (Multi-Format Support)
The system integrates information from five different file types:
* PDF
* DOC / DOCX
* JSON
* CSV
* TXT

## Technologies Used
* LLM Engine: Ollama (Open Source).
* Vector Database: ChromaDB.
* Embeddings: FastEmbed.
* Language: Python 3.12.
* Frameworks: LangChain.

## Model Delivery
The file containing the final state of the model and the database is:

> 📁 **rag_tfm_final.zip**

## Installation and Usage
1. Install Ollama and download the Llama3 model.
2. Unzip rag_tfm_final.zip.
3. Install dependencies:
   pip install langchain-community fastembed chromadb langchain-ollama
4. Run the main notebook.
