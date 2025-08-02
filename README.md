# Claude Workflow - Phased Development for Solo Developers + AI

A structured, research-backed workflow system for building ambitious software projects as a solo developer with AI assistance.

## What We're Building

This repository creates a **phased development workflow** specifically designed for solo developers working with AI coding assistants like Claude Code. Instead of ad-hoc development, we're establishing a systematic approach that:

1. **Gets working software deployed early** (Walking Skeleton phase)
2. **Builds features incrementally** through Minimal Viable Changes
3. **Uses AI to guide decision-making** through structured questioning
4. **Maintains high-quality documentation** without overwhelming overhead
5. **Scales enterprise methodologies** down to single-person projects

## The Core Problem We're Solving

**Traditional Challenge**: Solo developers often struggle with:
- Starting ambitious projects that never reach production
- Inconsistent development approaches across projects  
- Poor documentation that hurts future maintenance
- Lack of systematic decision-making frameworks
- Difficulty balancing planning vs execution

**Our Solution**: A reproducible workflow that provides:
- Clear phases with specific goals and artifacts
- AI-assisted questioning to drive each phase forward
- Lightweight but effective documentation strategies
- Battle-tested methodologies adapted for solo development
- Structured templates that work across different project types

## What Success Looks Like

When this workflow is complete, a solo developer should be able to:

1. **Clone this repository** into any new project folder
2. **Run through the Walking Skeleton phase** to get basic infrastructure deployed
3. **Use MVC phase templates** to add features systematically  
4. **Leverage AI questioning scripts** to make better decisions faster
5. **Maintain consistent documentation** across all their projects
6. **Feel confident** that they're following proven methodologies

## Getting Started with a New Project

### Quick Start (Current State)

1. **Create your new project directory**:
   ```bash
   mkdir my-new-project
   cd my-new-project
   ```

2. **Copy the workflow files**:
   ```bash
   # Copy core workflow files
   cp /path/to/claude-workflow/templates/CLAUDE.md ./
   cp /path/to/claude-workflow/human-validation-framework.md ./
   cp /path/to/claude-workflow/phase-templates/walking-skeleton.md ./
   cp /path/to/claude-workflow/phase-templates/mvc-phase.md ./
   cp /path/to/claude-workflow/ai-scripts/walking-skeleton-questions.md ./
   
   # Copy tracking templates (customize these)
   cp /path/to/claude-workflow/templates/phase-tracking.md ./
   cp /path/to/claude-workflow/templates/progress-log.md ./
   cp /path/to/claude-workflow/templates/decision-record.md ./decisions/
   
   # Create other project files
   mkdir decisions
   touch README.md
   ```

3. **Customize for your project**:
   - Edit `CLAUDE.md` to update project type, tech stack, and current phase
   - Update the project-specific context sections
   - Set your problem statement and success criteria

4. **Start development with AI**:
   - Claude will automatically understand the workflow from your `CLAUDE.md`
   - Begin with Walking Skeleton phase using the systematic questioning
   - Complete human validation at the end of each phase

### What Gets Copied to New Projects

**Core Workflow Files** (copy these):
- `templates/CLAUDE.md` - AI assistant instructions (customize for your project)
- `phase-templates/walking-skeleton.md` - Walking Skeleton phase template
- `phase-templates/mvc-phase.md` - MVC phase template for incremental features
- `ai-scripts/walking-skeleton-questions.md` - Systematic AI questioning framework
- `human-validation-framework.md` - Phase validation tools

**Project Tracking Templates** (copy and customize):
- `templates/phase-tracking.md` - Track progress through workflow phases
- `templates/progress-log.md` - Daily/weekly progress documentation
- `templates/decision-record.md` - Document important project decisions

**Project-Specific Files** (you create these):
- `README.md` - Project overview and setup instructions
- `decisions/` - Directory for decision records using the template

### Workflow Process

1. **Problem Validation** (use onboarding script)
2. **Walking Skeleton Phase** (minimal end-to-end implementation)
3. **MVC Phases** (incremental feature development)
4. **Human Validation** (at end of every phase)

*Note: This is the current manual process. Future versions will include automated setup scripts and better tooling.*

## Key Innovations

### Phased Approach
- **Walking Skeleton First**: Deploy minimal end-to-end functionality before building features
- **MVC Iterations**: Add one small, valuable change at a time
- **Clear Phase Gates**: Specific criteria for moving between phases

### AI Integration
- **Structured Questioning**: AI asks the right questions at the right time
- **Documentation Assistance**: AI helps maintain docs without overhead
- **Decision Support**: AI guides through complex architectural choices
- **Template Population**: AI helps fill out phase templates

### Solo Developer Focus
- **Sustainable Practices**: Designed for one person to maintain long-term
- **Manageable Scope**: Each phase completable in reasonable time
- **Future Self Friendly**: Documentation helps you remember past decisions
- **Transferable Skills**: Learn patterns that apply across projects

## Project Vision

We envision this workflow enabling solo developers to:

- **Ship more projects to completion** instead of abandoning them
- **Build higher quality software** through systematic approaches  
- **Make better architectural decisions** with AI guidance
- **Maintain projects effectively** over time
- **Scale their development practices** as projects grow

## What We're NOT Building

This is **not**:
- A project management tool (we integrate with existing tools)
- A code generation framework (we use existing AI assistants)
- A one-size-fits-all solution (it's adaptable to different project types)
- A replacement for learning fundamentals (it's a structured approach to applying knowledge)

## Repository Structure

```
claude-workflow/
├── README.md                    # This file - project vision and goals
├── CLAUDE.md                    # Instructions for AI assistants
├── braindump.md                 # Original ideation and requirements
├── research-papers/             # Evidence base for methodology
│   ├── gitlab-product-development-flow.md
│   ├── walking-skeleton-methodology.md
│   ├── gitlab-new-vs-existing-systems.md
│   ├── solo-developer-documentation-strategy.md
│   ├── ai-workflow-documentation-patterns.md
│   └── in-repo-vs-external-documentation.md
├── phase-templates/             # [TO BE BUILT] Structured templates for each phase
├── ai-scripts/                  # [TO BE BUILT] Question frameworks for AI guidance
└── examples/                    # [TO BE BUILT] Real project examples using the workflow
```

## Development Philosophy

We believe that:

1. **Structure enables creativity** - having a framework makes it easier to focus on building
2. **Documentation is an investment** - good docs save more time than they cost
3. **AI amplifies good practices** - AI works best with clear structure and context
4. **Small steps compound** - consistent incremental progress beats sporadic big pushes
5. **One person can build amazing things** - with the right methodology and tools

## Getting Involved

This workflow is being developed in the open. If you're interested in:
- **Using the workflow** - watch for releases and examples
- **Contributing ideas** - review the research papers and suggest improvements  
- **Sharing experiences** - tell us how similar approaches have worked for you

## Current Status

**Phase 1: Research Complete** ✅
- Analyzed enterprise methodologies (GitLab, Walking Skeleton)
- Studied solo developer practices and AI workflow patterns
- Documented evidence base for design decisions

**Phase 2: Design (In Progress)** 🔄
- Creating phase templates and structures
- Designing AI questioning frameworks
- Building reproducible setup processes

**Phase 3: Implementation (Planned)** 📋
- Real project examples and case studies
- Tool integrations and automations
- Community feedback and iteration

---

*This workflow represents our attempt to bring enterprise-level development discipline to solo developers, enhanced by the power of modern AI assistants. We're building the development process we wish we'd had when starting ambitious side projects.*