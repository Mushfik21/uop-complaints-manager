# UoP Complaints Manager

A complaints management system for the University of Portsmouth, built as our group project for **Software Engineering Theory and Practice (M30819)**, 2026/27.

The goal is a system that is easier and fairer to use than the current UoP complaints process, for students, for the people who complain on their behalf, and for the staff who handle the complaints.

## The problem

The current UoP complaints process is limited. For example, our requirements interview showed that **parents cannot submit a complaint on behalf of a student**. We're gathering requirements to find gaps like this and design a system that fixes them.

## Planned features

_Early ideas, to be confirmed by our requirements work._

- Students submit, track and update complaints online
- Complaints can be raised on a student's behalf (e.g. by a parent), with the student's consent
- Live status tracking so complainants know where their case is
- Staff dashboard for assigning, managing and resolving complaints
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
