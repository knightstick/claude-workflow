# MVC (Minimal Viable Change) Phase Template

*Add one small, valuable change to your existing Walking Skeleton.*

## Phase Overview

**Goal**: Implement one minimal but meaningful improvement that adds user value while maintaining system stability.

**Duration**: 1-2 weeks (time-boxed)

**Prerequisites**: Completed Walking Skeleton with deployed, working system

**Success Criteria**: 
- One new feature/improvement implemented and working
- Existing functionality remains stable
- System remains deployable throughout development
- Feature adds meaningful user value
- Documentation updated appropriately

## Research Foundation

Based on **GitLab Product Development Flow research**:
- "Build MVCs that improve Product KPIs and/or Engineering KPIs"
- "If it fails to do so, abandon it and restart validation cycle"
- Focus on minimal but viable changes rather than large features

Based on **Solo Developer Documentation Strategy research**:
- Time-box each phase to manageable scope
- Document decisions for future self
- Maintain "just enough" documentation overhead

## Phase Activities

### 1. Feature Selection and Scoping

#### Value Assessment Questions
**AI Prompt**: "Help identify and validate the next minimal viable change for this project."

**Key Questions**:
- What's the most valuable small improvement users would notice?
- What enhancement would build on the Walking Skeleton foundation effectively?
- Which feature would prove/validate an important assumption about the product?
- What improvement would make the biggest difference with minimal implementation effort?

**Deliverable**: Clear, specific feature definition with user value justification

#### Scope Validation
**AI Prompt**: "Help scope this feature to truly minimal viable implementation."

**Scoping Criteria**:
- Can be completed within 1-2 week timeframe
- Builds on existing Walking Skeleton architecture without major changes
- Provides user-visible value (not just technical improvements)
- Can be tested and validated independently
- Doesn't break existing functionality

**Examples by Project Type**:
- **Web App**: Add user profile page, implement basic search, add data filtering
- **API Service**: Add new endpoint, implement basic authentication, add data validation
- **CLI Tool**: Add new command, implement configuration file, add output formatting
- **Mobile App**: Add new screen, implement basic navigation, add data persistence

### 2. Technical Planning

#### Implementation Assessment
**AI Prompt**: "Break down the technical implementation of this MVC feature."

**Planning Questions**:
- What existing code/components need to be modified?
- What new code/components need to be created?
- How does this integrate with the current architecture?
- What are the potential technical risks or complications?
- How will this be tested to ensure it works correctly?

**Risk Evaluation**:
- Identify components that could break during implementation
- Plan rollback strategy if feature doesn't work as expected
- Consider impact on deployment pipeline and existing users

#### Architecture Impact
**AI Prompt**: "Assess how this feature affects the existing system architecture."

**Architecture Questions**:
- Does this require changes to the database schema?
- Will this affect the API or interface contracts?
- How does this integrate with existing authentication/authorization?
- What new dependencies or external services are needed?
- How will this feature be configured or customized?

### 3. Implementation Strategy

#### Development Approach
**AI Prompt**: "Plan the implementation sequence to minimize risk and validate assumptions early."

**Implementation Sequence**:
1. **Start with backend/data changes** (if needed)
2. **Implement core functionality** with minimal UI
3. **Add user interface** and user experience elements
4. **Integrate with existing features** and test interactions
5. **Polish and error handling** to production quality

#### Testing Strategy
**AI Prompt**: "Help design testing approach for this MVC feature."

**Testing Requirements**:
- Test new functionality works as expected
- Verify existing functionality still works (regression testing)
- Test integration points between new and existing features
- Validate deployment process still works correctly
- Test error handling and edge cases

### 4. Quality Assurance

#### User Experience Validation
**AI Prompt**: "Help validate that this feature actually provides user value."

**UX Validation Questions**:
- Is the feature discoverable by users?
- Is the interface/interaction intuitive?
- Does it solve the problem it was intended to solve?
- Would users actually use this feature?
- How does it fit with the overall user experience?

#### Code Quality Assessment
**AI Prompt**: "Review code quality and maintainability of the implementation."

**Quality Criteria**:
- Code follows existing project conventions and patterns
- New code is well-documented and maintainable
- Error handling is appropriate and user-friendly
- Performance impact is acceptable
- Security considerations have been addressed

## Human Validation Checkpoint

### Phase Completion Assessment

#### Objective Checklist
- [ ] MVC feature is implemented and working correctly
- [ ] Existing functionality remains stable and working
- [ ] Feature adds meaningful user value
- [ ] System deployment pipeline still works
- [ ] Documentation has been updated appropriately
- [ ] Testing validates both new and existing functionality

#### Quality Assessment
**For the new feature, evaluate**:
- **User Value**: Does this actually improve the user experience?
- **Technical Quality**: Is the implementation solid and maintainable?
- **Integration**: Does it work well with existing features?
- **Stability**: Has it introduced any bugs or instabilities?

#### Strategic Review
- **Value Delivered**: Did this MVC achieve its intended improvement?
- **Learning Generated**: What did you learn about the product/users/technology?
- **Architecture Impact**: How has this affected the system's foundation?
- **Future Direction**: What does this suggest for the next MVC?

### Decision Framework

#### Go/No-Go Questions
1. **Is the MVC feature working correctly and providing user value?**
   - YES → Continue to question 2
   - NO → Should you fix issues or abandon this feature?

2. **Do existing features still work correctly?**
   - YES → Continue to question 3
   - NO → Fix regressions before proceeding

3. **Is the system still maintainable and deployable?**
   - YES → Continue to question 4
   - NO → Address technical debt before next MVC

4. **Are you ready to plan the next MVC?**
   - YES → **✅ PROCEED** to next MVC planning
   - NO → Take break or address any remaining issues

#### Warning Signs
🚨 **Red Flags** that suggest iteration needed:
- Feature doesn't provide the expected user value
- Implementation introduced bugs or instabilities
- Code quality has degraded significantly
- Deployment process has become unreliable
- Feature is too complex for users to understand/use

### Decision Documentation

```markdown
## MVC Phase [X] Validation - [Date]

**Feature Implemented**: [Brief description of the MVC]

**Decision**: [PROCEED/ITERATE/PIVOT/PAUSE/STOP]

**User Value Assessment**:
- Intended value: [What this was supposed to achieve]
- Actual value: [What it actually achieved]
- User feedback: [Any user testing or feedback received]

**Technical Assessment**:
- Implementation quality: [Rating and notes]
- Integration success: [How well it works with existing features]
- Stability impact: [Any issues introduced or resolved]

**Key Learnings**:
- What worked well: [Successful aspects of implementation]
- What was challenging: [Difficulties encountered]
- Assumptions validated/invalidated: [What you learned about users/product]

**Next MVC Planning**:
- Priority improvements identified: [Potential next features]
- Technical debt to address: [Any cleanup needed]
- User feedback to investigate: [Areas for future exploration]

**Future Self Notes**:
- Implementation details that might be forgotten: [Technical specifics]
- User behavior observations: [How users actually use the feature]
- Architecture decisions for future reference: [Why certain choices were made]
```

## Next Phase Planning

### If PROCEEDING to Next MVC

**Next MVC Selection Process**:
1. Review user feedback and usage data from current MVC
2. Assess technical debt and maintenance needs
3. Identify next highest-value small improvement
4. Validate that next MVC builds logically on current system

**Considerations for MVC Sequencing**:
- Build complementary features that work together
- Address user pain points in order of priority
- Maintain architectural coherence across MVCs
- Balance new features with technical improvements

### If ITERATING on Current MVC

**Iteration Focus Areas**:
- User experience improvements based on feedback
- Technical quality improvements
- Integration refinements with existing features
- Performance or reliability enhancements

---

*This template implements GitLab MVC methodology adapted for solo developers, with systematic AI guidance and human validation gates based on research findings.*