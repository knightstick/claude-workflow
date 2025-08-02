# AI Questioning Script: Walking Skeleton Phase

*Structured questioning framework for AI assistants to guide Walking Skeleton implementation.*

## Script Overview

**Purpose**: Guide human through systematic Walking Skeleton development using research-backed questioning methodology

**Based on**: Walking Skeleton methodology research, GitLab validation frameworks, AI workflow patterns research

**Usage**: AI assistant should ask these questions in sequence, adapting based on responses

## Phase 1: Architecture Discovery

### Component Identification Questions

**AI Instruction**: Ask these questions to identify core architectural components. Wait for answers before proceeding.

#### Question 1: System Boundaries
> "Let's start by identifying the core components of your system. Based on your project description, what are the main parts that need to work together? 
> 
> For example:
> - Frontend (web interface, mobile app, CLI)
> - Backend (API, server, business logic)
> - Database (data storage, persistence)
> - External services (APIs, payment, auth)
> - Infrastructure (deployment, hosting)
> 
> Which of these apply to your project, and are there others I'm missing?"

**Follow-up**: Based on their answer, validate the minimal set needed for Walking Skeleton.

#### Question 2: Data Flow Validation
> "Now let's trace the simplest possible user journey through your system. Walk me through what happens when a user performs the most basic action in your app.
> 
> Start with: 'A user wants to [basic action]...'
> 
> What components does this touch, and in what order?"

**AI Goal**: Ensure they understand the end-to-end flow and identify all components in the path.

#### Question 3: Integration Points
> "Looking at the components you've identified, where are the potential integration challenges?
> 
> Specifically:
> - How does the frontend talk to the backend?
> - How does the backend connect to the database?
> - What external services need to be integrated?
> - Where could things break in the connection between components?
> 
> Which integration do you think will be the most challenging?"

**AI Goal**: Surface technical risks early and prioritize the riskiest integrations for Walking Skeleton validation.

## Phase 2: Minimal Feature Definition

### Feature Scoping Questions

#### Question 4: Core Value Proposition
> "What's the absolute smallest thing you could build that would prove this system works and delivers value?
> 
> Think about it this way: If you had to demo this to someone in 2 minutes, what single feature would you show that captures the essence of your project?
> 
> Don't worry about making it polished - what's the core functionality that makes this project worth building?"

**AI Goal**: Help them identify the minimal valuable feature that exercises the full stack.

#### Question 5: Walking Skeleton Feature Specification
> "Let's define your Walking Skeleton feature precisely. Based on what you said, I think your minimal feature could be: [summarize their answer].
> 
> Is this right? Let's refine it:
> - What exactly does the user do? (specific actions)
> - What do they see as a result? (specific outputs)
> - What data is created, stored, or retrieved?
> - How will you know it's working correctly?
> 
> Can we make this even simpler while still proving the system works?"

**AI Goal**: Create a precise, testable feature definition that's minimal but complete.

#### Question 6: Implementation Complexity Assessment
> "Looking at this minimal feature, let's break down what you'll need to implement:
> 
> **Frontend work**: [list based on their feature]
> **Backend work**: [list based on their feature]  
> **Database work**: [list based on their feature]
> **Integration work**: [list based on their feature]
> 
> Does this seem like something you can complete in 1-2 weeks? If not, how can we simplify further?"

**AI Goal**: Reality-check the scope and ensure it's achievable within Walking Skeleton timeframe.

## Phase 3: Technical Planning

### Technology Stack Validation

#### Question 7: Stack Feasibility Check
> "Let's validate your technology choices for this Walking Skeleton:
> 
> **Frontend**: [their choice] - Do you have experience with this? Are there any setup/deployment concerns?
> **Backend**: [their choice] - Same questions here.
> **Database**: [their choice] - Any special configuration or hosting requirements?
> **Deployment**: Where are you planning to deploy this?
> 
> Are there any parts of this stack you haven't used before? Should we consider simpler alternatives for the Walking Skeleton?"

**AI Goal**: Identify knowledge gaps and potential technical blockers before implementation starts.

#### Question 8: Development Environment Planning
> "What's your current development setup for this stack?
> 
> - Do you have the necessary tools installed?
> - Have you worked with this combination of technologies before?
> - What's your preferred development workflow?
> - Are there any setup steps we should tackle first?
> 
> Is there anything about the development environment that could slow down the Walking Skeleton implementation?"

**AI Goal**: Ensure smooth development experience and identify setup blockers.

### Deployment Strategy Questions

#### Question 9: Deployment Target Validation
> "Where do you want to deploy your Walking Skeleton, and what does that require?
> 
> For your chosen platform ([their platform]):
> - Do you have an account set up?
> - What configuration will be needed?
> - How will database hosting work?
> - Are there any costs to consider?
> - What's the deployment process?
> 
> Have you deployed this type of application to this platform before?"

**AI Goal**: Ensure deployment is feasible and won't become a major blocker.

#### Question 10: Minimum Viable Deployment
> "For the Walking Skeleton, we want the simplest possible deployment that proves the system works in production. 
> 
> Could we start with:
> - [suggest simplified deployment based on their stack]
> - [suggest simplified database option if applicable]
> - [suggest simplified hosting option]
> 
> We can make it more sophisticated later, but what's the absolute minimum that gets this working and accessible via URL?"

**AI Goal**: Define the simplest possible production deployment.

## Phase 4: Implementation Planning

### Task Breakdown Questions

#### Question 11: Implementation Order
> "Let's plan the implementation order to minimize risk and maximize learning:
> 
> Based on your Walking Skeleton feature, I suggest this order:
> 1. [suggest order based on their architecture]
> 2. [continue with logical sequence]
> 3. [end with integration and deployment]
> 
> Does this order make sense? What would you want to tackle first, and why?"

**AI Goal**: Help them plan implementation sequence that validates riskiest parts early.

#### Question 12: Success Criteria Definition
> "How will we know the Walking Skeleton is truly complete and successful?
> 
> Let me suggest some criteria:
> - [ ] Feature works end-to-end locally
> - [ ] All components are connected and communicating
> - [ ] Application is deployed and accessible via URL
> - [ ] Basic error handling exists
> - [ ] Development workflow is established
> 
> What else should we add to this list? What would make you confident to start building features on this foundation?"

**AI Goal**: Establish clear, objective success criteria for the phase.

## Phase 5: Risk Assessment

### Challenge Identification Questions

#### Question 13: Technical Risk Assessment
> "What do you think is most likely to go wrong during Walking Skeleton implementation?
> 
> Consider:
> - Technologies you haven't used before
> - Integration points between components
> - Deployment and hosting challenges
> - Time constraints or availability
> 
> What's your biggest concern, and how might we mitigate that risk?"

**AI Goal**: Identify potential blockers and plan mitigation strategies.

#### Question 14: Scope Creep Prevention
> "As you implement this Walking Skeleton, you'll probably think of features to add or improvements to make. That's normal but can derail the focus.
> 
> How will you resist the temptation to add 'just one more thing'? What's your plan for capturing those ideas without implementing them now?
> 
> What would convince you to keep the scope minimal until the Walking Skeleton is complete and deployed?"

**AI Goal**: Help them commit to minimal scope and plan for managing feature ideas.

## Implementation Support

### During Development Questions

**AI Instruction**: Use these questions when the human encounters challenges during implementation.

#### When Stuck on Technical Issues
> "Let's debug this systematically:
> 1. What exactly is happening vs. what you expected?
> 2. What was the last thing that worked?
> 3. What changed since then?
> 4. Have you seen this error before, or found similar issues online?
> 
> Should we try a simpler approach, or is this the right path to push through?"

#### When Considering Scope Changes
> "I notice you're thinking about adding [feature/improvement]. Let's evaluate this:
> - Is this necessary for the Walking Skeleton to work?
> - Does this prove something new about the architecture?
> - Can this wait until after the Walking Skeleton is deployed?
> 
> Remember, the goal is minimal end-to-end functionality first. Should we add this to the post-Walking Skeleton list instead?"

## Validation Preparation

### Pre-Human-Validation Questions

#### Question 15: Validation Readiness Check
> "You're approaching the end of the Walking Skeleton phase. Let's prepare for your validation checkpoint:
> 
> **Completion Assessment**:
> - Is the minimal feature working end-to-end?
> - Is the application deployed and accessible?
> - Are all major components connected?
> 
> **Quality Assessment**:
> - How do you feel about the code quality?
> - Is the architecture solid for future development?
> - Is the documentation sufficient?
> 
> **Strategic Assessment**:
> - Does this foundation support your project goals?
> - Are you confident to build features on this base?
> - Any major concerns or doubts?
> 
> What aspects need more work before you're ready for the validation checkpoint?"

**AI Goal**: Help them prepare for systematic human validation using the framework.

---

## Usage Notes for AI Assistants

### Questioning Best Practices
- **Ask one question at a time** - Don't overwhelm with multiple questions
- **Wait for complete answers** - Don't rush to next question
- **Adapt based on responses** - Skip irrelevant questions for their project type
- **Provide examples** - Help them understand what you're looking for
- **Validate understanding** - Summarize their answers back to them

### When to Reference Research
- **Walking Skeleton methodology**: When explaining minimal implementation approach
- **GitLab validation**: When discussing phase gates and success criteria  
- **Solo developer practices**: When balancing scope vs. quality tradeoffs
- **AI workflow patterns**: When structuring the development process

### Red Flags to Watch For
- Scope creep during planning
- Technology choices that create unnecessary complexity
- Avoiding deployment until "everything is perfect"
- Not defining clear success criteria
- Perfectionism preventing progress

---

*This questioning script implements structured AI guidance based on Walking Skeleton methodology research, GitLab Product Development Flow validation practices, and AI workflow documentation patterns for optimal human-AI collaboration.*