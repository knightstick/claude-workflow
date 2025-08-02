# Solution Validation Phase Template

*Validate that proposed solutions meet business goals and are technically feasible before building.*

## Phase Overview

**Goal**: Design and validate solutions that effectively address the validated problem while being technically feasible and differentiated from existing options.

**Duration**: 30-60 minutes (time-boxed)

**Prerequisites**: Completed Problem Validation with validated problem statement

**Success Criteria**: 
- Clear solution approach that addresses the validated problem
- Evidence that target users would adopt this solution
- Technical feasibility validated through research and prototyping
- Solution differentiation and competitive advantage identified
- Go/no-go decision based on solution validation evidence

## Research Foundation

Based on **GitLab Product Development Flow research**:
- "Product Designer leads the team in ideating about potential solutions"
- "Determine whether the proposed solution meets business goals and is technically feasible"
- "If the result is to move forward and solve the problem, move to design and solution validation"
- "Validate that the solutions meet users' needs"

Based on **Walking Skeleton Methodology research**:
- Solutions should enable minimal end-to-end implementation
- Technical feasibility must be validated before building
- Architecture choices should support incremental development

## Phase Activities

### 1. Solution Ideation and Design

#### Solution Brainstorming
**AI Prompt**: "Help generate multiple solution approaches for the validated problem."

**Ideation Process**:
- Generate 5-10 different solution approaches
- Include both obvious and creative solutions
- Consider different technology approaches
- Think about different user experience models
- Include solutions with varying complexity levels

**Solution Criteria**:
- Directly addresses the validated problem
- Feasible for solo developer + AI implementation
- Differentiable from existing solutions
- Can be implemented incrementally (Walking Skeleton → MVCs)

#### Solution Specification
**AI Prompt**: "Help specify the most promising solution approach in detail."

**Solution Design Elements**:
- **Core Functionality**: What will the solution actually do?
- **User Experience**: How will users interact with the solution?
- **Technology Approach**: What technical components are needed?
- **Integration Points**: How does it fit into users' existing workflows?
- **Success Metrics**: How will you measure if the solution works?

### 2. Technical Feasibility Assessment

#### Architecture Validation
**AI Prompt**: "Assess the technical feasibility of this solution approach."

**Technical Questions**:
- What are the core technical components required?
- Do you have the skills to implement these components?
- What external services or APIs would be needed?
- What are the potential technical risks or blockers?
- How complex would the initial implementation be?

#### Technology Stack Assessment
**AI Prompt**: "Help evaluate technology choices for implementing this solution."

**Stack Evaluation**:
- **Frontend Requirements**: What user interface needs exist?
- **Backend Requirements**: What server-side logic is needed?
- **Data Storage**: What database or storage requirements exist?
- **Integration Requirements**: What external systems need connection?
- **Deployment Requirements**: How will this be hosted and scaled?

#### Technical Risk Assessment
**AI Prompt**: "Identify the main technical risks and how to validate them quickly."

**Quick Technical Validation**:
- Identify the riskiest technical assumptions
- Plan 15-30 minute research/tests to validate feasibility
- Focus on proving core functionality is possible
- Use existing examples, tutorials, or documentation
- Defer detailed prototyping to Walking Skeleton phase

### 3. User Solution Validation

#### Solution Validation Research Design
**AI Prompt**: "Design research approach to validate this solution with target users."

**Quick Validation Methods** (for solo developers):
- **Concept Validation**: Quick check with 1-2 people or personal experience
- **Competitive Research**: 10-15 minute review of existing solutions
- **Technical Feasibility**: Quick research on implementation approach
- **Value Assessment**: Validate the core value proposition makes sense

#### User Validation Script
**AI Prompt**: "Create interview script to validate solution approach with users."

**Solution Interview Questions**:
1. "Based on our previous conversation about [problem], I'd like to show you a potential solution"
2. "What's your initial reaction to this approach?"
3. "How would this fit into your current workflow?"
4. "What concerns would you have about using something like this?"
5. "How does this compare to [existing solution] that you mentioned?"
6. "What would convince you to try this solution?"
7. "What would make you stop using this solution?"

### 4. Competitive Differentiation Analysis

#### Competitive Solution Analysis
**AI Prompt**: "Analyze how this solution compares to existing alternatives."

**Competitive Assessment**:
- **Direct Competitors**: Solutions that solve the same problem
- **Indirect Competitors**: Alternative approaches users might take
- **Substitute Solutions**: Different ways users might address the need
- **Differentiation Factors**: What makes this solution unique/better
- **Competitive Advantages**: Sustainable advantages over alternatives

#### Value Proposition Development
**AI Prompt**: "Help articulate the unique value proposition of this solution."

**Value Proposition Elements**:
- **Primary Benefit**: Main advantage for users
- **Differentiation**: How it's different from existing solutions
- **Proof Points**: Evidence that supports the value claims
- **Target User Fit**: Why this is especially good for target users
- **Adoption Drivers**: What would motivate users to switch

### 5. Business Model and Viability

#### Solution Viability Assessment
**AI Prompt**: "Assess the business viability of this solution approach."

**Viability Questions**:
- How would this solution be monetized (if commercial)?
- What would be the ongoing maintenance requirements?
- How would you reach and acquire users?
- What would be the development and operational costs?
- Is this viable as a solo developer project?

#### Resource Requirements Analysis
**AI Prompt**: "Analyze the resources required to build and maintain this solution."

**Resource Assessment**:
- **Development Time**: Realistic estimate for initial version
- **Ongoing Maintenance**: Time required to keep solution running
- **Technical Skills**: Any skills you'd need to learn
- **External Dependencies**: Services, APIs, or tools required
- **Support Requirements**: User support and documentation needs

### 6. Solution Validation Testing

#### Validation Execution
**AI Prompt**: "Guide execution of solution validation research with target users."

**Validation Process**:
1. **Recruit Participants**: Same users from problem validation ideally
2. **Prepare Materials**: Solution concepts, prototypes, or demos
3. **Conduct Sessions**: Interview users about solution approach
4. **Gather Feedback**: Document reactions, concerns, and suggestions
5. **Test Assumptions**: Validate key assumptions about user adoption

#### Validation Analysis
**AI Prompt**: "Analyze validation results to determine solution viability."

**Analysis Framework**:
- **User Reaction**: Do users understand and appreciate the solution?
- **Adoption Intent**: Would users actually use this solution?
- **Workflow Fit**: Does it integrate well into user processes?
- **Switching Likelihood**: Would users switch from current solutions?
- **Value Perception**: Do users see sufficient value to adopt?

## Human Validation Checkpoint

### Phase Completion Assessment

#### Objective Checklist
- [ ] Multiple solution approaches have been considered
- [ ] Preferred solution has been specified in detail
- [ ] Technical feasibility has been validated
- [ ] User validation research has been conducted
- [ ] Competitive differentiation has been analyzed
- [ ] Business viability has been assessed

#### Solution Quality Assessment
**For the proposed solution, evaluate**:
- **Problem Fit**: Does this actually solve the validated problem?
- **User Desirability**: Do users want this solution?
- **Technical Feasibility**: Can you realistically build this?
- **Business Viability**: Is this sustainable as a project?
- **Competitive Position**: Does this offer meaningful differentiation?

#### Validation Evidence Assessment
- **User Feedback Quality**: How thorough was user validation?
- **Technical Validation**: How confident are you in feasibility?
- **Market Position**: How well does this differentiate?
- **Resource Reality**: Do you have capacity to build this?

### Decision Framework

#### Go/No-Go Questions
1. **Do users clearly want this solution approach?**
   - YES → Continue to question 2
   - NO → Iterate on solution or return to problem validation

2. **Is this solution technically feasible for you to build?**
   - YES → Continue to question 3
   - NO → Simplify solution or pivot to different approach

3. **Does this solution offer meaningful differentiation from existing options?**
   - YES → Continue to question 4
   - NO → Find unique angle or reconsider problem/market

4. **Do you have the resources and commitment to build and maintain this?**
   - YES → **✅ PROCEED** to Walking Skeleton phase
   - NO → Adjust scope or timeline, or pause project

#### Warning Signs
🚨 **Red Flags** that suggest solution validation failed:
- Users don't get excited about the solution concept
- Technical complexity is much higher than expected
- Solution is very similar to existing options
- Resource requirements exceed available capacity
- Users identify major workflow or adoption barriers

### Decision Documentation

```markdown
## Solution Validation Decision - [Date]

**Validated Problem**: [Brief restatement of the problem being solved]

**Proposed Solution**: [Clear description of the solution approach]

**Decision**: [PROCEED/ITERATE/PIVOT/STOP]

**Technical Approach**:
- Core technology stack: [Technologies to be used]
- Architecture approach: [High-level system design]
- Key technical risks: [Main technical uncertainties]
- Feasibility confidence: [High/Medium/Low]

**User Validation Results**:
- Participants: [Number and type of users validated with]
- Key feedback: [Main themes from user validation]
- Adoption intent: [User willingness to use this solution]
- Workflow integration: [How well it fits user processes]

**Competitive Position**:
- Primary differentiation: [What makes this unique]
- Competitive advantages: [Why users would choose this]
- Market positioning: [How this fits in the market]

**Resource Assessment**:
- Development timeline: [Realistic estimate for initial version]
- Required skills: [Any new skills needed]
- Ongoing maintenance: [Time commitment for maintenance]
- External dependencies: [Services or tools required]

**Key Validation Insights**:
- What users liked: [Positive feedback themes]
- User concerns: [Worries or objections raised]
- Surprising learnings: [Unexpected insights from validation]
- Assumption changes: [How validation changed your assumptions]

**Next Phase Planning**:
- Walking Skeleton scope: [Minimal implementation to start with]
- Success metrics: [How you'll measure Walking Skeleton success]
- Key technical risks to validate first: [Priorities for initial implementation]

**Future Self Notes**:
- User quotes that validate the solution approach
- Technical resources or examples that will be helpful
- Key design decisions and their rationale
- Contact information for users willing to test early versions
```

## Next Phase Handoff

### If PROCEEDING to Walking Skeleton

**Handoff Package**:
- Validated solution specification
- Technical architecture and feasibility assessment
- User validation insights and feedback
- Competitive positioning and differentiation
- Resource requirements and timeline estimates

**Walking Skeleton Planning**:
- Focus on core technical risks first
- Implement minimal version that proves solution works
- Include user feedback mechanisms in initial implementation
- Plan for iterative validation and improvement

### If ITERATING on Solution

**Iteration Focus Areas**:
- Address user feedback and concerns
- Simplify technical approach if feasibility is questionable
- Strengthen differentiation if competitive position is weak
- Adjust resource requirements if scope is too large

### If PIVOTING

**Pivot Options**:
- **Solution Pivot**: Different solution for same validated problem
- **Technology Pivot**: Same solution with different technical approach
- **Market Pivot**: Same solution for different user group
- **Problem Pivot**: Return to problem validation for different problem

---

*This template implements GitLab's solution validation methodology adapted for solo developers, emphasizing user validation and technical feasibility before committing to implementation.*