# Claude Workflow - Phased Development for Solo Developers + AI

A complete, research-backed workflow system for building ambitious software projects as a solo developer with AI assistance.

## Overview

This repository provides a **phased development workflow** specifically designed for solo developers working with AI coding assistants like Claude Code. Based on GitLab's Product Development Flow and adapted for individual developers, it delivers:

1. **Systematic project progression** through validated phases
2. **AI-guided decision-making** with structured questioning frameworks  
3. **Proven enterprise methodologies** scaled for solo development
4. **Complete template system** for immediate project application
5. **Human validation gates** to maintain strategic oversight

## The Complete Workflow System

**5-Phase Development Process** (adapted from GitLab's Product Development Flow):

**Validation Track:**
1. **Problem Validation** (30-60 min) - Validate the problem before building solutions
2. **Solution Validation** (30-60 min) - Validate solution approach and technical feasibility

**Build Track:**
3. **Walking Skeleton** (2-4 hours) - Minimal end-to-end implementation and deployment
4. **Incremental Development** (1-2 hours per cycle) - Build features using MVC principles
5. **Track Phase** (30-60 min) - Measure outcomes and validate success

**Throughout:** Human validation at the end of every phase ensures strategic oversight.

## Getting Started with a New Project

### Quick Setup

1. **Create your project directory and copy workflow files**:
   ```bash
   mkdir my-new-project && cd my-new-project
   
   # Copy all workflow files
   cp /path/to/claude-workflow/templates/CLAUDE.md ./
   cp /path/to/claude-workflow/human-validation-framework.md ./
   cp -r /path/to/claude-workflow/phase-templates ./
   cp -r /path/to/claude-workflow/ai-scripts ./
   cp -r /path/to/claude-workflow/templates ./
   
   mkdir decisions
   touch README.md
   ```

2. **Customize CLAUDE.md** with your project details (tech stack, problem statement, etc.)

3. **Start with Problem Validation** using the phase template and AI assistance

4. **Progress through each phase** with human validation at each gate

### What You Get

**Complete Phase Templates:**
- Problem Validation, Solution Validation, Walking Skeleton, Incremental Development, Track Phase
- AI-guided questioning scripts for systematic decision-making
- Human validation checkpoints and decision frameworks

**Project Management:**
- Phase tracking templates
- Progress logging system  
- Decision record templates
- AI assistant instructions (CLAUDE.md)

**Research Foundation:**
- 6 research papers validating the methodology
- Lessons learned from building this system using itself
- Enterprise methodology adaptations for solo developers

## Why This Works

**Enterprise Methodology, Solo Scale**: Based on GitLab's proven Product Development Flow, adapted for individual developers working with AI assistants.

**Validation Before Building**: Systematic problem and solution validation prevents building the wrong thing.

**AI-Human Collaboration**: Structured AI questioning combined with human validation gates leverages the strengths of both.

**Incremental Progress**: MVC (Minimal Viable Change) ideology ensures consistent, valuable progress without overwhelming scope.

**Time-Bounded Phases**: Each phase has realistic time limits (30 minutes to 4 hours) designed for solo developer capacity.

## Repository Structure

```
claude-workflow/
├── README.md                           # Project overview and setup guide
├── CLAUDE.md                          # AI assistant instructions for this repo
├── lessons-learned.md                 # Insights from dogfooding the workflow
├── human-validation-framework.md      # Decision frameworks for phase gates
├── phase-templates/                   # Complete phase templates
│   ├── problem-validation.md          # 30-60 min problem validation
│   ├── solution-validation.md         # 30-60 min solution validation  
│   ├── walking-skeleton.md            # 2-4 hour minimal implementation
│   ├── mvc-phase.md                   # 1-2 hour incremental development
│   └── track-phase.md                 # 30-60 min outcome measurement
├── ai-scripts/                        # AI questioning frameworks
│   └── walking-skeleton-questions.md  # Systematic AI guidance scripts
├── templates/                         # Project templates
│   ├── CLAUDE.md                      # AI instructions template for new projects
│   ├── phase-tracking.md              # Progress tracking template
│   ├── progress-log.md                # Daily/weekly log template
│   └── decision-record.md             # Decision documentation template
└── research-papers/                   # Research foundation (6 papers)
    ├── gitlab-product-development-flow.md
    ├── walking-skeleton-methodology.md
    └── [4 more research papers...]
```

## Status

**✅ Complete and Ready for Use**

This workflow system has been successfully built using itself (dogfooded) and is ready for application to real projects. All phase templates, AI scripts, and validation frameworks are complete and tested.

---

*A systematic approach to solo development that combines enterprise methodology with AI assistance, enabling ambitious projects to ship successfully.*