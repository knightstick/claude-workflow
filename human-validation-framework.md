# Human Validation Framework

*Tools and templates to equip humans for effective end-of-phase validation decisions.*

## Phase Validation Template

**Use this template at the end of every phase to make informed go/no-go decisions.**

### Step 1: Phase Completion Assessment

#### Objective Checklist
- [ ] All phase deliverables are complete
- [ ] Success criteria from phase start have been met
- [ ] Key questions identified at phase start have been answered
- [ ] Documentation is sufficient for next phase or future reference
- [ ] Any blockers or risks have been identified and addressed

#### Deliverable Quality Check
For each major deliverable produced this phase:
- **What was created?**
- **What's the quality level?** (Draft/Good/Production-ready)
- **What would need to change to improve it?**
- **Is it good enough to build the next phase on?**

### Step 2: Strategic Alignment Review

#### Problem-Solution Fit
- **Is this still solving the right problem?**
- **Has the problem changed or evolved during this phase?**
- **Do the solutions developed still make sense?**
- **What have we learned that changes our approach?**

#### Resource Reality Check
- **How much time/energy was invested in this phase?**
- **How does that compare to initial estimates?**
- **What's the estimated effort for the next phase?**
- **Do I realistically have capacity to continue?**

### Step 3: Decision Framework

#### Go/No-Go Decision Tree

**Ask these questions in order:**

1. **Are the phase objectives clearly met?**
   - YES → Continue to question 2
   - NO → Should I iterate on this phase or move forward anyway?

2. **Am I confident the next phase will build successfully on this foundation?**
   - YES → Continue to question 3  
   - NO → What needs to be fixed before proceeding?

3. **Do I still believe this project is worth pursuing?**
   - YES → Continue to question 4
   - NO → Should I pivot the project or pause/stop?

4. **Do I have the resources (time/energy/skills) for the next phase?**
   - YES → **✅ PROCEED** to next phase
   - NO → Should I pause until I have resources, or stop now?

#### Decision Options

**✅ PROCEED** - Move to next phase
- **When**: All criteria met, confident in direction
- **Action**: Update phase tracking, start next phase planning

**🔄 ITERATE** - Continue current phase with adjustments
- **When**: Core objective not met, but path forward is clear
- **Action**: Identify specific gaps, create iteration plan

**🔀 PIVOT** - Change project direction based on learnings
- **When**: Better opportunity discovered, or original approach not working
- **Action**: Document pivot rationale, restart appropriate phase

**⏸️ PAUSE** - Temporarily halt project
- **When**: External constraints (time/resources) but project is still viable
- **Action**: Document current state, plan for restart

**❌ STOP** - Abandon project
- **When**: Project no longer viable or worthwhile
- **Action**: Document learnings, archive work for future reference

### Step 4: Risk Assessment

#### Common Warning Signs by Phase

**Problem Validation Phase:**
🚨 Can't clearly articulate who has this problem
🚨 No evidence that problem actually exists
🚨 Problem seems too small or niche to matter

**Walking Skeleton Phase:**
🚨 Can't get basic deployment working
🚨 Architecture choices feel overly complex
🚨 Technology stack has major gaps in knowledge

**MVC Phases:**
🚨 Features taking much longer than expected
🚨 Adding complexity without clear value
🚨 Losing sight of original problem being solved

#### Risk Mitigation Questions
- **What's the biggest risk to project success right now?**
- **What would need to go wrong for this project to fail?**  
- **What early warning signs should I watch for?**
- **What's my backup plan if current approach doesn't work?**

### Step 5: Documentation for Future Self

#### Decision Record Template
```
## Phase [X] Validation Decision - [Date]

**Decision**: [PROCEED/ITERATE/PIVOT/PAUSE/STOP]

**Rationale**: 
- What was accomplished this phase
- Why this decision makes sense
- Key factors influencing the decision

**Key Learnings**:
- What worked well
- What didn't work
- What would I do differently

**Next Steps**: 
- Immediate actions required
- Success criteria for next phase
- Potential risks to monitor

**Future Self Notes**:
- Context that might be lost over time
- Decisions that might seem unclear later
- Resources or contacts that were helpful
```

## Validation Best Practices

### Timing
- **Schedule validation sessions** - Don't rush the decision
- **Take breaks between phases** - Allow for reflection
- **Validate when you're mentally fresh** - Not at end of long coding sessions

### Mindset
- **Be honest about quality** - Better to iterate than build on shaky foundation
- **Consider sunk cost fallacy** - Past investment doesn't justify continuing bad projects
- **Trust your instincts** - If something feels off, investigate further

### Tools
- **Use checklists consistently** - Don't rely on memory
- **Document decisions** - Future self will thank you
- **Review past decisions** - Learn from previous validation choices

## Integration with AI Workflow

### AI Role in Validation
- **AI prepares validation materials** - Summarizes accomplishments, identifies gaps
- **AI suggests questions** - Helps human think through decision systematically  
- **AI documents decisions** - Captures human decisions in structured format
- **Human makes final call** - AI informs, human decides

### Validation Handoff
1. **AI completes phase work** and prepares validation package
2. **Human reviews materials** using this framework
3. **Human makes go/no-go decision** and documents rationale
4. **AI updates project tracking** and begins next phase (if proceeding)

---

*This framework ensures human strategic oversight while leveraging AI acceleration. Based on GitLab phase gate methodology, solo developer decision frameworks, and AI-human collaboration patterns.*