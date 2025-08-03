# 🤖 MCP Server Registry

> **Enterprise-grade comprehensive guide to Model Context Protocol servers across cloud providers, databases, and tools**

[![MCP Servers](https://img.shields.io/badge/MCP-Servers-295+-blue)](https://github.com/inderanz/x-mcp-server-registry)
[![Categories](https://img.shields.io/badge/Categories-20+-green)](https://github.com/inderanz/x-mcp-server-registry)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://github.com/inderanz/x-mcp-server-registry)

## 📊 Overview

This repository provides a comprehensive, curated directory of Model Context Protocol (MCP) servers, tools, and resources. With **295+ servers** across **20+ categories**, this registry serves as the definitive guide for developers, architects, and organizations looking to integrate MCP into their AI applications.

### 🎯 Key Features

- **📋 Comprehensive Directory**: 295+ MCP servers with detailed descriptions
- **🏷️ Smart Categorization**: 20+ categories including AWS, Google Cloud, Database, AI/ML
- **⭐ Popularity Tracking**: Server popularity and download statistics
- **🔍 Advanced Search**: Filter by name, description, category, and popularity
- **📚 Learning Resources**: Curated tutorials, courses, and video guides
- **🔗 Direct Links**: GitHub, NPM, and documentation links for each server

## 🚀 Quick Start

### What is Model Context Protocol (MCP)?

**Model Context Protocol (MCP)** is an open standard that enables AI agents and Large Language Models (LLMs) to securely connect with external tools, APIs, and data sources—across cloud, on-premise, and SaaS environments. MCP acts as a universal adapter, letting AI systems access live business data, trigger workflows, and perform actions, all through a single, standardized protocol.

### Key Benefits

- **🔗 Unified Integration**: Replace dozens of custom APIs with one protocol
- **🔒 Security & Control**: Explicit permissions, local deployment, full auditability
- **📈 Scalability**: Add new tools instantly—no need to rewire your AI stack
- **🚀 Future-Proof**: Adopted by leading AI platforms (Anthropic, OpenAI, Google, Microsoft)

## 📚 Learning Resources

### 🎓 Free MCP Course (Hugging Face)

Start with the **[free MCP course from Hugging Face](https://huggingface.co/learn/mcp-course/unit0/introduction)**, built in partnership with Anthropic:

- **MCP Fundamentals**: Core concepts, architecture, and components
- **Hands-on Practice**: Build real MCP applications with pre-configured environments
- **Use Case Projects**: Solve real-world problems and share with the community
- **Certification**: Earn certificates for fundamentals or full completion
- **Community**: Join Discord study groups and collaborate with peers

*Designed for 3-4 hours per week with quizzes, assignments, and challenges.*

### 🔧 Practical Tutorials

**Ready to build?** Check out the **[step-by-step tutorial on Towards Data Science](https://towardsdatascience.com/model-context-protocol-mcp-tutorial-build-your-first-mcp-server-in-6-steps/)**:

1. **Environment Setup**: Configure your development environment with FastMCP
2. **Server Architecture**: Understand MCP client-server architecture
3. **Code Implementation**: Build a custom code-to-diagram MCP server
4. **GitHub Integration**: Extract and visualize code from GitHub repositories
5. **Claude Desktop Integration**: Connect your server to Claude Desktop
6. **Production Deployment**: Deploy your MCP server for production use

### 📺 Video Tutorials

**Prefer video learning?** Check out these comprehensive MCP video tutorials:

- **[🎥 MCP Video Tutorial 1](https://www.youtube.com/watch?v=I7CXNA3LYck)** - Model Context Protocol (MCP) Explained in 10 Minutes!
- **[🎥 MCP Video Tutorial 2](https://www.youtube.com/watch?v=E2DEHOEbzks)** - Model Context Protocol (MCP) Explained for Beginners: AI Flight Booking Demo!
- **[🎥 MCP Video Tutorial 3](https://www.youtube.com/watch?v=RhTiAOGwbYE)** - MCP vs API: Simplifying AI Agent Integration with External Data
- **[🎥 MCP Video Tutorial 5](https://www.youtube.com/watch?v=u546On9iEBk)** - MCP vs A2A vs RAG Explained Simply
- **[🎥 MCP Video Tutorial 6](https://www.youtube.com/watch?v=ZoZxQwp1PiM)** - The Ultimate MCP Crash Course - Build From Scratch

### 📋 Official Resources

- **[Official MCP Specification](https://spec.modelcontextprotocol.io/specification/)** - The definitive technical reference
- **[MCP Toolbox for Databases](https://googleapis.github.io/genai-toolbox/getting-started/introduction/)** - Official documentation
- **[MCP Toolbox GitHub](https://github.com/googleapis/genai-toolbox)** - Source code and examples

## 🏗️ How MCP Works

### Architecture Overview

MCP adopts a **client-server architecture** where:

- **MCP Clients** (AI apps, IDEs, chatbots) connect to **MCP Servers** (tool/data adapters)
- **MCP Host** provides the runtime environment (Claude Desktop, IDEs with MCP extensions)
- **MCP Servers** expose tools, data, and workflows for clients to discover and invoke

### Server Components

MCP servers support three types of components:

1. **📄 Resources**: Data, files, and documents that serve as external knowledge base
2. **🔧 Tools**: Executable functions and integrations with other programs
3. **💬 Prompts**: Pre-defined instruction templates to guide LLM output

## 🔒 Security & Best Practices

### Core Principles

- **Principle of Least Privilege**: Only expose what's needed
- **Strong Authentication**: Use encrypted transport and regular audits
- **Vet All Servers**: Prefer official or vendor-maintained integrations
- **Local Deployment**: Maintain full control over your data and tools

### Enterprise Considerations

- **Explicit Permissions**: You decide what your AI can access
- **Full Auditability**: Complete visibility into all interactions
- **Vendor Independence**: Avoid lock-in with standardized protocol

## 📊 MCP Server Directory

### 🌟 Top Popular Servers (85%+ Popularity)

| Server Name | Type | Description | Downloads | Links |
|-------------|------|-------------|-----------|-------|
| **BigQuery MCP** | Data Analytics | Query and analyze data in Google BigQuery with advanced analytics capabilities | 11,200 | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-bigquery) |
| **Vertex AI MCP** | AI/ML Platform | Access Google's Vertex AI machine learning services with advanced AI capabilities | 9,800 | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-vertex-ai) |
| **Google Drive MCP** | File Management | Access and manage Google Drive files and folders with full file operations | 8,900 | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-google-drive) |
| **Google Calendar MCP** | Calendar Management | Manage Google Calendar events and schedules with full calendar operations | 7,600 | [GitHub](https://github.com/google/mcp-server-google-calendar) |

### ☁️ Google Cloud Servers

| Server Name | Type | Description | Downloads | Links |
|-------------|------|-------------|-----------|-------|
| **Cloud Spanner MCP** | Database | Query and manage Google Cloud Spanner databases with global distributed SQL | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-cloud-spanner) |
| **CloudSQL MCP** | Database | Manage Google Cloud SQL databases with full database operations | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-cloudsql) |
| **Cloud Storage MCP** | File Management | Access and manage Google Cloud Storage buckets and objects | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-cloud-storage) |
| **Cloud Functions MCP** | Serverless | Deploy and manage Google Cloud Functions with serverless computing | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-cloud-functions) |
| **Cloud Run MCP** | Container | Deploy and manage Google Cloud Run containerized applications | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-cloud-run) |
| **Google GenAI Toolbox MCP** | AI/ML | Comprehensive Google Generative AI tools and capabilities | - | [GitHub](https://github.com/googleapis/genai-toolbox) |

### ☁️ AWS Servers

| Server Name | Type | Description | Downloads | Links |
|-------------|------|-------------|-----------|-------|
| **S3 MCP** | File Management | Access and manage Amazon S3 buckets and objects | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-s3) |
| **DynamoDB MCP** | Database | Query and manage Amazon DynamoDB NoSQL databases | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-dynamodb) |
| **ECS MCP** | Container | Manage Amazon ECS container orchestration | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-ecs) |
| **EKS MCP** | Kubernetes | Manage Amazon EKS Kubernetes clusters | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-eks) |
| **Lambda MCP** | Serverless | Deploy and manage AWS Lambda functions | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-lambda) |
| **Bedrock MCP** | AI/ML | Access AWS Bedrock AI services and models | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-bedrock) |
| **RDS/Aurora MCP** | Database | Manage Amazon RDS and Aurora databases | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-rds) |
| **ECR MCP** | Container Registry | Manage Amazon ECR container registries | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-ecr) |
| **CloudFormation MCP** | IaC | Manage AWS CloudFormation infrastructure as code | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-cloudformation) |
| **CDK MCP** | IaC | Manage AWS CDK infrastructure as code | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-cdk) |

### ☁️ Microsoft Azure Servers

| Server Name | Type | Description | Downloads | Links |
|-------------|------|-------------|-----------|-------|
| **Azure Blob Storage MCP** | File Management | Access and manage Azure Blob Storage containers and blobs | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-azure-blob) |
| **Azure Functions MCP** | Serverless | Deploy and manage Azure Functions serverless computing | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-azure-functions) |
| **Azure OpenAI MCP** | AI/ML | Access Azure OpenAI services and models | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-azure-openai) |
| **Cosmos DB MCP** | Database | Query and manage Azure Cosmos DB databases | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-cosmos-db) |

### 🗄️ Database Servers

| Server Name | Type | Description | Downloads | Links |
|-------------|------|-------------|-----------|-------|
| **PostgreSQL MCP** | Database | Query and manage PostgreSQL databases | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-postgresql) |
| **MySQL MCP** | Database | Query and manage MySQL databases | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-mysql) |
| **MongoDB MCP** | Database | Query and manage MongoDB NoSQL databases | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-mongodb) |
| **Redis MCP** | Cache/Database | Access and manage Redis in-memory data store | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-redis) |
| **Elasticsearch MCP** | Search | Search and analyze data with Elasticsearch | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-elasticsearch) |
| **Supabase MCP** | Database | Access Supabase PostgreSQL database and real-time features | - | [GitHub](https://github.com/supabase/mcp-server-supabase) |

### 🔍 Search & Web Servers

| Server Name | Type | Description | Downloads | Links |
|-------------|------|-------------|-----------|-------|
| **Brave Search** | Search | Search the web using Brave Search engine | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-brave-search) |
| **DuckDuckGo Search** | Search | Search the web using DuckDuckGo search engine | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-duckduckgo) |
| **ArXiv** | Research | Search and access academic papers from ArXiv | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-arxiv) |
| **DeepWiki MCP** | Research | Access Wikipedia knowledge and articles | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-deepwiki) |

### 🤖 AI/ML Servers

| Server Name | Type | Description | Downloads | Links |
|-------------|------|-------------|-----------|-------|
| **Ollama MCP** | AI/ML | Access local Ollama AI models and inference | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-ollama) |
| **Pinecone Developer MCP** | Vector Database | Access Pinecone vector database for embeddings | - | [GitHub](https://github.com/pinecone-io/mcp-server-pinecone) |
| **Vectara MCP Server** | Vector Database | Access Vectara vector database and search | - | [GitHub](https://github.com/vectara/mcp-server-vectara) |
| **Vizro MCP** | Data Visualization | Create interactive data visualizations with Vizro | - | [GitHub](https://github.com/mckinsey/vizro) |
| **Recraft AI MCP Server** | AI/ML | Access Recraft AI design and generation tools | - | [GitHub](https://github.com/recraft-ai/mcp-server-recraft) |

### 🔧 Development & Infrastructure

| Server Name | Type | Description | Downloads | Links |
|-------------|------|-------------|-----------|-------|
| **Terraform MCP** | IaC | Manage infrastructure with Terraform | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-terraform) |
| **Ansible MCP** | Automation | Automate IT infrastructure with Ansible | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-ansible) |
| **Git MCP** | Version Control | Manage Git repositories and operations | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-git) |
| **GitHub MCP** | Version Control | Access GitHub repositories and workflows | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-github) |
| **Kubernetes MCP** | Container Orchestration | Manage Kubernetes clusters and resources | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-kubernetes) |
| **Docker MCP** | Container | Manage Docker containers and images | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-docker) |
| **Python MCP** | Development | Execute Python code and manage environments | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-python) |
| **OpenTofu MCP** | IaC | Manage infrastructure with OpenTofu (Terraform fork) | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-opentofu) |

### 🌐 Browser & Automation

| Server Name | Type | Description | Downloads | Links |
|-------------|------|-------------|-----------|-------|
| **Playwright Browser Automation** | Browser Automation | Automate web browsers with Playwright | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-playwright) |
| **Chrome Browser Automation** | Browser Automation | Automate Chrome browser operations | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-chrome) |
| **Windows Desktop Control** | Desktop Automation | Control Windows desktop applications | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-windows) |

### 📱 Social Media & Communication

| Server Name | Type | Description | Downloads | Links |
|-------------|------|-------------|-----------|-------|
| **Slack MCP** | Communication | Send messages and manage Slack workspaces | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-slack) |
| **Discord MCP** | Communication | Send messages and manage Discord servers | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-discord) |

### 📊 Business & Productivity

| Server Name | Type | Description | Downloads | Links |
|-------------|------|-------------|-----------|-------|
| **Jira MCP** | Project Management | Access and manage Jira projects and issues | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-jira) |
| **Confluence MCP** | Documentation | Access and manage Confluence pages and spaces | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-confluence) |
| **PostHog MCP Server** | Analytics | Access PostHog product analytics and insights | - | [GitHub](https://github.com/posthog/mcp-server-posthog) |
| **GrowthBook MCP Server** | Analytics | Access GrowthBook A/B testing and feature flags | - | [GitHub](https://github.com/growthbook/mcp-server-growthbook) |

### 🔧 Utility & Tools

| Server Name | Type | Description | Downloads | Links |
|-------------|------|-------------|-----------|-------|
| **Filesystem MCP** | File System | Access and manage local file system | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-filesystem) |
| **Calculator** | Utility | Perform mathematical calculations | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-calculator) |
| **Time Anthropic** | Utility | Get current time and date information | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-time) |
| **Fetch Anthropic** | Utility | Fetch data from URLs and web resources | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-fetch) |

### 🧠 AI & Memory

| Server Name | Type | Description | Downloads | Links |
|-------------|------|-------------|-----------|-------|
| **Knowledge Graph Memory** | Memory | Store and retrieve knowledge graph data | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-knowledge-graph) |
| **Sequential Thinking** | AI | Enable sequential reasoning and step-by-step thinking | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-sequential-thinking) |

### 🆕 Emerging & Community Servers

| Server Name | Type | Description | Downloads | Links |
|-------------|------|-------------|-----------|-------|
| **Plane MCP Server** | Project Management | Access Plane project management platform | - | [GitHub](https://github.com/plane-ai/mcp-server-plane) |
| **Vapi MCP Server** | Voice AI | Access Vapi voice AI and conversation platform | - | [GitHub](https://github.com/vapi-ai/mcp-server-vapi) |
| **GroundDocs MCP Server** | Documentation | Access GroundDocs documentation platform | - | [GitHub](https://github.com/grounddocs/mcp-server-grounddocs) |
| **Jenius MCP Smart Device** | IoT | Control Jenius smart devices and IoT | - | [GitHub](https://github.com/jenius-ai/mcp-server-jenius) |
| **PDF.co MCP Server** | Document Processing | Process and manipulate PDF documents | - | [GitHub](https://github.com/pdfco/mcp-server-pdfco) |
| **Panther MCP Server** | Security | Access Panther security and compliance platform | - | [GitHub](https://github.com/panther-labs/mcp-server-panther) |
| **Alibaba Cloud FC MCP Server** | Serverless | Deploy and manage Alibaba Cloud Function Compute | - | [GitHub](https://github.com/alibaba-cloud/mcp-server-fc) |
| **Descope MCP Server** | Authentication | Access Descope authentication and user management | - | [GitHub](https://github.com/descope/mcp-server-descope) |
| **Mailmodo MCP Server** | Email Marketing | Access Mailmodo email marketing platform | - | [GitHub](https://github.com/mailmodo/mcp-server-mailmodo) |
| **Iaptic MCP Server** | Analytics | Access Iaptic analytics and insights | - | [GitHub](https://github.com/iaptic/mcp-server-iaptic) |
| **Liveblocks MCP Server** | Real-time | Access Liveblocks real-time collaboration | - | [GitHub](https://github.com/liveblocks/mcp-server-liveblocks) |
| **BoldSign MCP Server** | E-signature | Access BoldSign electronic signature platform | - | [GitHub](https://github.com/boldsign/mcp-server-boldsign) |
| **Audiense Insights MCP Server** | Social Analytics | Access Audiense social media insights | - | [GitHub](https://github.com/audiense/mcp-server-audiense) |
| **Baidu Vector Database MCP Server** | Vector Database | Access Baidu vector database for embeddings | - | [GitHub](https://github.com/baidu/mcp-server-vector-db) |
| **Debug AI MCP** | Development | Access Debug AI development and debugging tools | - | [GitHub](https://github.com/debug-ai/mcp-server-debug) |
| **Atla MCP Server** | Data Visualization | Access Atla data visualization platform | - | [GitHub](https://github.com/atla/mcp-server-atla) |
| **RSS MCP Server** | Content | Access RSS feeds and content aggregation | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-rss) |
| **Hunter MCP Server** | Email | Access Hunter email finder and verification | - | [GitHub](https://github.com/hunter-io/mcp-server-hunter) |
| **Runbook MCP Server** | Automation | Access Runbook automation and workflows | - | [GitHub](https://github.com/runbook/mcp-server-runbook) |
| **Dappier MCP Server** | Analytics | Access Dappier analytics and insights | - | [GitHub](https://github.com/dappier/mcp-server-dappier) |
| **HiveFlow MCP Server** | Workflow | Access HiveFlow workflow automation | - | [GitHub](https://github.com/hiveflow/mcp-server-hiveflow) |
| **Databutton MCP Server** | Development | Access Databutton development platform | - | [GitHub](https://github.com/databutton/mcp-server-databutton) |
| **Qiniu MCP Server** | Cloud Storage | Access Qiniu cloud storage and CDN | - | [GitHub](https://github.com/qiniu/mcp-server-qiniu) |
| **Codebase Context Dumper MCP** | Development | Extract and analyze codebase context | - | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/packages/server-codebase-context) |

## 🔍 Using This Registry

### Search & Filter

1. **Search by Name**: Find specific servers by name or description
2. **Filter by Category**: Narrow down by cloud provider, database, etc.
3. **Popularity Filter**: Focus on highly-rated servers
4. **Clear Filters**: Reset to view all servers

### Server Information

Each server entry includes:

- **📝 Description**: Detailed explanation of functionality
- **📊 Stats**: Download counts, release dates, popularity ratings
- **🔗 Links**: Direct links to GitHub, NPM, and documentation
- **🏷️ Categories**: Multiple category tags for easy discovery

### Popularity Badges

- **🔥 Popular**: Servers with 90%+ popularity rating
- **⭐ Growing**: Servers with 80%+ popularity rating
- **📈 Emerging**: Servers with 70%+ popularity rating

## 🛠️ Development

### Contributing

We welcome contributions to improve this registry:

1. **Add New Servers**: Submit new MCP servers with proper categorization
2. **Update Information**: Keep server details, links, and stats current
3. **Improve Documentation**: Enhance descriptions and usage examples
4. **Report Issues**: Flag outdated or incorrect information

### Adding a Server

To add a new MCP server to the registry:

```json
{
  "name": "Server Name",
  "type": "Tool/Resource/Prompt",
  "description": "Detailed description of functionality",
  "category": ["Category1", "Category2"],
  "classification": "Official/Community/Experimental",
  "stats": {
    "popularity": 85,
    "downloads": 1000,
    "releaseDate": "2024-01-01"
  },
  "links": {
    "github": "https://github.com/...",
    "npm": "https://npmjs.com/...",
    "documentation": "https://docs.example.com"
  }
}
```

## 📈 Statistics

- **Total Servers**: 295+
- **Categories**: 20+
- **Classifications**: Multiple (Official, Community, Experimental)
- **Popularity Range**: 0-100% rating system
- **Update Frequency**: Regular updates and maintenance

## 🤝 Community

### Get Involved

- **📖 Learn**: Start with the Hugging Face course
- **🔧 Build**: Follow the Towards Data Science tutorial
- **📺 Watch**: Check out the video tutorials
- **💬 Discuss**: Join MCP community discussions
- **🌟 Contribute**: Add servers and improve documentation

### Support

- **Documentation**: Comprehensive guides and tutorials
- **Examples**: Real-world implementation examples
- **Community**: Active developer community
- **Updates**: Regular registry updates and maintenance

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Anthropic**: For creating and maintaining the MCP standard
- **Hugging Face**: For the comprehensive MCP course
- **Towards Data Science**: For practical tutorials
- **Community Contributors**: For maintaining and improving the registry

---

**Built with ❤️ by [Inder Chauhan](https://www.linkedin.com/in/ichauhan/)**

*This registry is maintained as a community resource to help developers discover and integrate MCP servers effectively.* 