# Core Design Principles

## Human-in-the-Loop Phase Validation

**CRITICAL PRINCIPLE**: Every phase ends with human validation and go/no-go decision.

### Why This Matters

Based on our research:
- **GitLab Product Development Flow**: Clear phase gates prevent building wrong things
- **Solo Developer Strategy**: Human maintains long-term project vision and priorities  
- **AI Workflow Patterns**: AI augments human decision-making, doesn't replace it
- **Walking Skeleton Methodology**: Human validates architectural decisions before proceeding

### Implementation Requirements

Every phase template must include:

1. **Clear Success Criteria**: Specific, measurable outcomes that define phase completion
2. **Validation Checklist**: Step-by-step verification process for human review
3. **Decision Framework**: Structured approach for go/no-go/pivot decisions
4. **Risk Assessment**: Common failure modes and red flags to watch for
5. **Artifact Review**: Human validation of AI-generated deliverables

### Human Validation Framework

#### What the Human Validates
- **Strategic Alignment**: Does this still solve the right problem?
- **Quality Assessment**: Are the deliverables good enough to build on?
- **Resource Reality Check**: Can I realistically continue given time/energy constraints?
- **Technical Feasibility**: Do the architectural decisions make sense?
- **Value Validation**: Is this creating meaningful progress toward the goal?

#### Decision Options at Each Phase Gate
- **✅ PROCEED**: Phase completed successfully, move to next phase
- **🔄 ITERATE**: Phase needs more work, continue with adjustments
- **🔀 PIVOT**: Change direction based on learnings from this phase
- **⏸️ PAUSE**: Put project on hold (document current state for future resume)
- **❌ STOP**: Abandon project (document learnings for future projects)

#### Equipping the Human for Good Decisions

**Validation Tools to Provide:**
1. **Phase Completion Checklist** - Objective criteria for phase success
2. **Quality Assessment Framework** - How to evaluate AI-generated artifacts
3. **Decision Tree** - Structured questions to guide go/no-go decisions
4. **Risk Indicators** - Warning signs that suggest iteration or pivot
5. **Documentation Templates** - Capture decisions and rationale for future self

**Information the Human Needs:**
- Summary of what was accomplished in this phase
- Key decisions made and alternatives considered  
- Artifacts produced and their quality level
- Remaining uncertainties and risks
- Resource investment to date
- Estimated effort for next phase

### Research Foundation

This principle is supported by:
- **GitLab research**: "If we don't have confidence in the MVC or what success looks like, we should continue validation cycles"
- **Solo developer research**: "Documentation should provide context for future self decision-making"
- **AI workflow research**: "AI balances asking the right questions with forward motion"
- **Walking Skeleton research**: "Early validation of architectural assumptions prevents expensive changes later"

---

*This principle ensures that AI acceleration doesn't compromise human strategic oversight and long-term project success.*