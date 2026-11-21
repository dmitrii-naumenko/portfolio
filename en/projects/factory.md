[Portfolio](../README.md) · [Русский](../../projects/factory.md)

# AI Software Factory — Automating the Development Lifecycle

**In use and evolving.**

![AI Software Factory workflow](../../assets/factory.svg)

**[Explore a step-by-step task example, in Russian](https://dmitrii-naumenko.github.io/portfolio/demos/factory.html)**

## Purpose and my contribution

I’m developing an AI software factory that turns a development goal into a coordinated cycle of planning, implementation, review, and verification. It builds on my experience creating AI development workflows and brings the coordination of that work into a reusable system.

The factory manages how work moves forward—breaking goals into tasks, coordinating coding agents, and feeding review findings and test results back into implementation. The engineering harness provides the execution layer, with project context, isolated workspaces, repeatable checks, and development tools.

Standalone installation into existing repositories and adaptation to their architecture, conventions, and quality standards remain a development direction. Priorities and consequential decisions stay under the developer’s control.

## Engineering decisions

- Separate coordination from execution: factory manages work and feedback; harness supplies context, workspaces, checks, and tools.
- Use the project’s own architecture, verification commands, and conventions.
- Feed review findings and failed checks back into implementation.
- Keep priorities and consequential decisions under developer control.

## How the factory carries a task forward

**Organize work around the outcome.** A task retains its goal, boundaries, and acceptance criteria. The agent receives project context and an isolated workspace; execution remains connected to the original request.

**Turn findings into follow-up work.** Independent review and checks form part of the same cycle. A finding leads to a revision, followed by verification of the updated change.

**Preserve progress across interruptions.** Task state, code changes, and the reason for stopping remain available. Recovery compares the saved state with the actual state of the repository and delivery tools.

**Bring the developer in for consequential decisions.** Priorities, ambiguous requirements, and delivery permissions remain explicit. When human input is needed, the handoff preserves context and a clear next step. This leaves attention available for architecture and the next task while prepared work progresses through its cycle.
