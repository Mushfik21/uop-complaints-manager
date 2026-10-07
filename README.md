# UoP Complaints Manager

A system for reporting complaints about courses at the University of Portsmouth, built as our group project for **Software Engineering Theory and Practice (M30819)**, 2026/27.

## Project brief

> Students should be able to report complaints, keep track of them, and check their resolution. Course Leaders should be able to provide input at various stages, provide an action plan, and delegate tasks in the action plan to other stakeholders.

Our aim is to build something easier, clearer and fairer to use than UoP's current complaints process.

## Users

| User | What they can do |
|------|------------------|
| Student | Report a complaint about a course, track its progress, see how it was resolved |
| Course Leader | Give input at each stage, write an action plan, delegate tasks from it |
| Other stakeholders | Pick up and complete tasks delegated to them from an action plan |

## Early findings

From our Week 2 interview with the lecturer about the current system:

- **Parents cannot complain on a student's behalf.** This is a gap we could address.

_More findings to be added as our requirements gathering continues._

## Planned features

_Early ideas, to be confirmed by our requirements work._

- Students submit course complaints online
- Live status tracking from submission to resolution
- Course Leaders add input at each stage of a complaint
- Action plans with tasks delegated to stakeholders and tracked to completion
- Students can see the final resolution and outcome
- Secure handling of personal data

## Architecture

A 3-tier system:

| Tier | Folder | Tech |
|------|--------|------|
| Presentation (frontend) | `src/frontend/` | _TBC_ |
| Application (backend / API) | `src/backend/` | _TBC_ |
| Data (database) | `src/database/` | _TBC_ |

## Team

| Name | GitHub username | Role |
|------|-----------------|------|
|      |                 |      |
|      |                 |      |
|      |                 |      |
|      |                 |      |
|      |                 |      |
|      |                 |      |

## Progress

| Week | What we did | Notes |
|------|-------------|-------|
| 1 | Presented the project idea to the class | [notes](docs/meetings/) |
| 2 | Interviewed the lecturer about the current complaints system | [Q&A](docs/requirements-gathering/) |

## Key dates

| Deliverable | Deadline |
|-------------|----------|
| Coursework 1: requirements, design, version control setup | 7 December 2026 |
| Coursework 2: implementation, testing, demo videos | 4 May 2027 |

## Repository layout

| Folder | What goes in it |
|--------|-----------------|
| `docs/meetings/` | One file per meeting (copy `TEMPLATE.md`) |
| `docs/requirements-gathering/` | Raw evidence: interview Q&A, surveys, analysis |
| `docs/presentation/` | Slides |
| `trials/` | Small experiments with tools and frameworks |
| `src/` | The code: `frontend/`, `backend/`, `database/` |
| `tests/` | Automated tests |

## How we work

- Don't commit straight to `main`. Make a branch per task, e.g. `feature/complaint-form`.
- Open a pull request, get a teammate to review it, then merge.
- Every task gets a GitHub Issue. Link it in the PR with `Closes #12`.
- Write meeting notes on the day and commit them.

## Getting started

_Setup instructions will go here once the tech stack is chosen._
