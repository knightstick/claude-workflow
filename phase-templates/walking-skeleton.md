# Walking Skeleton Phase Template

*Minimal end-to-end implementation that links together all main architectural components.*

## Phase Overview

**Goal**: Create the smallest possible working system that exercises the full technology stack and can be deployed to production.

**Duration**: 2-4 hours (time-boxed)

**Success Criteria**: 
- Basic application structure exists and runs
- All major architectural components are connected
- System can be deployed to target environment
- One simple end-to-end user journey works
- Development and deployment processes are established

## Research Foundation

Based on **Walking Skeleton methodology research**:
- "A tiny implementation that performs a small end-to-end function"
- "Link together all main architectural components"
- "Technical proof of concept that validates architecture"
- "Deploy early, iterate incrementally"

## Phase Activities

### 1. Architecture Planning

#### Core Components Identification
**AI Prompt**: "Based on the project requirements, help identify the core architectural components needed for this system."

**Key Questions**:
- What are the main architectural layers? (Frontend, Backend, Database, etc.)
- What external services or APIs will be integrated?
- What's the deployment target and hosting requirements?
- What are the critical technical constraints or requirements?

**Deliverable**: Architecture diagram showing component connections

#### Technology Stack Validation
**AI Prompt**: "Validate the chosen technology stack for feasibility and integration."

**Validation Checklist**:
- [ ] All technologies are compatible with each other
- [ ] Developer has sufficient knowledge or learning resources available
- [ ] Deployment platform supports chosen stack
- [ ] No major technical blockers identified

### 2. Minimal Implementation

#### Core Feature Definition
**AI Prompt**: "Help define the minimal feature that exercises the full stack."

**Feature Criteria**:
- Exercises frontend → backend → database → response flow
- Represents core value proposition in simplest form
- Can be completed within time box
- Provides foundation for future features

**Examples by Project Type**:
- **Web App**: User registration + simple dashboard
- **API Service**: Single endpoint with database persistence
- **CLI Tool**: Basic command with file/config operations
- **Mobile App**: Single screen with data fetch/display

#### Implementation Tasks
**AI Prompt**: "Break down the minimal feature into specific implementation tasks."

**Task Categories**:
1. **Development Environment Setup**
   - Local development configuration
   - Dependency management
   - Code organization structure

2. **Core Infrastructure**
   - Database setup and basic schema
   - Authentication/security basics
   - Error handling framework

3. **Basic Functionality**
   - Minimal UI/interface
   - Core business logic
   - Data persistence

4. **Integration**
   - Component connection and communication
   - Basic testing setup
   - Configuration management

### 3. Deployment Pipeline

#### Environment Setup
**AI Prompt**: "Guide setup of deployment pipeline for the chosen platform."

**Deployment Requirements**:
- [ ] Production environment accessible
- [ ] Automated deployment process
- [ ] Environment configuration management
- [ ] Basic monitoring/logging setup

#### Deployment Validation
**Test Criteria**:
- [ ] Application builds successfully
- [ ] Deployment process completes without errors
- [ ] Application is accessible at target URL/environment
- [ ] Core functionality works in production environment

### 4. Documentation

#### Decision Documentation
**AI Prompt**: "Help document key architectural and technical decisions made during this phase."

**Required Documentation**:
- **README.md**: Setup and deployment instructions
- **ARCHITECTURE.md**: System overview and component relationships  
- **DECISIONS.md**: Key choices made and rationale
- **SETUP.md**: Development environment configuration

#### Knowledge Capture
- Document any non-obvious setup steps
- Record troubleshooting solutions discovered
- Note dependencies and version requirements
- Capture deployment configuration details

## Human Validation Checkpoint

### Phase Completion Assessment

#### Objective Checklist
- [ ] Minimal feature is implemented and working
- [ ] All architectural components are connected
- [ ] Application can be deployed to production
- [ ] Development workflow is established
- [ ] Basic documentation exists

#### Quality Assessment
**For each deliverable, evaluate**:
- **Code Quality**: Is it maintainable and well-structured?
- **Architecture**: Does it support planned future development?
- **Documentation**: Is it sufficient for future development?
- **Deployment**: Is the process reliable and repeatable?

#### Strategic Review
- **Problem Alignment**: Does this foundation support solving the core problem?
- **Technical Feasibility**: Are there any major technical concerns?
- **Resource Reality**: How much effort was required vs. estimated?
- **Future Viability**: Can this architecture scale with planned features?

### Decision Framework

#### Go/No-Go Questions
1. **Is the basic system working end-to-end?**
   - YES → Continue to question 2
   - NO → Identify blockers and iterate

2. **Does the architecture feel solid for future development?**
   - YES → Continue to question 3
   - NO → Consider architectural changes before proceeding

3. **Is the deployment process reliable?**
   - YES → Continue to question 4
   - NO → Fix deployment issues before adding features

4. **Do I have confidence to build features on this foundation?**
   - YES → **✅ PROCEED** to MVC phases
   - NO → Identify what needs improvement

#### Warning Signs
🚨 **Red Flags** that suggest iteration needed:
- Deployment process is unreliable or overly complex
- Core technology choices causing major friction
- Architecture feels fragile or hard to modify
- Development workflow is painful or slow

### Decision Documentation

```markdown
## Walking Skeleton Phase Validation - [Date]

**Decision**: [PROCEED/ITERATE/PIVOT/PAUSE/STOP]

**What Was Accomplished**:
- [List major deliverables and achievements]

**Architecture Decisions**:
- [Key technical choices and rationale]

**Quality Assessment**:
- Code Quality: [Rating and notes]
- Architecture: [Assessment of foundation strength]
- Documentation: [Completeness evaluation]
- Deployment: [Reliability assessment]

**Key Learnings**:
- [What worked well]
- [What was challenging]
- [What would be done differently]

**Next Phase Planning**:
- Success criteria for first MVC phase
- Priority features to implement
- Potential risks to monitor

**Future Self Notes**:
- [Important context for later development]
- [Non-obvious decisions that might be questioned]
```

## Next Phase Handoff

### If PROCEEDING to MVC Phases

**Handoff Package**:
- Working deployed application
- Development environment setup
- Architecture documentation
- First MVC feature prioritized and scoped

**Success Criteria for Next Phase**:
- Add one meaningful feature using established architecture
- Maintain deployment pipeline stability
- Improve documentation based on learnings

### If ITERATING on Walking Skeleton

**Iteration Focus Areas**:
- Architectural improvements
- Deployment pipeline fixes
- Development workflow optimization
- Documentation gaps

---

*This template implements Walking Skeleton methodology with human validation gates, based on research from Alistair Cockburn's methodology, GitLab Product Development Flow, and solo developer best practices.*