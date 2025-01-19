# Build and extend agents with Copilot Studio

Microsoft Copilot Studio provides a comprehensive platform for building and extending AI-powered agents. Here's a detailed breakdown of its capabilities:

## Building Agents

**Basic Creation Methods**
- Create agents through a simple interface using natural language or manual configuration[1]
- Build declarative agents quickly using the Describe tab for conversational authoring or Configure tab for manual setup[1]
- Available in multiple languages including English, French, German, Spanish, and others[1]

**Development Approaches**
- Low-code graphical development environment for easy agent creation[6]
- Natural language-based agent creation through conversational interface[2]
- Option to skip conversation interface and directly configure agent details[11]

## Knowledge Integration

**Sources and Capabilities**
- Add knowledge from multiple sources including:
  - Microsoft Graph
  - SharePoint
  - Public websites
  - Dataverse
  - Internal documentation[7]
- Connect to over 1,500 prebuilt data connectors across Microsoft and non-Microsoft sources[7]

**Generative AI Features**
- Instant knowledge capability for answering queries without manual topic creation[5]
- AI general knowledge integration for broader response capabilities[14]
- Generative orchestration for dynamic topic and action selection[14]

## Customization Options

**Agent Enhancement**
- Create custom topics and conversation flows[11]
- Add images, video clips, adaptive cards, and variable expressions[5]
- Configure agent personality, tone, and behavior through instructions[2]

**Integration Features**
- Build plugins and connectors for the Microsoft 365 ecosystem[6]
- Connect to external systems like SAP, Workday, and ServiceNow[8]
- Create custom actions for specific business processes[11]

## Deployment and Management

**Publishing Options**
- Deploy to multiple channels including:
  - Microsoft Teams
  - SharePoint
  - Microsoft 365 Copilot Chat
  - Websites
  - Social media platforms[7]

**Security and Governance**
- Manage access controls and user permissions[11]
- Configure secure connectors for knowledge and custom actions[11]
- Set content moderation levels for generative answers[6]

## Testing and Optimization

**Quality Assurance**
- Test agents in real-time using the Test Agent Canvas[4]
- Track conversation flows with Activity map functionality[5]
- Monitor agent performance through built-in analytics[6]

**Continuous Improvement**
- Update agent instructions and knowledge sources as needed[1]
- Refine conversation flows based on user interactions[4]
- Optimize response generation through generative AI settings[6]

Citations:
[1] https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/copilot-studio-agent-builder-build
[2] https://learn.microsoft.com/en-gb/microsoft-copilot-studio/fundamentals-get-started
[3] https://abhishekdhoriya.com/what-is-microsoft-copilot-studio-ai-powered/
[4] https://www.cxtoday.com/data-analytics/what-is-microsoft-copilot-studio-and-how-can-i-create-a-custom-agent/
[5] https://learn.microsoft.com/en-us/microsoft-copilot-studio/nlu-gpt-quickstart?WT.mc_id=javascript-00000-gllemos
[6] https://blog.prodwaregroup.com/artificial-intelligence/microsoft-copilot-studio-explained/
[7] https://www.microsoft.com/en-us/microsoft-copilot/microsoft-copilot-studio
[8] https://www.microsoft.com/en-us/microsoft-365/blog/2023/11/15/introducing-microsoft-copilot-studio-and-new-features-in-copilot-for-microsoft-365/
[9] https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/copilot-studio-agent-builder
[10] https://learn.microsoft.com/en-us/microsoft-copilot-studio/fundamentals-what-is-copilot-studio?wt.mc_id=1reg_22790_webpage_reactor
[11] https://learn.microsoft.com/en-us/microsoft-copilot-studio/microsoft-copilot-extend-copilot-extensions
[12] https://learn.microsoft.com/vi-vn/microsoft-copilot-studio/advanced-ai-features
[13] https://learn.microsoft.com/en-us/training/paths/create-extend-custom-copilots-microsoft-copilot-studio/
[14] https://learn.microsoft.com/en-us/microsoft-copilot-studio/nlu-gpt-overview
[15] https://learn.microsoft.com/en-us/training/paths/power-virtual-agents-enhance/
[16] https://learn.microsoft.com/en-gb/power-platform/release-plan/2024wave1/microsoft-copilot-studio/planned-features
[17] https://www.youtube.com/watch?v=gVZiaufLTZM
[18] https://learn.microsoft.com/pl-pl/training/paths/work-power-virtual-agents/
[19] https://learn.microsoft.com/uk-ua/microsoft-copilot-studio/



# Essential prompting for GitHub Copilot in VS Code

GitHub Copilot prompting in VS Code requires a strategic approach to get the most effective code suggestions. Here's a comprehensive overview of essential prompting techniques:

## Core Prompting Principles

**Set Clear Goals**
- Begin with a high-level description of what you want to build or accomplish[1]
- Prime Copilot with the big picture before diving into specific details[1]
- Think of it as having a conversation with a pair programmer[1]

**Crafting Effective Prompts**
- Keep prompts single-focused, specific, and concise[7]
- Break complex tasks into simpler components[2]
- Provide explicit requirements and boundaries for the desired output[26]

## Context Management

**File Context**
- Open relevant files and close irrelevant ones in your IDE[2]
- Use the workspace context to help Copilot understand your project structure[13]
- Reference specific files by highlighting code or using file references[28]

**Code Comments**
- Write descriptive comments that explain the intended functionality[14]
- Use clear and specific language in your comments[14]
- Include implementation details and requirements in comment blocks[1]

## Best Practices

**Iterative Approach**
- Experiment with different prompt formulations if initial results aren't satisfactory[26]
- Start general, then get more specific with requirements[2]
- Review and refine generated code to match your needs[4]

**Specific Techniques**
- Use slash commands (like `/tests`, `/fix`, `/explain`) for common scenarios[28]
- Leverage custom instructions through `.github/copilot-instructions.md` for consistent coding patterns[3]
- Provide examples when needed to guide the output format[2]

## Common Use Cases

**Code Generation**
- Write high-level comments describing desired functionality[1]
- Specify input/output requirements clearly[26]
- Include expected behavior and edge cases[2]

**Code Improvement**
- Ask for specific optimizations or improvements[21]
- Request error handling additions[21]
- Seek performance enhancements for existing code[21]

Remember that Copilot's effectiveness largely depends on the quality of your prompts and the context you provide[4]. Regular experimentation and refinement of your prompting techniques will lead to better results over time[26].

Citations:
[1] https://github.blog/developer-skills/github/how-to-write-better-prompts-for-github-copilot/
[2] https://docs.github.com/en/copilot/using-github-copilot/prompt-engineering-for-github-copilot
[3] https://code.visualstudio.com/docs/copilot/copilot-customization
[4] https://www.hatica.io/blog/prompt-engineering-with-github-copilot/
[5] https://xebia.com/academy/nl/training/github-copilot-prompt-engineering/
[6] https://devblogs.microsoft.com/visualstudio/how-to-use-comments-to-prompt-github-copilot-visual-studio/
[7] https://www.geeksforgeeks.org/prompt-engineering-tips-with-github-copilot/
[8] https://code.visualstudio.com/docs/copilot/getting-started
[9] https://www.youtube.com/watch?v=-Z_MjUAaurM
[10] https://www.linkedin.com/pulse/best-practices-prompting-github-copilot-vs-code-pamela-fox
[11] https://tilburg.ai/2024/08/github-copilot-prompt-guide/
[12] https://github.blog/developer-skills/github/how-to-use-github-copilot-in-your-ide-tips-tricks-and-best-practices/
[13] https://code.visualstudio.com/docs/copilot/overview
[14] https://code.visualstudio.com/docs/copilot/copilot-vscode-features
[15] https://docs.github.com/en/copilot/using-github-copilot/getting-code-suggestions-in-your-ide-with-github-copilot
[16] https://leadwithtech.in/github-copilot-elevating-productivity-with-context-over-prompts/
[17] https://www.udemy.com/course/master-generativeai-though-prompt-engineeringgithub-copilot/
[18] https://github.com/features/copilot/?culture=en-us
[19] https://www.simplilearn.com/free-copilot-prompt-engineering-course-skillup
[20] https://code.visualstudio.com/docs/copilot/prompt-crafting
[21] https://docs.github.com/en/copilot/using-github-copilot/guides-on-using-github-copilot/getting-started-with-prompts-for-copilot-chat
[22] https://www.youtube.com/watch?v=pXSCfpnC1hQ
[23] https://www.youtube.com/watch?v=9hZsOeIINg8
[24] https://www.accelebrate.com/library/how-to-articles/github-copilot-prompts
[25] https://docs.github.com/en/copilot/using-github-copilot/best-practices-for-using-github-copilot
[26] https://github.blog/developer-skills/github/how-to-write-better-prompts-for-github-copilot/
[27] https://www.udemy.com/course/prompt-engineering-mastering-chatgpt-github-copilot/
[28] https://docs.github.com/en/copilot/using-github-copilot/asking-github-copilot-questions-in-your-ide
[29] https://github.blog/developer-skills/github/what-can-github-copilot-do-examples/
[30] https://github.com/Azure/Security-Copilot/blob/main/Customer%20Guides/Prompting%20Tips%20for%20Copilot%20For%20Security/readme.md


# Explore Models with Azure AI Foundry Model Catalog
Azure AI Foundry's Model Catalog serves as a comprehensive hub for discovering and implementing AI models. Here's a detailed overview of its key aspects:

## Core Features

**Model Discovery**
- Access to a diverse range of foundation models from Microsoft, OpenAI, Hugging Face, Meta, Mistral AI, and other partners[1][4]
- Models are pre-packaged for immediate use and optimized for Azure AI Foundry implementation[4]
- Browse models by task, compare benchmarks, and experiment in the playground environment[4]

## Model Collections

**Three Primary Categories**
- Azure AI Curated Models: Popular third-party models optimized for Azure AI platform[8]
- Azure OpenAI Models: Exclusive models available through Azure OpenAI Service[8]
- Hugging Face Hub Models: Extensive collection accessible for real-time inference[8]

## Deployment Options

**Flexible Implementation Methods**
- Standard Deployment: For Azure OpenAI models with enterprise features[3]
- Models as a Service (MaaS): Serverless API deployment with pay-as-you-go token billing[3]
- Open and Custom Models: Self-hosted options with managed infrastructure[3]

## Development Workflow

**Project Stages**
- Define and Explore: Test models against specific use cases[7]
- Build and Customize: Develop solutions using selected models and tools[7]
- Assess and Improve: Optimize application performance through evaluation tools[7]

## Model Capabilities

**Key Functions**
- Evaluation: Test model accuracy using custom data without infrastructure setup[4]
- Fine-tuning: Customize models to specific needs and use cases[8]
- Scaling: Deploy models with enterprise-grade security and governance[4]
- RAG Integration: Implement retrieval-augmented generation with vector indexes[10]

The platform emphasizes ease of use while maintaining enterprise-level security and scalability, making it suitable for both experimentation and production deployment.

Citations:
[1] https://microsoftlearning.github.io/mslearn-ai-studio/Instructions/02-Explore-model-catalog.html
[2] https://azure.microsoft.com/en-au/products/ai-foundry/
[3] https://learn.microsoft.com/vi-vn/azure/ai-studio/concepts/deployments-overview
[4] https://azure.microsoft.com/en-us/products/ai-model-catalog?WT.mc_id=aiml-138114-kinfeylo
[5] https://www.youtube.com/watch?v=ZZBNa7Kuhq8
[6] https://azure.microsoft.com/en-in/products/ai-model-catalog
[7] https://learn.microsoft.com/th-th/azure/ai-studio/what-is-ai-studio
[8] https://learn.microsoft.com/en-us/azure/machine-learning/concept-model-catalog?view=azureml-api-2
[9] https://ai.azure.com/explore/models?selectedTask=chat-completion
[10] https://learn.microsoft.com/en-us/azure/ai-studio/how-to/model-catalog-overview?WT.mc_id=academic-105485-koreyst
[11] https://www.linkedin.com/pulse/exploring-azure-ai-model-catalog-khaleel-shaik-jn2zc
[12] https://ai.azure.com/explore/models
[13] https://ai.azure.com/explore/models?selectedCollection=phi


# Sessions: Azure AI and RAG Development Resources 📚

## Azure AI Agent Service Lab 🤖
Learn to build your first agent with Azure AI Agent Service:  
[Build Your First Azure AI Agent Lab](https://github.com/gloveboxes/build-your-first-agent-with-azure-ai-agent-service-lab)

## RAG with Python Resources 🐍

### Presentation Materials
- **Slide Deck**: [RAGHack: Building RAG Apps in Python](https://speakerdeck.com/pamelafox/raghack-building-rag-apps-in-python)
- **PowerPoint Source**: [RAGHack-RAGInPython.pptx](https://github.com/microsoft/RAG_Hack/blob/main/slides/RAGHack-RAGInPython.pptx)

## Code Samples and Implementations 💻

### RAG on CSV
Explore CSV-based RAG implementation:  
[Python OpenAI Demos - RAG Implementation](https://github.com/pamelafox/python-openai-demos/blob/main/retrieval_augmented_generation.py)

### RAG with Azure AI Search
Interactive notebook demonstrating RAG with Azure AI Search:  
[RAG with Azure AI Search Notebook](https://github.com/Azure-Samples/rag-with-azure-ai-search-notebooks/blob/main/rag.ipynb)

### End-to-End RAG Solution
Complete RAG chat solution leveraging Azure AI Search:  
[Azure Search OpenAI Demo](https://github.com/Azure-Samples/azure-search-openai-demo)

---

> 📌 **Note**: Each link provides hands-on examples and implementations for different aspects of RAG development using Python and Azure services.

# Scalable RAG Solutions with Azure Cosmos DB 🚀

## Cosmos DB for NoSQL Implementation 📊
Access the comprehensive presentation:  
[RAGHack Cosmos DB NoSQL Slides](https://github.com/microsoft/RAG_Hack/blob/main/slides/RAGHACKCosmosDBNoSQL.pptx)

## Cosmos DB MongoDB API Integration 🍃
Explore MongoDB-specific implementation details:  
[RAGHack Cosmos DB MongoDB Slides](https://github.com/microsoft/RAG_Hack/blob/main/slides/RAGHackCosmosDBMongo.pptx)

---

## Azure Cosmos DB RAG Solutions Overview 💫

### NoSQL Implementation Benefits
- **Scalability**: Enterprise-grade performance
- **Flexibility**: Schema-agnostic data storage
- **Global Distribution**: Low-latency access worldwide
- **Integration**: Seamless Azure ecosystem connectivity

### MongoDB API Advantages
- **Compatibility**: Native MongoDB tooling support
- **Migration**: Easy transition from existing MongoDB
- **Performance**: Optimized query execution
- **Security**: Enterprise-grade security features

---

> 🔑 **Key Resources**:  
> Both presentations provide detailed insights into implementing RAG solutions using different Cosmos DB APIs, enabling robust, scalable document retrieval and generation capabilities.

---

💡 **Note**: For hands-on implementation, refer to both slide decks for architecture patterns, best practices, and detailed deployment guidance.

# Advanced RAG Development Resources 🔍

## GraphRAG Introduction & Implementation 🌐

### John's Code Repository
Explore comprehensive GraphRAG examples and implementations:  
[Intro to GraphRAG Repository](https://github.com/ms-johnalex/intro-to-graphrag)

## Agentic RAG with LangChain 🤖

### Contoso Creative Writer
Complete implementation of agentic RAG using LangChain:  
[Contoso Creative Writer Repository](https://github.com/Azure-Samples/contoso-creative-writer)

---

## Core Components Overview 🔧

### GraphRAG Features
- **Graph-Based Retrieval**: Intelligent document relationships
- **Knowledge Mapping**: Enhanced context understanding
- **Query Processing**: Optimized information retrieval
- **Semantic Search**: Advanced relationship exploration

### Agentic RAG Capabilities
- **Autonomous Agents**: Self-directed information processing
- **Chain Management**: Structured workflow execution
- **Context Handling**: Dynamic information integration
- **Creative Generation**: Enhanced content creation

---

## Implementation Resources 📚

### GraphRAG Tools
```python
# Core components available in repository
- Graph Construction
- Query Processing
- Relationship Mapping
- Semantic Analysis
```

### LangChain Integration
```python
# Key functionalities
- Agent Configuration
- Chain Orchestration
- Memory Management
- Output Generation
```

---

> 🔑 **Access Resources**:  
> Both repositories contain complete implementation details, documentation, and working examples for advanced RAG applications.

---

💡 **Note**: Follow repository-specific setup instructions for local development environment configuration.




