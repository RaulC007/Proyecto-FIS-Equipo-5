# Project Process

## 1. Development Process

We used an **iterative approach organized in sprints**, each one closing with a delivery. Tasks were tracked as GitHub Issues and worked on in short branches.

**Team structure:** 6 members, 1 leader, 2 subgroups (see [Team, Roles and Contribution Metric](./Team-Metric-and-Roles.md)).

| Subgroup | Members | Responsibility |
| --- | --- | --- |
| Repository and architecture | Correa Aguilar Raúl, Vargas Mena Danna Verónica | GitHub structure, version control, documentation of requirements and process |
| Information and video | Atencio Galea Alejandro Daniel, Vega Bastarrachea Jesús Diego, Hernandez García Luis Gerardo, Pool Canul Sofia Elizabeth | Procedure data, content writing, use cases, presentation and video |

### Sprint summary

| Sprint | Dates | Size | Goal | Result |
| --- | --- | --- | --- | --- |
| Sprint 1 | Sep 25 - Oct 4, 2026 | 6 members | Gather requirements with School Control and write the first FR/NFR set | First delivery: initial requirements |
| Sprint 2 | Oct 5 - Oct 30, 2026 | 6 members | Refine requirements, define use cases, sketch interfaces, prepare presentation and video | Second delivery: refined requirements, use cases and diagram, prototype, presentation |

### Sprint 1: Requirements gathering

- **Planning:** Team meeting on Sep 25 to define the project approach and split the analysis tasks.
- **Activities:** In-person interview with School Control staff and the professor (Sep 28); format unification meeting with another team (Sep 29); first draft of FR and NFR.
- **Roles:** Whole team in the general phase; two subgroups afterwards.
- **Result:** First FR/NFR list and a shared format with the other team. 

### Sprint 2: Refinement and design

- **Planning:** Date of the planning meeting; tasks created as GitHub Issues with the weights in the contribution metric.
- **Activities and owners:**

| Activity | Owner(s) | Evidence |
| --- | --- | --- |
| Review of FR/NFR: remove, add and reword | Vargas, Atencio, Hernández, Pool, Vega |  |
| Acceptance criteria, priority justification and FR–NFR links | Same drafting members |  |
| Use cases and use case diagram | Vega | PR / Issue links |
| Interface prototypes | Atencio, Correa | PR / Issue links |
| Repository organization, translations and merges | Correa, Vargas | PR / Issue links |
| Presentation and video | Hernández, Pool, Vega | Links |

## 2. Process Management

### Tools and communication

| Purpose | Tool | Use |
| --- | --- | --- |
| Synchronous follow-up | Discord calls | Sprint planning and review meetings |
| Quick coordination | WhatsApp | Day-to-day questions and PR review coordination |
| Task tracking | GitHub Issues | One issue per task, with description and owner |
| Review | GitHub Pull Requests | Peer review before merging to `main` |
| Progress monitoring | Commits and merged PRs | Evidence of delivered work |

### Meeting log

| # | Date and time | Attendees | Purpose | Agreements and decisions | Action items |
| --- | --- | --- | --- | --- | --- |
| 1 | Sep 25, 2026, 10:00 PM | Whole team | Define the project approach and analyze the tasks | Approach chosen and task split | The team defines the requirements in a document |
| 2 | Sep 28, 2026, 2:00 PM | Whole team, School Control staff, professor | Interview about procedures, timelines and frequent questions | Information collected for the procedure catalog; Key answers |  |
| 3 | Sep 29, 2026, 9:00 PM | Whole team and another team | Unify FR/NFR formats because both teams share the same problem | Common requirement format | Owner and deadline |
| 4 | Oct 28, 2026, 4:00 PM | Correa, Vargas| Discord call for the final changes in the repository in the second delivery | Corrections, changes and adjustments in the repository, requirements, and processes | |

Meeting notes are taken by Vargas, Atencio, Hernández and Pool. Conflicts or disagreements are resolved in the meeting where they appear and recorded in the **Agreements** column.

### Deliverables and deadlines

| Deliverable | Deadline | Owner | Status |
| --- | --- | --- | --- |
| First delivery | 05/Oct/2026 | Whole team | Done |
| Second delivery | 30/Oct/2026 | Whole team | Done |

## 3. GitHub Process

1. A `main` branch was created with a draft README and folders for the requirements, and all collaborators were added.
2. Each task starts as an **Issue** that describes what will be done.
3. A **branch** is created from the issue and the work is committed in VS Code.
4. When finished, a **Pull Request** is opened and linked to the issue (for example, `Closes #12`).
5. Collaborators review the PR looking for errors, changes and improvements; coordination happens via WhatsApp.
6. If the PR is approved, it is **merged to `main`**. If not, it is rejected, adjusted and a new PR is opened.

### Conventions

| Item | Convention |
| --- | --- |
| Branch names | `feature/<issue-number>-short-description`, for example `feature/12-acceptance-criteria` |
| Delivery branch | `delivery-2` for the second delivery, merged to `main` when closed |
| Commit messages | Start with a verb in English, for example `Add acceptance criteria to FR1` |
| Pull requests | Title with the issue number; at least one reviewer other than the author |



**README.md must contain:** project description, project overview, current status, and the repository structure. At the time of writing.

