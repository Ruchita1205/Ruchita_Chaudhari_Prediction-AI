# Ruchita_Chaudhari_Prediction-AI
# Prediction AI – Startup & Project Risk Analyzer

Prediction AI is an AI-assisted decision-support system designed to evaluate startup ideas, business proposals, and project concepts. By analyzing project parameters, market conditions, and operational variables, the system quantifies risk, assesses project feasibility, and generates structured, actionable strategic guidance.

---

## 📌 Output Capabilities

The system takes project information, market/competitor context, risk assessment results, SWOT analysis, and feasibility analysis to generate:

* **Risk Assessment & Status Scoring**
* **Automated SWOT Analysis**
* **Feasibility Analysis**
* **Strategic Recommendations**
* **Risk Mitigation Strategies**
* **Improvement Suggestions**
* **Assessment report**

---

## 🎯 Project Objectives

* **Data Collecting:** Collect and structure important project information.
* **Market Intelligence:** Analyze target market and competitor conditions.
* **Risk Evaluation:** Identify and quantify project risks.
* **Risk Classification:** Classify projects according to calculated risk levels.
* **Success Estimation:** Estimate project success probability accurately.
* **Strategic Assessment:** Generate automated SWOT and feasibility analyses.
* **Actionable Recommendations:** Convert identified risks into concrete strategic guidance.
* **Continuous Improvement:** Suggest targeted improvements across key operational domains.

---

## 🔄 System Workflow

```text
Project Information
        ↓
Market & Competitor Analysis
        ↓
Risk Assessment
        ↓
Risk Score & Risk Status
        ↓
Success Probability
        ↓
SWOT Analysis
        ↓
Feasibility Analysis
        ↓
Strategic Recommendations
        ↓
Risk Mitigation
        ↓
Improvement Suggestions
        ↓
Action Plans
        ↓
Final Strategic Assessment



```

## Milestones
### Milestone 1 – Information Collection and Market Analysis

The first milestone establishes the project foundation.

It focuses on:

Project information collection
Target market identification
Target customer information
Market analysis
Competitor analysis
Structured project data

The output of Milestone 1 provides the context required for risk assessment.

### Milestone 2 – Risk Assessment and Feasibility

Milestone 2 evaluates the project's potential risks and feasibility.

It includes:

Market Competition assessment
Team Expertise assessment
Resource Availability assessment
Innovation Level assessment
Market Research assessment
Overall Risk Score
Risk Status
Success Probability
SWOT Analysis
Feasibility Analysis

Risk classification is based on the calculated risk score:

```
70 or above → High Risk
40–69       → Medium Risk
Below 40    → Low Risk
```

Success probability is calculated as:
```
Success Probability = max(0, 100 - Risk Score)
```

### Milestone 3 – Recommendations and Strategic Reasoning


Milestone 3 converts the results of the previous milestones into actionable strategies.

It includes:

#### Strategic Recommendations
Overall Strategic Recommendation
Risk-Based Recommendations
Market Recommendations
Technical Recommendations
Financial Recommendations
Operational Recommendations

#### Risk Mitigation

For identified risks, the system provides:

Risk
Category
Impact
Priority
Mitigation Strategy
Preventive Action
Contingency Action

#### Improvement Suggestions

The system provides improvement suggestions across:

Product
Market
Technical
Financial
Operational
Marketing

## LangGraph Workflow

The strategic reasoning workflow is organized around six stages:

```text
analyze_project
      ↓
analyze_risks
      ↓
generate_recommendations
      ↓
generate_mitigation
      ↓
generate_improvements
      ↓
generate_final_response
```

The workflow uses a shared state so that information generated at each stage can be passed to the next stage.

## Technology Stack
### Python

Used as the primary programming language for the application and backend logic.

### Streamlit

Used to provide the interactive application interface and dashboard.

### Google Gemini

Used as the LLM reasoning component for generating strategic recommendations when configured.

### LangGraph

Used to organize the strategic reasoning process into connected workflow nodes.

### PostgreSQL / Database Layer

Used for structured storage of project and assessment information in the project implementation.

### HTML / CSS

Used for interface styling where required.


## Project Outcome

The project progresses from collecting project information to evaluating risks and finally generating strategic actions.

The overall goal is to provide a structured decision-support system that helps project teams understand:

What could go wrong → Why it matters → What can be done → How the project can be improved




