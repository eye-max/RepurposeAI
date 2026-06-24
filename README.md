**Problem**:
Content creators and marketers often spend hours manually rewriting the same article for different platforms, each requiring a unique tone, format, and audience approach. This repetitive process is time-consuming, inconsistent, and difficult to scale.

**Solution**:
AI Multi-Agent Content Repurposing System
I built an AI-powered content repurposing workflow that transforms a single article into multiple platform-specific content assets automatically. Using AI agents and workflow automation, the system generates a LinkedIn post, Facebook post, and email newsletter from one source article, then sends all outputs to Notion for human review and approval before publishing.

**Objective**:
One article goes in. Three platform-ready content pieces come out. A human reviews and approves before anything is published.

**Tech Stack**
- n8n
- Groq API
- Llama 3.3 70B
- Notion API
- Web Forms

**Workflow Overview**
1. User submits article
2. n8n processes input
3. Groq generates LinkedIn post
4. Groq generates Facebook post
5. Groq generates Email Newsletter
6. Outputs sent to Notion
7. Human reviews and approves

**Importing the Workflow**
1. Download `repurposeai-workflow.json`
2. Open n8n
3. Click Import Workflow
4. Configure your Groq and Notion credentials
5. Run the workflow
