# Claude Workflow Project Setup Script

*AI Assistant: Use this script to guide new project setup with systematic questioning based on research-backed methodologies.*

## Setup Overview

This script implements the onboarding experience for new projects using the Claude Workflow methodology. Follow the questions in order to establish proper project foundation.

## Phase 1: Problem Validation Questions

**AI Instruction**: Ask these questions to validate the project before setup:

### Core Problem Discovery
1. **What problem does this project solve?**
   - Help the user articulate the core problem in customer/user language
   - Avoid jumping to solution descriptions

2. **Who has this problem?**
   - Identify specific user groups or use cases
   - Validate that this is a real problem affecting real people

3. **How do you know this problem exists?**
   - Look for evidence: personal experience, user feedback, market research
   - Ensure this isn't just a "nice to have" feature

4. **What happens if this problem isn't solved?**
   - Assess problem significance and urgency
   - Validate that solving this creates meaningful value

## Phase 2: Project Type Discovery

**AI Instruction**: Based on the validated problem, determine project characteristics:

### Technical Architecture Questions
1. **What type of application is this?**
   - Web application (frontend + backend)
   - API service or microservice
   - Desktop application
   - Mobile application
   - Command-line tool
   - Library or framework

2. **What's your preferred technology stack?**
   - Frontend: React, Vue, vanilla JS, etc.
   - Backend: Node.js, Python, Go, etc.
   - Database: PostgreSQL, MongoDB, SQLite, etc.
   - Note: Guide toward proven, well-documented choices

3. **Where will this be deployed?**
   - Cloud platforms: Vercel, Netlify, AWS, etc.
   - Self-hosted: VPS, local server
   - Desktop: Electron, native apps
   - Mobile: App stores, web apps

### Project Scope Questions
4. **Is this a completely new project or extending existing work?**
   - New/Greenfield: Full Walking Skeleton approach
   - Existing/Brownfield: Focus on integration and compatibility

5. **What's your timeline and commitment level?**
   - Weekend project: Minimal setup, quick iteration
   - Side project: Structured approach, sustainable pace
   - Commercial venture: Full documentation, scalable architecture

## Phase 3: AI Workflow Configuration

**AI Instruction**: Configure the AI assistance approach:

### Documentation Preferences
1. **How do you prefer to manage project documentation?**
   - In-repo (recommended for 2025): Markdown files, docs-as-code
   - External tools: Notion, Linear, GitHub Projects
   - Hybrid: Technical docs in-repo, planning external

2. **What's your experience level with Git workflows?**
   - Beginner: Provide extra guidance on Git commands
   - Intermediate: Standard workflow with best practices
   - Advanced: Minimal guidance, focus on methodology

### AI Assistant Integration
3. **Which AI tools are you using?**
   - Claude Code (terminal-based)
   - GitHub Copilot (in-editor)
   - Other AI assistants
   - Note: Adapt instructions for specific tool capabilities

## Phase 4: Project Structure Generation

**AI Instruction**: Based on answers, create project structure:

### Required Files
Create these files based on project type and preferences:

1. **README.md** - Project overview and setup instructions
2. **CLAUDE.md** - AI assistant instructions specific to this project
3. **.gitignore** - Appropriate for chosen technology stack
4. **phase-tracking.md** - Track progress through workflow phases

### Technology-Specific Setup
Generate appropriate configuration files:
- **Web app**: package.json, index.html, basic components
- **API service**: requirements.txt, main.py, basic routes
- **CLI tool**: setup.py, main module, argument parsing

### Walking Skeleton Structure
Create minimal end-to-end implementation:
- Basic application structure
- Simple deployment configuration
- One working feature that exercises full stack
- Basic testing setup

## Phase 5: Next Steps Setup

**AI Instruction**: Guide user to immediate next actions:

### Walking Skeleton Phase
1. **Create Walking Skeleton issue** in project tracker
2. **Set up development environment** with chosen stack
3. **Implement minimal end-to-end feature** 
4. **Deploy to chosen platform** (even if basic)
5. **Document architecture decisions** in decision log

### Success Criteria
The setup is complete when:
- [ ] Project structure exists and makes sense
- [ ] Development environment works
- [ ] Basic deployment pipeline functions  
- [ ] AI assistant has proper project context
- [ ] First Walking Skeleton task is defined

## Implementation Notes

**For AI Assistants**: 
- Ask questions one at a time, wait for answers
- Adapt follow-up questions based on responses
- Provide specific recommendations when user is uncertain
- Reference research papers when explaining methodology choices
- Create all files and folders as discussed

**For Users**:
- Be honest about your experience level and timeline
- Think about the actual problem you're solving, not just the technology
- Don't over-engineer the initial setup
- Focus on getting something working end-to-end first

---

*This script implements onboarding based on GitLab Product Development Flow (problem validation), Walking Skeleton methodology (minimal implementation), and AI workflow patterns research (structured questioning).*