# PolicyForge AI
# PolicyForge AI  
### AI-Powered Cybersecurity Policy Calculator for SMEs

![Status](https://img.shields.io/badge/status-active-success)
![Version](https://img.shields.io/badge/version-1.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Architecture](https://img.shields.io/badge/architecture-AI%20%7C%20Automation%20%7C%20SQL-orange)
![Framework Alignment](https://img.shields.io/badge/frameworks-NIST%20800--53%20%7C%20ISO%2027001-purple)
![Built With](https://img.shields.io/badge/built%20with-AI%20Automation%20Platform-red)

---

## Overview

PolicyForge AI is an AI-powered cybersecurity governance platform that enables small and medium-sized enterprises (SMEs) to automatically generate customized cybersecurity policies, standards, and procedures aligned with globally recognized frameworks such as:

- NIST 800-53
- ISO/IEC 27001
- ISO/IEC 27002

The platform bridges the gap between cybersecurity standards and practical implementation by transforming organizational inputs into structured, professional cybersecurity documentation.

---

## Live Application

**Access the live platform:**  
https://policy-forge-ai.base44.app/

---

## Table of Contents

- Overview  
- Problem Statement  
- Solution  
- Key Features  
- System Architecture  
- Technology Stack  
- Workflow Architecture  
- Database Architecture  
- Automation Architecture  
- Installation (Development Context)  
- Usage  
- Project Structure  
- Security Considerations  
- Roadmap  
- Author  
- License  

---

## Problem Statement

Small and medium-sized enterprises face major challenges in implementing cybersecurity governance:

- Lack of cybersecurity expertise  
- High cost of cybersecurity consultants  
- Complex compliance requirements  
- Absence of structured policy documentation  
- Difficulty translating frameworks into actionable policies  

This leaves SMEs vulnerable to:

- Data breaches  
- Compliance violations  
- Operational disruptions  
- Financial and reputational damage  

---

## Solution

PolicyForge AI provides an automated, AI-driven platform that:

- Collects organizational cybersecurity context  
- Analyzes risk posture  
- Generates framework-aligned policies  
- Exports professional cybersecurity documentation  
- Logs usage analytics via backend automation  

---

## Key Features

### AI-Powered Policy Generation

Generates:

- Cybersecurity Policies  
- Cybersecurity Standards  
- Cybersecurity Procedures  

Based on:

- Organizational profile  
- Infrastructure  
- Risk exposure  
- Security maturity  

---

### Framework Alignment

Outputs are aligned with:

- NIST 800-53
- ISO 27001
- ISO 27002
- Industry cybersecurity best practices

---

### Interactive AI Agent

CyberAI agent performs:

- Organizational assessment  
- Requirement gathering  
- Policy generation  
- Document formatting  

---

### Automated Document Export

Supports export of:

- Word documents (.docx)
- Text documents (.txt)
- Structured governance documentation

---

### Backend Automation and Logging

Integrated with:

- Webhook automation
- SQL database logging
- Workflow orchestration pipelines

---

## System Architecture

### High-Level Architecture Diagram
             ┌──────────────────────┐
             │     User Interface   │
             │   PolicyForge AI    │
             └─────────┬──────────┘
                       │
                       ▼
             ┌──────────────────────┐
             │    AI Policy Agent   │
             │   (Policy Generator) │
             └─────────┬──────────┘
                       │
                       ▼
             ┌──────────────────────┐
             │   Document Generator │
             │   (Policy Output)   │
             └─────────┬──────────┘
                       │
            ┌──────────┴───────────┐
            ▼                      ▼
  ┌─────────────────┐   ┌─────────────────┐
  │ Automation Layer │   │ SQL Database    │
  │ (Webhook / Zap) │   │ User Tracking   │
  └─────────────────┘   └─────────────────┘
  
---

## Workflow Architecture

### Policy Generation Workflow
User Input → AI Agent → Risk Analysis → Policy Generation → Document Export → Database Logging


---

### Automation Workflow
Generate Document Button
↓
Webhook Trigger
↓
Automation Platform
↓
SQL Database Logging
↓
Document Delivery

---

## Database Architecture

### Table: CYBER_USERS_SIMPLE

| Column | Type | Description |
|------|------|-------------|
| ID | NUMBER | Unique identifier |
| NAME | VARCHAR | User name |
| EMAIL | VARCHAR | User email |
| PROFESSIONAL_ROLE | VARCHAR | User role |

---

## Technology Stack

### Frontend

- Web Application Interface
- AI Chat Interface

### Backend

- AI Policy Generation Engine
- Automation Workflow System
- Webhook Integration Layer

### Database

- Oracle SQL Database

### Automation

- Webhooks
- Workflow automation platform

---


---

## Usage

### Step 1: Access the platform

https://policy-forge-ai.base44.app/

---

### Step 2: Interact with AI Agent

Provide:

- Organization description
- Industry
- Infrastructure
- Security maturity

---

### Step 3: Generate Policy

AI generates:

- Cybersecurity policy
- Standards
- Procedures

---

### Step 4: Download Document

Export professional cybersecurity governance document.

---

## Security Considerations

The platform ensures:

- Secure handling of user inputs  
- Database integrity  
- Automation workflow validation  
- Controlled data storage  

---

## Roadmap

Future enhancements include:

- Cyber risk scoring engine  
- Compliance readiness scoring  
- Dashboard analytics  
- Multi-framework mapping  
- Continuous governance monitoring  

---

## Business Value

PolicyForge AI enables:

- Automated cybersecurity governance  
- Reduced reliance on consultants  
- Improved cybersecurity posture  
- Scalable compliance readiness  

---

## Author

**Vanya Sahi**  
Cybersecurity Strategist | AI Governance Builder | Systems Analyst  

---

## Repository Purpose

This repository demonstrates:

- AI governance automation architecture  
- Cybersecurity policy generation systems  
- Workflow automation and database integration  
- Enterprise-grade SaaS architecture design  

---

## Keywords

cybersecurity  
ai  
policy generation  
governance  
risk assessment  
automation  
sql  
nist  
iso27001  
saas  
security architecture  




