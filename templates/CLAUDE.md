# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

*This project uses the Claude Workflow methodology - a phased development approach for solo developers with AI assistance.*

## Project Setup

**Current Phase**: [UPDATE: Problem Validation / Walking Skeleton / MVC-1 / etc.]

**Project Type**: [UPDATE: Web App / API Service / CLI Tool / Mobile App / etc.]

**Tech Stack**: [UPDATE: React+Node / Python+FastAPI / Go CLI / etc.]

## Claude Workflow Instructions

### Phase-Based Development

This project follows a structured workflow with human validation at the end of each phase:

1. **Problem Validation** - Validate the problem before building solutions
2. **Walking Skeleton** - Minimal end-to-end implementation and deployment  
3. **MVC Phases** - Incremental feature development with validation

### Current Phase Guidance

#### If Problem Validation Phase:
- Help validate that this project solves a real problem for real users
- Ask systematic questions about problem significance and evidence
- Reference `onboarding/setup-script.md` for structured questioning
- Goal: Clear problem statement and evidence before building

#### If Walking Skeleton Phase:
- Focus on minimal end-to-end functionality that proves the architecture
- Help identify core architectural components and simplest integration
- Reference `ai-scripts/walking-skeleton-questions.md` for systematic guidance
- Goal: Deployable system with one working feature

#### If MVC Phase:
- Focus on one small, valuable change at a time
- Help scope features to minimal viable changes
- Maintain existing architecture and deployment pipeline
- Goal: Add meaningful value without breaking existing functionality

### Development Principles

- **Research-Driven**: Reference methodology research when making decisions
- **Minimal Viable Changes**: Small, incremental improvements over large features
- **Deploy Early and Often**: Keep the system deployable throughout development
- **Human Validation**: Prepare validation materials at the end of each phase
- **Documentation**: Maintain just enough documentation for future development

### AI Assistant Role

- **Ask systematic questions** to guide decision-making in each phase
- **Suggest minimal implementations** that prove concepts quickly
- **Help resist scope creep** by focusing on current phase goals
- **Prepare validation materials** for human review at phase end
- **Document key decisions** and architectural choices

### Phase Completion

At the end of each phase:
1. **Prepare validation package**: Summarize accomplishments and artifacts
2. **Identify remaining risks**: What could go wrong in next phase?
3. **Document decisions**: Key choices made and alternatives considered
4. **Human validation required**: Use `human-validation-framework.md`

## Project-Specific Context

**Problem Being Solved**: [UPDATE: Describe the core problem this project addresses]

**Target Users**: [UPDATE: Who has this problem and will use this solution]

**Success Criteria**: [UPDATE: How will you know this project is successful]

**Key Constraints**: [UPDATE: Time, technology, scope, or other limitations]

## Architecture Decisions

*Document key architectural choices as they're made:*

**[Date] - Technology Stack Choice**
- Decision: [e.g., React + Node.js + PostgreSQL]
- Rationale: [Why this choice over alternatives]
- Trade-offs: [What this choice optimizes for vs. what it sacrifices]

**[Date] - Deployment Strategy**
- Decision: [e.g., Vercel for frontend, Railway for backend]
- Rationale: [Why this approach]
- Trade-offs: [Considerations and limitations]

## Current Status

**Last Updated**: [UPDATE DATE]

**Phase Progress**:
- [ ] [Current phase objectives]
- [ ] [Key milestones or deliverables]
- [ ] [Integration or deployment goals]

**Next Steps**:
- [Immediate priorities for current phase]
- [Potential blockers to address]
- [Success criteria for phase completion]

**Notes for Future Self**:
- [Important context that might be forgotten]
- [Decisions that might seem unclear later]
- [Resources or references that were helpful]

---

*This project follows the Claude Workflow methodology. For methodology details, see: https://github.com/[your-username]/claude-workflow*