# Research Paper: GitLab Product Development Flow

## Overview

GitLab's Product Development Flow is described as a "flexible yet concise product development framework for developing products that customers love and value." It emphasizes cross-functional collaboration and validation-driven development.

## Core Principle

**Foundation**: "Good product development starts with a well understood and clearly articulated customer problem."

The methodology separates validation from building to ensure teams solve the right problems before investing in solutions.

## Phase Structure

### Two-Track System

**Validation Track**: Problem and solution validation (1-2 months ahead of build)
**Build Track**: Implementation and delivery

### Detailed Phases

#### 1. Problem Validation Phase

**Goal**: Establish and validate customer problems before solutioning

**Key Activities**:
- Create issues using "Problem Validation" template
- Describe problems in customer language (not solution language)
- Apply RICE formula for prioritization
- Validate through multiple sensing mechanisms:
  - Customer feedback
  - Internal stakeholder input
  - Product usage insights
  - Support tickets
  - Win/loss data

**Decision Criteria**: Problem is "well understood and clearly articulated"

**Labels**: ~"workflow::problem validation"

#### 2. Solution Validation Phase

**Goal**: Validate that proposed solutions meet business goals and are technically feasible

**Key Activities**:
- Product Designer leads ideation
- Engage PM and Engineers for feasibility assessment
- Create solution artifacts (API docs, workflow diagrams)
- Validate technical feasibility for both UI and non-UI features

**Decision Criteria**: Solution meets user needs and business objectives

**Handoff**: Move to Build Track when solution is validated

#### 3. Build Track Phases

**Goal**: Break down opportunities into well-defined implementation issues

**Key Participants**: PM, UX, SET, Engineering Managers

**Activities**:
- Technical feasibility validation during design phase
- Cross-functional artifact creation and review
- Shared understanding development

#### 4. Track Phase

**Goal**: Measure outcomes and validate success

**Success Criteria**: 
- Improve Product KPIs and/or Engineering KPIs
- Deliver performant MVCs (Minimal Viable Changes)

**Failure Protocol**: If KPIs not improved, abandon and restart validation cycle

## Cross-Functional Collaboration Principles

- PM and UX Researcher execute research studies together
- Engineers shadow research studies when beneficial
- Continuous cross-functional contribution (#everyonecancontribute)
- Avoid phase siloing

## Key Questions Framework

While specific question sets weren't fully detailed in available sources, the methodology implies these meta-questions per phase:

**Problem Validation**:
- Is this a real customer problem?
- How do we know this problem exists?
- What evidence supports the problem significance?

**Solution Validation**:
- Does this solution address the validated problem?
- Is this solution technically feasible?
- Will users adopt this solution?

**Build Track**:
- How do we break this into implementable pieces?
- What are the technical constraints?
- How do we maintain quality during implementation?

**Track Phase**:
- Did we achieve our intended outcomes?
- What metrics demonstrate success/failure?
- Should we continue, pivot, or abandon?

## Research Gaps

Further investigation needed for:
1. Detailed question scripts for each phase
2. Specific research methodologies used in validation
3. Decision criteria and gates between phases
4. Success metrics and measurement frameworks
5. Tools and templates used in practice

## Applicability to Single-Developer + AI Workflow

**Scalable Elements**:
- Problem-first approach
- Validation before building
- Phase-based artifact creation
- Outcome measurement

**Adaptation Needed**:
- Simplify cross-functional coordination
- AI-assisted questioning frameworks
- Streamlined documentation
- Faster iteration cycles suitable for solo development

## Sources

- GitLab Handbook Product Development Flow sections
- GitLab UX Research documentation references
- Product Development Flow Working Group outcomes
- Web search compilation from multiple GitLab handbook pages

*Note: Some GitLab handbook pages were inaccessible during research. Future updates should include direct access to problem validation methods, solution validation techniques, and detailed phase templates.*