[Portfolio](../README.md) · [Русский](../../projects/factory.md)

# AI Software Factory — Automating the Development Lifecycle

**Status: reusable product in design.** Built on experience creating operational project-specific AI workflows.

![Process overview](../../assets/factory.svg)

[Explore the illustrative workflow, in Russian](https://dmitrii-naumenko.github.io/portfolio/demos/factory.html)

I’m designing an AI software factory that turns a development goal into a coordinated cycle of planning, implementation, review, and verification. It builds on my experience creating AI development workflows and brings the coordination of that work into a reusable system.

The factory manages how work moves forward—breaking goals into tasks, coordinating coding agents, and feeding review findings and test results back into implementation. The engineering harness provides the execution layer, with project context, isolated workspaces, repeatable checks, and development tools.

Designed to install into existing repositories, the system will adapt to each project’s architecture, conventions, and quality standards. The goal is to automate the work between a development request and a verified change, while keeping priorities and consequential decisions under the developer’s control.

## Engineering decisions

- Separate coordination from execution: factory manages work and feedback; harness supplies context, workspaces, checks, and tools.
- Adapt to an existing repository's architecture and quality standards.
- Feed review findings and failed checks back into implementation.
- Keep priorities and consequential decisions under developer control.

## Evidence and current boundary

Project-specific workflows have already used prepared tasks, isolated workspaces, independent review, and pre-delivery checks. The reusable factory consolidates this experience. Installation across repositories, goal decomposition, and portability remain target capabilities.

The walkthrough uses a fictional change request. Review identifies a missing period-boundary check, which leads to a revision and renewed verification. It illustrates the design; it is not a recorded run of a finished reusable product. A successful installation and task run in an independent repository will be a meaningful verification milestone.
