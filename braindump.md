# Custom Workflow for building with Claude Code

## Raw thoughts

I want to create a repository with documentation, research and a structure, to use when building things with Claude Code.

I care about a "phased" workflow that has artefacts produced during each phase, that eventually get to "Done". From there, the next phase can use the artefacts created prior in order to stay on track in the new phase.

### Phases I can talk about

#### Walking Skeleton

When starting a brand new project, I assume you will clone the workflow repo, and/or start a new folder and import all the workflow stuff.

From there, the first phase should be the WALKING SKELETON. This means getting something into production as soon as possible. For example, for an AI app, this might mean a React/Next.js frontend, in typescript, that is deployed with the pre-generated Landing page, as well as a FastAPI python backend that is also deployed. The next iteration from here might be getting one app talking to the other. I am assuming here a monorepo structure, but, that might not always be the case I suppose.

#### Minimal Viable Change

The other phase-workflows I believe should be focused around the concept of GitLab's "Minimal Viable Change" - rather than MV PRODUCT, it's a focus on changing what we already have, in a way that is both "minimal" AND "viable".

### Product Development Flow

I also want to follow a PRODUCT methodology for building each MVC. I'm a big fan of the Product Development Flow that is freely available in the GitLab Handbook that outlines the distinct phases of getting a MVC from an "idea in a backlog" to "deployed to all users" and beyond. The "vibe" of each phase makes it clear what questions need to be answered before moving on, and the "activities" listed in each phase become a menu of choices for how to achieve that goal.

For what I care about, this is way, way OVER-engineered, however, using it as the Gold Standard of what QUESTIONS need to be answered in each phase, and scaling that down to something manageable by a single person accompanied by AI is likely to outline a very good step-by-step flow for documenting intention, implementation etc.

### Asking Questions

A large part of the Product Development Flow(PDF) is being able to answer "simple sounding" questions well - for example "Why is this worth building?" sounds simple, but, the actual "value calculus" can sometimes be very complicated.

One thing I think an AI assistant, with the right documentation and workflows, can assist with, is asking a SERIES of questions to the user, aiming at the goal of the phase. Ideally, the AI balances asking the right questions, with forward motion, finding that right balance based on the scale of the change.

### Research Papers

Given the workflows we're talking about here are based on concepts from "the real world", it is a good idea to do research into what those things look like, and use that as input into the "workflow design" phase. For example, we should research and document the GitLab Product Development Flow, and continuously reference that when deciding how to structure the phases.

## Ideology

- Walking Skeleton comes first
- Minimal Viable Changes only, nothing huge in any one flow
- Follow a well-defined Product Development Flow that goes from phase to phase, producing artefacts at the end of each phase
- Scale the flow down to something that can be accomplished by ONE PERSON assisted by AI - each phase cannot take too long
- The AI can assist best by ASKING QUESTIONS in each phase, until we have what we need to know to create a good artefact
- The documentation produced should be WELL-STRUCTURED as well as PREDICTABLY-STRUCTURED from project to project, making it easy to "port" the AI workflow from project to project
- The workflows should be well documented FOR THE AI, such that it can follow it precisely
- Building the workflow from the start requires "Research Papers" being written on the source material
- The research papers should consistently be referenced when constructing the workflows, structuring the documentation, as well as structuring documents written for the AI

## Considerations

### Research Papers
- [ ] The GitLab Product Development Flow
    - The phases
    - For each phase, the "Goal" of the phase, the "meta-Questions" to be answered, and the "Activites" to consider
- [ ] The GitLab philosophy on building NEW Systems/Components/Products - does it differ from the MVC flow on an existing Product?
- [ ] The Walking Skeleton - getting the bare minimum to production EARLY
- [ ] Documenting Workflows for coding agents like Claude Code
- [ ] Documenting Projects and Products for "ambitious side projects" - not for a team of 100, but, for 1 developer and an AI.
- [ ] Documenting within the repo, vs documenting "outside" and using MVC - for example, using Notion and/or Linear as part of the Workflow
