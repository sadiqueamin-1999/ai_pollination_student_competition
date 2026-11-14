# TrustDoc AI

# 

# Explainable Document Intelligence Platform

# TrustDoc AI is an AI-powered document intelligence platform developed for the AI Pollination Student Competition 2026.

# 

# The platform enables users to query, summarise, validate and audit large collections of documents while maintaining transparency through evidence-backed responses and source traceability.

# 

# Competition Achievement

# Finalist - AI Pollination Student Competition 2026.

# 

# Challenge Overview

# The competition required a solution that could:

# 

# Query and summarise documents

# Work with PDF and DOCX files

# Handle text, tables, figures and charts

# Support multiple documents

# Provide traceable evidence for generated answers

# TrustDoc AI expands on these requirements through:

# 

# Semantic Question Answering

# 

# Evidence Viewer

# 

# AI Evidence Explanations

# 

# Compliance Auditing

# 

# Cross-Document Validation

# 

# Financial Reconciliation

# 

# CSV Audit Export

# 

# Key Features

# Semantic Question Answering

# Users can ask natural language questions across one or more uploaded documents.

# 

# Examples:

# 

# What are the key findings about AI in healthcare?

# 

# What approvals are required for accompanied travel?

# 

# What onboarding documents are required for crew members?

# 

# TrustDoc retrieves relevant evidence before generating a response.

# 

# Evidence Viewer

# Every answer can be traced back to:

# 

# Source document

# Source page

# Retrieved evidence chunk

# Additionally, TrustDoc provides AI-generated explanations of retrieved evidence to improve interpretability.

# 

# Compliance Audit

# TrustDoc automatically identifies compliance and governance issues within document collections.

# 

# Example findings:

# 

# Agreement not signed

# 

# Draft agreement detected

# 

# Invoice exists despite unsigned agreement

# Cross-Document Validation

# TrustDoc analyses relationships between multiple documents rather than treating each file independently.

# 

# Examples:

# 

# Agreement <-> Invoice

# 

# Agreement <-> Crew Records

# 

# Agreement <-> Information Pack

# 

# This enables the identification of inconsistencies and governance risks across related documents.

# 

# Financial Reconciliation

# TrustDoc validates monetary values between agreements and invoices.

# 

# Examples:

# 

# PASS

# Agreement value matches invoice value

# MANUAL REVIEW

# P\&L-based agreement detected

# The platform intentionally routes complex revenue-sharing arrangements for human review rather than making unsupported assumptions.

# 

# Exportable Audit Reports

# Audit findings can be exported as CSV reports for further investigation and record keeping.

# 

# Technology Stack

# 

# Backend

# Python

# ChromaDB

# Sentence Transformers

# Groq API

# Pandas

# 

# Frontend

# Streamlit

# Embedding Model

# all-MiniLM-L6-v2

# Used for semantic retrieval and similarity search.

# 

# LLM

# openai/gpt-oss-120b

# Served through Groq

# 

# Datasets

# Dataset 1

# Single report containing:

# 

# Text

# Tables

# Figures

# 

# Used to test:

# 

# Question Answering

# Summarisation

# Figure Interpretation

# 

# Dataset 2

# Cardiff University travel-policy documents.

# 

# Used to test:

# 

# Multi-document retrieval

# Policy reasoning

# Evidence traceability

# 

# Dataset 3

# Festival operational document ecosystem including:

# 

# Policies

# Contracts

# Invoices

# Reports

# Crew records

# 

# Used to test:

# 

# Compliance auditing

# Cross-document validation

# Financial reconciliation

# Responsible AI

# TrustDoc AI was designed around transparency and explainability.

# 

# Core principles:

# 

# Retrieval-Augmented Generation (RAG)

# Evidence-backed responses

# Source document references

# Page-level traceability

# Explainable evidence summaries

# Human review for complex financial decisions

# The platform prioritises trustworthy and explainable outputs over fully autonomous decision-making.

# 

# Running the Project

# 

# Step 1

# 

# Open:

# 

# Notebook/TrustDoc\_AI.ipynb

# using:

# 

# Google Colab

# Jupyter Notebook

# 

# Step 2

# Install dependencies:

# 

# pip install chromadb

# pip install sentence-transformers

# pip install groq

# pip install streamlit

# pip install pymupdf

# pip install python-docx

# pip install pandas

# 

# Step 3

# Run notebook cells in order:

# 

# Step 4

# Launch the dashboard

# 

# The notebook automatically creates:

# 

# backend.py

# app.py

# Launch Streamlit:

# 

# streamlit run app.py

# 

# Example Queries

# 

# Dataset 1

# What are the key findings about AI in healthcare?

# Dataset 2

# What approvals are required for accompanied travel?

# Dataset 3

# What onboarding documents are required for crew members?

# 

# Future Work

# Automated contract validation

# Knowledge graph reasoning

# English-Welsh multilingual retrieval

# Real-time compliance monitoring

# Enterprise repository integration

# Enhanced chart and figure understanding

# 

# AI Usage Disclosure

# Generative AI tools were used for language refinement and debugging support during development. All architecture design, implementation, retrieval strategy, compliance logic, testing, validation, dataset analysis, evaluation and final outputs were independently reviewed and verified by the author.

