# Conference Room Booking System – Git & Collaboration Workflow
Presentation Speaker Notes
---

## Slide 1 – Title & Context (30 seconds)

Introduce the Conference Room Booking System and explain that this presentation focuses specifically on how Git and GitHub are used to collaborate on the project.

---

## Slide 2 – Agenda (20 seconds)

Briefly outline what will be covered:
- Why collaboration matters for this system
- The Git workflow used in the repository
- How pull requests are handled
- How documentation fits into the workflow
- Common risks
- A short demo overview

---

## Slide 3 – Problem / System Context (45 seconds)

Explain that the system supports multiple features such as room booking, admin priority, visitor bookings, and maintenance blocks.
Because multiple features exist, multiple developers may work in parallel.
Without a clear Git workflow, this can lead to conflicts, broken features, or inconsistent API behaviour.
Git provides structure, accountability, and traceability.

---

## Slide 4 – High-Level Git Workflow (45 seconds)

Walk through the high-level flow:
Developers clone the repository, create feature branches, commit changes, open pull requests, and merge into the main branch.
Emphasise that changes are never made directly on main.

---

## Slide 5 – Key Technical Components (45 seconds)

Position Git as part of a larger technical setup.
Explain how Git works together with:
- The API codebase
- Docker for consistent environments
- Documentation stored in the repository
This ensures that code, configuration, and documentation evolve together.

---

## Slide 6 – Pull Requests & Collaboration Flow (1 minute)

Explain the importance of pull requests.
Each feature or fix is developed in its own branch.
A pull request is opened to describe the change and allow review.
This reduces bugs, improves code quality, and creates a clear history of decisions.

---

## Slide 7 – Documentation & Contracts (45 seconds)

Explain that documentation such as the README and API specifications are version-controlled.
Highlight that this is critical for onboarding new developers and avoiding misunderstandings.

---

## Slide 8 – Common Pitfalls / Risks (45 seconds)

Discuss common mistakes:
- Committing directly to main
- Large, unclear commits
- Poor commit messages
- Merge conflicts from outdated branches
- Forgetting to update documentation
Explain how the defined workflow helps avoid these issues.

---

## Slide 9 – Demo Overview (45 seconds)

Describe what would be shown in a live demo:
- The GitHub repository
- Branch structure
- Commit history
- A pull request example
Explain that the demo reinforces how collaboration is managed in practice.

---

## Slide 10 – Summary & Resources (30 seconds)

Summarise that a clear Git workflow enables safe collaboration, scalability, and easier onboarding.
Point viewers to the GitHub repository, README, and API documentation as key resources.
