# 🤖 AzureFrontierGirls-DoughAI
Dough – Personal Finance Assistant Powered by Azure AI Agents
Part of the Azure Frontier Girls Challenge

Dough is an AI-powered personal finance assistant designed to help users understand, organize, and make smarter decisions about their money.

## 🚀 Project Overview
This project implements an AI agent (“Dough”) focused on personal finance awareness and decision support.
Dough behaves like a friendly, trustworthy, and intelligent companion — helping users plan budgets, analyze monthly income vs. expenses, and stay on track with financial goals.

Built using Azure AI Foundry, the assistant combines natural language intelligence with custom backend Actions to deliver practical, friendly, and real-time financial guidance. The system uses Azure AI Agents with custom Actions, allowing the AI to call external APIs to perform real calculations.


## 🛠️ Development :Azure AI Agent Setup Summary
I created a complete Azure AI solution as part of this project, following these steps:

**1. Azure Resource Creation**
I started by creating the required Azure resource to host the AI capabilities.

**2. Project Setup in Microsoft Foundry**
I created a new project inside Microsoft Foundry, which serves as the workspace for managing deployments, agents, and Actions.

**3. Model Deployment**
Inside the project, I deployed the gpt-4o-mini model, making it available for use within the agent.

**4. Agent Creation: DoughAI**
I created a new agent in Azure AI Foundry with the following configuration:

**Agent Name**: DoughAI

**Model Deployment**: gpt-4o-mini

**Agent Description**: Personal finance organizer

**Action**: Calculates the user’s monthly remaining balance and suggests a healthy financial distribution.

<img width="886" height="262" alt="image" src="https://github.com/user-attachments/assets/4d24d631-8fab-40f7-95de-0b1b124b2754" />


**Agent Instructions**:
“You are a personal finance agent that helps people organize their income and expenses. You act like a smart friend who gives financial advice in a simple, clear, and friendly way.
You do not provide investment recommendations or suggest investment products.
You do not answer questions outside the topic of personal finance.
You do not offer formal financial consulting and you do not ask for sensitive data.
Your tone should be warm, direct, modern, and fun.
You must explain concepts clearly, compare options, suggest good practices, and create practical, easy-to-follow plans.”

**Screenshots of responses, flow, and execution:**

1. first without the active action
<img width="886" height="626" alt="image" src="https://github.com/user-attachments/assets/3030db07-b818-4601-947c-e5e498002142" />

<img width="886" height="671" alt="image" src="https://github.com/user-attachments/assets/85059be5-6a04-4e8b-8358-5d1b598f1e95" />

<img width="886" height="656" alt="image" src="https://github.com/user-attachments/assets/57176bd1-a149-4d75-868b-454f39feade0" />

<img width="886" height="665" alt="image" src="https://github.com/user-attachments/assets/59376d83-0eda-4983-a982-e1d3743acac4" />

<img width="886" height="684" alt="image" src="https://github.com/user-attachments/assets/48300ee4-2fc6-4e99-962c-33f82f466019" />


2. then with the action active

<img width="886" height="572" alt="image" src="https://github.com/user-attachments/assets/b2f37f70-52fe-4191-9bc3-ff6eea331191" />

<img width="886" height="443" alt="image" src="https://github.com/user-attachments/assets/77af83bf-f00b-4b07-b8ba-1b2b7c31adbc" />

<img width="886" height="698" alt="image" src="https://github.com/user-attachments/assets/65570ebb-3cd5-4fb9-af13-414ca14825b9" />

<img width="886" height="441" alt="image" src="https://github.com/user-attachments/assets/734481f4-5188-4f1f-b42c-f741e14f9d71" />

<img width="886" height="446" alt="image" src="https://github.com/user-attachments/assets/ec3fa198-9e3c-4bbe-b5ce-1acae7dec2c9" />


## 🔮 Planned Future Actions

As the DoughAI personal financial assistant evolves, various advanced actions can be implemented to enhance its financial guidance capabilities.

**1. Create Financial Reminders**
This Action will allow DoughAI to schedule reminders for important financial tasks such as paying bills, credit card due dates, savings deposits, subscription renewals, and recurring financial obligations. The goal is to help users stay organized and avoid late fees or financial surprises.

**2. Categorize Expenses**
DoughAI will automatically classify user expenses into categories such as housing, transportation, food, leisure, subscriptions, and more. This Action will help users understand spending patterns and identify potential areas for cost optimization.

**3. Generate a Monthly Budget**
This Action will produce a personalized budget plan based on the user’s income, expenses, habits, and goals. It will allow DoughAI to create clear budget recommendations, track spending limits, and help users stick to a realistic monthly financial structure.

**4. Prioritize Debts**
This Action will evaluate a user’s outstanding debts and suggest a priority order using strategies like the Avalanche Method (highest interest first) or Snowball Method (smallest balance first). The goal is to help users pay off debts faster and reduce financial stress.

**5. Create Financial Goals**
With this Action, DoughAI will help users define clear financial goals—such as building an emergency fund, saving for a trip, buying a car, or paying down debt—along with timelines, contribution plans, and progress tracking.

**6. Calculate Emergency Fund Timeframe**
This Action will compute how long it will take for the user to build a complete emergency fund based on monthly savings capacity, the recommended emergency fund amount, and savings habits. This feature will provide realistic projections and motivate users to stay consistent.

## 📋 Tech Stack
- Azure AI Foundry (AI Studio)
- Azure AI Agents + Actions
- OpenAPI 3.0 specification for exposing APIs
- Visual Code Studio

## 📚 Additional Resources
- [ai.azure.com](https://ai.azure.com)
- [Azure OpenAI Service](https://learn.microsoft.com/azure/ai-services/openai/)
- [Microsoft Agent Framework](https://github.com/microsoft/agent-framework)
- [Azure AI Foundry](https://learn.microsoft.com/azure/ai-studio/)
