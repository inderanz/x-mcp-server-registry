---
name: Add MCP Server
about: Add a new MCP server to the registry
title: "[ADD SERVER] "
labels: ["enhancement", "mcp-server"]
assignees: ["inderanz"]
---

## 🚀 Add New MCP Server

Thank you for contributing to the MCP Server Registry! Please provide the following information to add your MCP server to our comprehensive directory.

### 📋 Required Information

#### 1. MCP Server - GitHub Repository
- **Repository URL**: [Provide the GitHub repository URL]
- **Repository Name**: [e.g., mcp-server-example]
- **Maintainer**: [Your GitHub username or organization]

#### 2. README with Instructions
- **README Status**: [ ] Complete with installation and usage instructions
- **Documentation Quality**: [ ] Clear examples and API documentation
- **Code Examples**: [ ] Working examples provided

#### 3. Local vs Remote MCP
- **Deployment Type**: [ ] Local only | [ ] Remote only | [ ] Both supported
- **Local Setup**: [Describe local installation process]
- **Remote Setup**: [Describe remote deployment process]
- **Configuration**: [Explain configuration requirements]

#### 4. Installation Guide
```bash
# Provide installation commands
npm install mcp-server-example
# or
pip install mcp-server-example
# or
go install github.com/example/mcp-server
```

#### 5. Tool Configuration
- **Tools Provided**: [List the tools/functions your server exposes]
- **Resources Available**: [List any resources (files, data) your server provides]
- **Prompts Supported**: [List any prompt templates your server includes]

Example:
```json
{
  "tools": [
    "search_database",
    "create_report",
    "analyze_data"
  ],
  "resources": [
    "database_schema",
    "api_documentation"
  ],
  "prompts": [
    "generate_report_template",
    "data_analysis_prompt"
  ]
}
```

#### 6. Authentication & Auth Model (If Any)
- **Authentication Required**: [ ] Yes | [ ] No
- **Auth Type**: [API Key | OAuth | JWT | None]
- **Environment Variables**: [List required environment variables]
- **Security Considerations**: [Describe any security requirements]

Example:
```bash
# Environment variables
export MCP_SERVER_API_KEY="your-api-key"
export MCP_SERVER_ENDPOINT="https://api.example.com"
```

### 📊 Server Details

#### Basic Information
- **Server Name**: [e.g., Example MCP Server]
- **Description**: [Brief description of what your server does]
- **Category**: [Select from: AWS, Google Cloud, Database, Search & Web, Development, AI/ML, Browser & Automation, Infrastructure, Utility, Research, Social Media, Data Sources]
- **Classification**: [Official | Community | Experimental]
- **Type**: [Tool | Resource | Prompt | Mixed]

#### Statistics (Optional)
- **Downloads**: [Number of downloads if available]
- **Release Date**: [YYYY-MM-DD]
- **Popularity Score**: [0-100, based on community usage]

#### Links
- **GitHub**: [Repository URL]
- **NPM**: [NPM package URL if applicable]
- **Documentation**: [Documentation URL]
- **Website**: [Official website if available]

### 🧪 Testing

- **Tested with Claude Desktop**: [ ] Yes | [ ] No
- **Tested with other MCP clients**: [ ] Yes | [ ] No
- **Working examples provided**: [ ] Yes | [ ] No

### 📝 Additional Information

#### Use Cases
[Describe common use cases for your MCP server]

#### Integration Examples
[Provide examples of how your server integrates with AI assistants]

#### Dependencies
[List any external dependencies or requirements]

#### Performance
[Any performance considerations or limitations]

### ✅ Checklist

Before submitting, please ensure:

- [ ] All required information is provided
- [ ] GitHub repository is public and well-maintained
- [ ] README includes clear installation and usage instructions
- [ ] Code examples are working and tested
- [ ] Authentication requirements are clearly documented
- [ ] Server follows MCP specification standards
- [ ] No sensitive information (API keys, passwords) is included

### 🔗 Related Links

- [MCP Specification](https://spec.modelcontextprotocol.io/specification/)
- [MCP Server Development Guide](https://modelcontextprotocol.io/docs/server-development)
- [Claude Desktop Documentation](https://docs.anthropic.com/claude/docs/claude-desktop)

---

**Thank you for contributing to the MCP ecosystem!** 🚀

Your server will be reviewed and added to the registry if it meets our quality standards. 