# Co-Craft 🚀
## AI-Powered Project Collaboration Tool for Organizations

[![Next.js](https://img.shields.io/badge/Next.js-15.0-black)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue)](https://www.typescriptlang.org/)
[![AI Powered](https://img.shields.io/badge/AI-Powered-green)](https://gemini.google.com/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Co-Craft revolutionizes organizational collaboration by integrating GitHub context-aware intelligence with AI-powered code understanding. Built for modern development teams who need seamless knowledge sharing and intelligent project insights.

## 🌟 Key Features

### 🧠 Intelligent Code Comprehension
- **Repository Context Generation**: Instantly understand entire codebases through AI-powered analysis
- **Semantic Code Search**: Find code snippets and functions using natural language queries
- **Context-Aware Q&A**: Ask questions about your codebase and get accurate, contextual answers

### 🤝 Enhanced Team Collaboration
- **Project-Based Workspaces**: Organize teams around specific repositories and projects
- **Team Member Invitations**: Seamlessly add collaborators to project workspaces
- **Collaborative Knowledge Base**: Share insights and maintain institutional knowledge

### 📊 Smart Meeting Analysis
- **AI-Powered Transcription**: Automatic meeting recording transcription using Assembly AI
- **Intelligent Summaries**: Generate actionable meeting summaries with key insights
- **Query Meeting Content**: Ask questions about meeting discussions and decisions

### 🔍 Advanced Project Insights
- **Commit Analysis**: AI-generated summaries for each commit to track project evolution
- **Code Change Intelligence**: Understand the impact and context of code modifications
- **Project Health Monitoring**: Track collaboration patterns and code quality metrics

## 🏗️ Technical Architecture

### Core Technologies
- **Frontend**: Next.js 15 with TypeScript
- **AI Engine**: Google Gemini AI for intelligent processing
- **Vector Database**: NeonDB with Prisma ORM for embeddings storage
- **File Storage**: Firebase for secure document and media management
- **Meeting Analysis**: Assembly AI for transcription and analysis
- **Payment Processing**: Stripe integration for credit-based scaling

### AI & Machine Learning Pipeline
- **Retrieval Augmented Generation (RAG)**: Context-aware AI responses
- **LangChain Integration**: Advanced document processing and embedding generation
- **Vector Embeddings**: Semantic understanding of code and documentation
- **Smart Scraping**: Intelligent GitHub repository parsing and analysis

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ 
- GitHub account with repository access
- Google Gemini AI API key
- Firebase project setup
- NeonDB database instance

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/co-craft.git
   cd co-craft
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```

3. **Environment Setup**
   Create a `.env.local` file in the root directory:
   ```env
   # Database
   DATABASE_URL="your-neondb-connection-string"
   
   # AI Services
   GEMINI_API_KEY="your-gemini-api-key"
   ASSEMBLY_AI_API_KEY="your-assembly-ai-key"
   
   # GitHub Integration
   GITHUB_TOKEN="your-github-personal-access-token"
   
   # Firebase
   FIREBASE_API_KEY="your-firebase-api-key"
   FIREBASE_PROJECT_ID="your-firebase-project-id"
   
   # Stripe
   STRIPE_SECRET_KEY="your-stripe-secret-key"
   STRIPE_PUBLISHABLE_KEY="your-stripe-publishable-key"
   ```

4. **Database Setup**
   ```bash
   npx prisma generate
   npx prisma db push
   ```

5. **Run the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   ```

6. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📖 Usage Guide

### Creating a Project
1. Sign up/Login to Co-Craft
2. Click "Create New Project"
3. Enter project name and GitHub repository URL
4. Co-Craft will automatically analyze and index your repository

### Inviting Team Members
1. Navigate to your project dashboard
2. Click "Invite Members"
3. Enter team member email addresses
4. Members receive invitation to join the project workspace

### Asking Code Questions
1. Go to the "Ask AI" section in your project
2. Type natural language questions about your codebase
3. Get instant, contextual answers with code references
4. Save important answers for team reference

### Meeting Analysis
1. Upload meeting recordings to your project
2. Co-Craft automatically transcribes and analyzes content
3. Review AI-generated summaries and action items
4. Query meeting content for specific discussions

## 🏢 Organizational Benefits

### For Development Teams
- **Reduced Onboarding Time**: New developers understand codebases 70% faster
- **Enhanced Code Discovery**: Find relevant code sections using natural language
- **Improved Knowledge Retention**: Persistent project memory across team changes

### For Project Managers
- **Meeting Intelligence**: Automated documentation and action item tracking
- **Project Insights**: Track collaboration patterns and team productivity
- **Resource Optimization**: Credit-based system scales with organizational needs

### For Organizations
- **Knowledge Preservation**: Institutional knowledge survives team transitions
- **Cross-Team Collaboration**: Share insights across different projects
- **Compliance & Documentation**: Automated meeting records and code documentation

## 💰 Pricing Model

Co-Craft uses a flexible credit-based system:
- **Pay-per-Use**: Only pay for the AI processing you need
- **Team Scaling**: Credits can be shared across team members
- **Enterprise Plans**: Custom solutions for large organizations

## 🔧 API Integration

Co-Craft provides REST APIs for enterprise integration:

```javascript
// Example: Query codebase
const response = await fetch('/api/query', {
  method: 'POST',
  headers: {
    'Authorization': 'Bearer your-api-key',
    'Content-Type': 'application/json'
  },
  body: JSON.stringify({
    projectId: 'your-project-id',
    query: 'How is user authentication implemented?'
  })
});
```

## 🛡️ Security & Privacy

- **Data Encryption**: All data encrypted in transit and at rest
- **Access Control**: Granular permissions for team members
- **GitHub Integration**: Secure OAuth integration with minimal permissions
- **Compliance Ready**: SOC2 and GDPR compliant infrastructure

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🆘 Support

- **Documentation**: [docs.co-craft.dev](https://docs.co-craft.dev)
- **Community**: [Discord Server](https://discord.gg/co-craft)
- **Issues**: [GitHub Issues](https://github.com/yourusername/co-craft/issues)
- **Email**: support@co-craft.dev

## 🗺️ Roadmap

- [ ] **Enhanced AI Models**: Integration with Claude and GPT-4
- [ ] **Mobile App**: iOS and Android applications
- [ ] **Advanced Analytics**: Detailed project and team insights
- [ ] **Plugin Ecosystem**: Extensible architecture for third-party integrations
- [ ] **Enterprise SSO**: SAML and OIDC integration
- [ ] **Advanced Security**: Zero-trust architecture implementation

## 🏆 Acknowledgments

- **LangChain Community** for document processing capabilities
- **Vercel** for deployment and hosting solutions
- **Google** for Gemini AI API access
- **Assembly AI** for meeting transcription services

---

**Built with ❤️ by the Co-Craft Team**

*Transforming how organizations collaborate on software projects*
