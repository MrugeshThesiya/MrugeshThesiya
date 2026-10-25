# Hi, I'm Mrugesh 👋

Full-stack engineer who ships products real people depend on.

I took PDEU's management portal from a first requirements conversation to production, where it now serves **450+ students and 40+ faculty**. I own the whole loop: talking to users, building, deploying, and supporting. I'm also building **Vajra**, an open-source security tool for AI coding agents, and I work daily with those agents to ship faster.

## Projects

**PDEU Management Portal** — [portal.pdpu.ac.in](https://portal.pdpu.ac.in) · *In production*
`TypeScript` `React` `Node.js` `Express` `Appwrite` `LDAP` `Docker` · May 2024 – Present

- Own the portal end to end, from requirements to deployment and support: one product for industrial training and for minor, major, and comprehensive projects, used by **450+ students and 40+ faculty**.
- Replaced manual submission and tracking with one workflow: team and mentor allocation, submissions with deadlines, evaluation and grading, training applications, document uploads, and status reports.
- Ran requirements gathering, demos, and feedback rounds directly with faculty, administrators, and students; triage their bug reports and feature requests and ship the fixes.
- Integrated sign-in with the campus LDAP directory by working with the university IT department, and built role-based access for SuperAdmin, faculty, and mentors.
- Rebuilt the original Next.js app on React and Node.js in a pnpm and Turborepo monorepo, with self-hosted Appwrite for auth, database, and storage; containerized with Docker and deployed on the university's own server.

**[Vajra](https://github.com/codekalakaars/vajra)** — Sandbox for AI Coding Agents · *Open source, Apache 2.0*
`Rust` `TypeScript` `napi-rs` `pnpm` `Turborepo`

- Building an open-source sandbox that confines AI CLI agents (Claude Code, Codex, OpenCode) to a single project, so they can work on code without reaching secrets elsewhere on the machine.
- Wrote the native core in Rust, exposed to Node through napi-rs, enforcing filesystem confinement with Landlock on Linux and Seatbelt on macOS.
- Hides `.env` files from file listings and automatically redacts secret values in agent output.
- Shipped a CLI for multi-agent task execution with developer, master, and worker roles and per-file permissions, across five packages in one monorepo.

**Open Elective Choice Filling System** — PDEU
`Go` `React` `REST APIs` `Docker`

- Designed and built a Go backend that collects open elective choices from every student of a PDEU school in one pass, run department by department, with a React front end for students and coordinators.
- Built the REST API in Go with request validation, so each student can submit only electives offered to their department and cannot submit duplicate or conflicting choices.
- Handled many students submitting at the same time with Go's concurrency primitives and safe writes, so choices are never lost or overwritten during a filling window.
- Built coordinator controls to configure electives, seat limits, and filling windows per department, and to export the collected choices for allocation.
- Secured the API with authenticated access and role checks, and containerized the service with Docker for deployment.

## Experience

**Web Development Committee, PDEU** — Gandhinagar, India · *Committee Lead* · July 2024 – Present

- Lead a team of student developers building production software for the university under faculty mentorship.
- Teach a weekly engineering session to **60+ students** on AI coding agents and context engineering, learning with AI, and backend architecture, authentication, databases, and infrastructure.
- Write and publish the session guides at [wdc-guides.pages.dev](https://wdc-guides.pages.dev/guides/).

**Pandit Deendayal Energy University (PDEU)** — Gandhinagar, India · *Tech Intern* · May 2024 – July 2024

- Scoped and built the first version of the project submission portal with faculty stakeholders in Next.js and Appwrite; it grew into the production portal above.

## Skills

| Area | Tools |
| --- | --- |
| Languages | TypeScript, JavaScript, Go, Python, Java |
| Web | React.js, Next.js, Node.js, Express.js, Astro, Tailwind CSS, REST APIs |
| Data and Auth | Appwrite (self-hosted), MySQL, MongoDB, LDAP, role-based access control |
| Infrastructure | Docker, Nginx, PM2, Git, Linux servers, AWS, DigitalOcean |
| AI-Assisted Development | Claude Code and other coding agents, context engineering, agent sandboxing |
| Working with Users | Requirements gathering, stakeholder demos, user support, technical teaching and writing |

## Education

**B.Tech. Computer Science and Engineering** — Pandit Deendayal Energy University (PDEU), Gandhinagar, India
CGPA: 9.44 · July 2023 – Present

## Get in Touch

[![Email](https://img.shields.io/badge/email-thesiyamrugesh@gmail.com-2b2b2b?style=flat-square&logo=gmail&logoColor=white)](mailto:thesiyamrugesh@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-mrugeshthesiya-0a66c2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mrugeshthesiya/)
[![X](https://img.shields.io/badge/X-MrugeshThesiya-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/MrugeshThesiya)
[![GitHub](https://img.shields.io/badge/GitHub-MrugeshThesiya-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/MrugeshThesiya)
[![Portfolio](https://img.shields.io/badge/Portfolio-mrugesh.pages.dev-24292e?style=flat-square&logo=googlechrome&logoColor=white)](https://mrugesh.pages.dev/)
