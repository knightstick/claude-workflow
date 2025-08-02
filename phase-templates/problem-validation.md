# Problem Validation Phase Template

*Validate that this project solves a real problem for real users before investing in solutions.*

## Phase Overview

**Goal**: Establish and validate customer problems before moving to solution development.

**Duration**: 30-60 minutes (time-boxed)

**Prerequisites**: Initial project idea or opportunity identified

**Success Criteria**: 
- Clear problem statement in customer language
- Evidence that the problem exists and is significant
- Validation that target users actually have this problem
- Understanding of problem impact and urgency
- Decision to proceed, pivot, or stop based on evidence

## Research Foundation

Based on **GitLab Product Development Flow research**:
- "Good product development starts with a well understood and clearly articulated customer problem"
- "Validation opportunities should be captured in customer problem language"
- "Avoid jumping ahead to feature/solution language"
- "If we don't have confidence in the problem, continue validation cycles"

Based on **Solo Developer Documentation Strategy research**:
- Focus on decisions that save future time and effort
- Document evidence and reasoning for future self
- Keep validation lightweight but systematic

## Phase Activities

### 1. Problem Discovery and Definition

#### Problem Statement Development
**AI Prompt**: "Help me articulate the core problem this project should solve."

**Key Questions**:
- What specific problem are you trying to solve?
- Who experiences this problem? (Be specific about user groups)
- When and how often does this problem occur?
- What are people doing now to solve this problem (if anything)?
- Why is this problem worth solving?

**Output**: Clear problem statement that:
- Describes the problem in user/customer language
- Avoids solution or feature descriptions
- Identifies specific user groups affected
- Explains the current impact of the problem

#### User Group Identification
**AI Prompt**: "Help identify and validate the specific users who have this problem."

**User Analysis**:
- Who are the primary users affected by this problem?
- What are their current workflows or processes?
- How do they currently handle this problem?
- What would motivate them to adopt a new solution?
- How would you reach these users for validation?

### 2. Problem Evidence Gathering

#### Evidence Collection
**AI Prompt**: "Help identify ways to gather evidence that this problem actually exists."

**Evidence Sources**:
- **Personal Experience**: Your own encounters with this problem
- **User Interviews**: Direct conversations with potential users
- **Observation**: Watching people encounter this problem
- **Data Analysis**: Usage patterns, support tickets, forum discussions
- **Market Research**: Existing solutions, competitor analysis
- **Expert Input**: Industry professionals, domain experts

**Validation Activities** (time-boxed for solo developers):
- Conduct 2-3 quick user conversations or use personal experience
- Quick research of existing solutions (15-30 minutes)
- Analyze current problem-solving approaches
- Use available data or simple online research

#### Problem Significance Assessment
**AI Prompt**: "Help assess whether this problem is significant enough to build a solution."

**Significance Criteria**:
- **Frequency**: How often do users encounter this problem?
- **Impact**: How much pain/cost does this problem cause?
- **Urgency**: How badly do users need this solved?
- **Reach**: How many potential users are affected?
- **Willingness to Pay**: Would users pay for a solution?

### 3. Market and Competitive Analysis

#### Existing Solutions Research
**AI Prompt**: "Help research what solutions already exist for this problem."

**Competitive Landscape**:
- What tools/services currently address this problem?
- How well do existing solutions work?
- What are the gaps or limitations in current solutions?
- Why might users be dissatisfied with existing options?
- What would differentiate a new solution?

#### Market Opportunity Assessment
**AI Prompt**: "Help assess the market opportunity for solving this problem."

**Market Questions**:
- Is this market growing, stable, or declining?
- Are there recent changes that make this problem more important?
- What trends might affect the relevance of this problem?
- Is there room for a new solution in this space?

### 4. Problem Validation Testing

#### Validation Methodology
**AI Prompt**: "Design a systematic approach to validate this problem with real users."

**Validation Approaches**:
- **Problem Interviews**: Focus on understanding the problem, not pitching solutions
- **Observation Studies**: Watch users encounter the problem naturally
- **Survey Validation**: Quantify problem frequency and impact
- **Expert Validation**: Get input from domain experts
- **Market Validation**: Analyze existing solution adoption and satisfaction

#### Validation Script Template
**Problem Interview Questions**:
1. "Tell me about the last time you encountered [problem area]"
2. "What was frustrating about that experience?"
3. "How do you currently handle [specific situation]?"
4. "What would need to change for that to work better?"
5. "How much time/money does this problem cost you?"
6. "If there was a solution to this, what would success look like?"

### 5. Problem Validation Analysis

#### Evidence Synthesis
**AI Prompt**: "Help analyze and synthesize the validation evidence collected."

**Analysis Framework**:
- **Problem Confirmation**: Does evidence confirm the problem exists?
- **User Validation**: Do target users actually experience this problem?
- **Significance Validation**: Is the problem important enough to solve?
- **Market Validation**: Is there opportunity for a new solution?
- **Timing Validation**: Is now the right time to solve this problem?

#### Risk Assessment
**AI Prompt**: "Identify risks and assumptions that still need validation."

**Risk Categories**:
- **Problem Risk**: Is this a real problem or just a perceived one?
- **Market Risk**: Are enough people affected to make this viable?
- **Solution Risk**: Can this problem actually be solved effectively?
- **Timing Risk**: Are there external factors that affect timing?
- **Resource Risk**: Do you have capability to solve this problem?

## Human Validation Checkpoint

### Phase Completion Assessment

#### Objective Checklist
- [ ] Problem statement is clear and specific
- [ ] Target users have been identified and validated
- [ ] Evidence has been gathered from multiple sources
- [ ] Problem significance has been assessed
- [ ] Market opportunity has been evaluated
- [ ] Competitive landscape has been researched

#### Evidence Quality Assessment
**For each type of evidence, evaluate**:
- **User Interviews**: How many conducted? Quality of insights?
- **Market Research**: Depth and reliability of sources?
- **Competitive Analysis**: Comprehensiveness of solution review?
- **Quantitative Data**: Sample size and reliability?

#### Problem Strength Assessment
- **Problem Clarity**: Can you explain the problem in one sentence?
- **User Pain**: Do users clearly express frustration with this problem?
- **Problem Frequency**: Do users encounter this regularly?
- **Current Solutions**: Are existing solutions inadequate?
- **User Motivation**: Would users actively seek a better solution?

### Decision Framework

#### Go/No-Go Questions
1. **Is there clear evidence that this problem exists for real users?**
   - YES → Continue to question 2
   - NO → Gather more evidence or redefine problem

2. **Do enough users have this problem to make a solution worthwhile?**
   - YES → Continue to question 3
   - NO → Look for a broader or different problem

3. **Is this problem significant enough that users would adopt a new solution?**
   - YES → Continue to question 4
   - NO → Validate problem importance or find more critical problems

4. **Is there a realistic opportunity to build a better solution than exists today?**
   - YES → **✅ PROCEED** to Solution Validation phase
   - NO → Reconsider approach or find different problem

#### Warning Signs
🚨 **Red Flags** that suggest problem validation failed:
- Users don't express strong frustration about the problem
- Existing solutions are "good enough" for most users
- Only you seem to care about this problem
- Problem is too niche or affects very few people
- Users have workarounds they're satisfied with

### Decision Documentation

```markdown
## Problem Validation Decision - [Date]

**Problem Statement**: [One sentence description of the validated problem]

**Decision**: [PROCEED/PIVOT/STOP]

**Target Users**: [Specific user groups validated]

**Evidence Summary**:
- User interviews: [Number conducted and key insights]
- Market research: [Key findings about problem prevalence]
- Competitive analysis: [Gaps in existing solutions]
- Quantitative data: [Any metrics gathered]

**Problem Significance**:
- Frequency: [How often users encounter this]
- Impact: [Cost/pain this problem causes]
- Urgency: [How badly users need this solved]
- Market size: [Rough estimate of affected users]

**Key Validation Insights**:
- What users said about the problem: [Direct quotes or themes]
- How users currently solve this: [Existing approaches]
- Why current solutions don't work: [Gaps identified]
- What would make users switch: [Switching criteria]

**Assumptions Validated**:
- [List assumptions that were confirmed]

**Assumptions Invalidated**:
- [List assumptions that were disproven]

**Remaining Risks**:
- [Key uncertainties or risks still present]

**Next Phase Planning**:
- If proceeding: Focus areas for solution validation
- Key constraints to consider in solution design
- Success criteria for solution validation phase

**Future Self Notes**:
- User quotes that capture the problem well
- Sources for recruiting users for solution validation
- Important context about user workflows or constraints
```

## Next Phase Handoff

### If PROCEEDING to Solution Validation

**Handoff Package**:
- Validated problem statement
- Target user profiles and recruitment sources  
- Evidence documentation and user insights
- Competitive landscape analysis
- Market opportunity assessment

**Success Criteria for Solution Validation**:
- Design solutions that address the validated problem
- Validate solutions with the same user groups
- Ensure solutions are feasible and differentiated
- Confirm users would adopt the proposed solution

### If PIVOTING

**Pivot Options**:
- **User Pivot**: Same problem, different user group
- **Problem Pivot**: Same user group, different problem
- **Solution Pivot**: Same problem, completely different approach
- **Market Pivot**: Same solution, different market context

### If STOPPING

**Documentation Requirements**:
- Clearly document why problem validation failed
- Capture insights for future reference
- Note any valuable research or user connections made
- Consider if any learnings apply to other problem areas

---

*This template implements GitLab's problem validation methodology adapted for solo developers, emphasizing systematic evidence gathering and validation before proceeding to solution development.*