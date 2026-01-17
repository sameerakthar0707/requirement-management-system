Enterprise Requirement Management & Issue Tracking System
📌 Overview

The Enterprise Requirement Management & Issue Tracking System is a backend-driven application designed to simulate how organizations manage business requirements across the software development lifecycle (SDLC).

The project emphasizes process adherence, documentation, traceability, testing, and communication — key expectations in consulting and enterprise environments.

🎯 Business Problem

Large organizations often struggle to:

Track evolving business requirements

Convert requirements into technical specifications

Ensure test coverage and lifecycle traceability

This project provides a structured solution to manage requirements from intake to closure.

🧠 Solution Approach

The system enables:

Capture of business requirements

Conversion into technical specifications

Lifecycle tracking (New → In Progress → Tested → Closed)

Mapping of requirements to test cases

Validation through automated testing

🏗 Architecture Overview
Business Requirement → Technical Specification → Implementation → Testing → Closure

⚙ Technology Stack

Backend Framework: FastAPI / Flask

Database: SQLite

Testing: pytest

Documentation: Markdown (BRD, Tech Specs, Test Cases)

📂 Project Structure
requirement-management-system/
├── docs/            # Business & technical documentation
├── app/             # Application logic
├── tests/           # API and workflow tests
├── requirements.txt
└── README.md

📑 Documentation Included

Business Requirement Document (BRD)

Technical Specification

Test Case Mapping

These artifacts reflect real-world consulting deliverables.

🧪 Testing Strategy

API-level testing for core workflows

Validation of requirement status transitions

Ensures traceability between requirements and tests

🚀 How to Run
pip install -r requirements.txt
uvicorn app.main:app --reload

📈 Key Outcomes

Clear requirement traceability

Strong documentation discipline

Process-driven development

Test-backed implementation

🏢 Industry Relevance

This project demonstrates:

SDLC understanding

Business-to-technology translation

Enterprise documentation practices

Consulting-ready engineering mindset

🔮 Future Enhancements

Role-based access control

Frontend UI integration

Reporting dashboards

Workflow automation
