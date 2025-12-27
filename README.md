# Microsoft 365 Copilot Custom Agents

## Overview

This repository contains production-ready custom agents for Microsoft 365 Copilot designed to enhance enterprise productivity. These agents provide specialized capabilities for business professionals, including professional email writing assistance and advanced SQL query optimization.

## Featured Agents

### 1. Email Assistant Agent (Email_Assistant_Ak_2.1)

A professional email rewriting agent tailored for Indian corporate standards and MNC communication practices.

#### Features
- **Grammar & Syntax Correction**: Automatically fixes grammar, spelling, and sentence structure
- **Tone Enhancement**: Transforms casual or unclear messages into polite, professional business English
- **Indian MNC Standards**: Follows communication conventions specific to Indian multinational corporations
- **Multi-language Support**: Automatically detects and translates Hindi inputs to professional English
- **Context Awareness**: Maintains original intent while improving clarity and professionalism
- **Audience Adaptation**: Adjusts tone based on recipient seniority (senior leadership, peers, subordinates)

#### Capabilities
- Email rewriting and enhancement
- Grammar and tone correction
- Hindi to English translation (professional)
- Table/data to formal email conversion
- Email summarization
- Reply composition assistance

#### Use Cases
- Drafting professional emails to senior leadership
- Converting casual messages into formal business communication
- Translating Hindi messages into professional English
- Structuring complex messages with tables or data
- Ensuring consistency with corporate communication standards

---

### 2. Universal SQL Developer Agent

A comprehensive SQL query analyzer and optimizer supporting multiple database platforms.

#### Supported Databases
- **Oracle SQL** (PL/SQL)
- **Microsoft SQL Server** (T-SQL)
- **PostgreSQL**
- **MySQL**
- **SQLite**

#### Features
- **Cross-Platform Support**: Seamlessly works across multiple SQL dialects
- **Syntax Correction**: Identifies and fixes SQL syntax errors
- **Query Optimization**: Improves query performance through indexing suggestions and restructuring
- **CTE Expertise**: Validates and optimizes Common Table Expressions (WITH clauses)
- **Dialect Detection**: Automatically detects SQL engine from keywords or user specification
- **Recursive Query Support**: Handles complex recursive CTEs and multi-level joins

#### Capabilities
- SQL query debugging and correction
- Performance optimization recommendations
- CTE (Common Table Expression) validation and optimization
- Dialect conversion between SQL platforms
- Partial query completion and logic validation
- Complex join and subquery restructuring
- Best practice recommendations

#### SQL Operations Supported
- SELECT statements with complex joins
- INSERT, UPDATE, DELETE operations
- Subqueries and correlated subqueries
- Common Table Expressions (CTEs) and recursive CTEs
- Window functions and analytics
- Aggregate functions and GROUP BY operations
- CASE statements and conditional logic

#### Use Cases
- Debugging broken SQL queries
- Optimizing slow-running queries
- Converting between SQL dialects
- Creating efficient CTEs and recursive queries
- Validating complex join logic
- Performance tuning for large datasets

---

## How to Use These Agents

### In Microsoft 365 Copilot Studio

1. **Access Copilot Studio**: Navigate to Microsoft 365 admin center > Copilot Studio
2. **Create New Agent**: Click "New Agent" and select "Prompt-based"
3. **Configure Agent**:
   - Copy the agent instructions from the respective files:
     - `Email_Assistant_Ak_2.1.txt` for Email Assistant
     - `Universal_SQL_Developer_Agent.txt` for SQL Agent
   - Paste the entire instruction set into the "Instructions" field
4. **Save & Test**: Save the agent and test with sample inputs
5. **Deploy**: Publish the agent to your Microsoft 365 environment

### Integration Options

- **Teams Integration**: Use agents within Microsoft Teams conversations
- **Outlook Integration**: Embed in Outlook for quick email assistance
- **Web Access**: Access through Copilot Studio web interface
- **Plugin Development**: Extend with custom actions and APIs

---

## File Structure

```
Microsoft365-Copilot-Custom-Agents/
├── README.md                           # This file
├── Email_Assistant_Ak_2.1.txt         # Email Assistant Agent Instructions
├── Universal_SQL_Developer_Agent.txt  # SQL Developer Agent Instructions
└── SETUP_GUIDE.md                     # Detailed setup and configuration guide
```

---

## Agent Specifications

### Email Assistant Agent
- **Version**: 2.1
- **Type**: Prompt-based Agent
- **Language Support**: English, Hindi
- **Target Audience**: Indian MNC professionals
- **Response Style**: Professional, polite, mid-level business English

### SQL Developer Agent
- **Type**: Prompt-based Agent
- **SQL Engines**: 5 major platforms
- **Complexity**: Supports beginner to expert-level queries
- **Response Style**: Technical, educational, best-practice focused

---

## Key Benefits

### For Email Assistant
✅ Saves time in email composition and review
✅ Ensures professional communication standards
✅ Bridges language gaps (Hindi to English)
✅ Maintains corporate communication consistency
✅ Reduces miscommunication risks

### For SQL Developer
✅ Accelerates query development
✅ Improves query performance
✅ Ensures cross-platform compatibility
✅ Reduces debugging time
✅ Enforces SQL best practices

---

## Requirements

- Microsoft 365 subscription with Copilot Studio access
- Copilot Pro or higher tier for custom agents
- Active internet connection
- Modern web browser

---

## License

This project is provided as-is for use within Microsoft 365 environments. Please respect intellectual property rights and organizational policies when implementing these agents.

---

## Support & Contributions

For issues, improvements, or feedback:
1. Open an issue in this repository
2. Provide detailed description of your use case
3. Share any relevant error messages or examples

---

## Version History

### Version 1.0 (Current)
- ✅ Email Assistant Agent (v2.1)
- ✅ Universal SQL Developer Agent
- ✅ Core documentation

---

## Author

**Akash Dixit**
- GitHub: [@AkashhDixit](https://github.com/AkashhDixit)
- Focus: AI/Prompt Engineering, Data Analysis, Business Automation

---

## Disclaimer

These agents are designed to assist and enhance productivity. They should be used as tools to support human decision-making, not replace it. Always review agent outputs for accuracy and appropriateness before using in critical business communications.
