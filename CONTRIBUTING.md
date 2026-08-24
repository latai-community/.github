# Contributing to LatAI

Welcome! LatAI is an open-source community focused on learning and building with artificial intelligence. We welcome contributions from everyone—whether code, documentation, experiments, ideas, or community participation.

This guide explains how to contribute to LatAI projects and how to propose new projects for possible adoption into the LatAI GitHub organization.

**New to LatAI?** Start with the [New Joiner Checklist](new_joiner_checklist.md) to understand prerequisites, community channels, and how to introduce yourself.

---

## Ways to Contribute

LatAI welcomes many forms of contribution:

- **Code and bug fixes** — Features, improvements, and problem resolution
- **Documentation** — READMEs, guides, tutorials, examples, and translations
- **Testing and technical feedback** — Reproducing issues, validating features, and code review
- **AI prompts, experiments, and evaluations** — Shareable prompts, model comparisons, and learning resources
- **Design and media assets** — Diagrams, visualizations, or other assets with clear project purpose
- **Issue triage and pull-request review** — Helping maintainers prioritize and validate work
- **Contributions to existing projects** — Any of the above applied to active LatAI repositories
- **Proposals for new community projects** — Ideas that could grow into LatAI initiatives

---

## Contributing to an Existing LatAI Project

### Standard Workflow

Each LatAI repository maintains its own README and contribution guidelines. Repository-specific instructions take precedence over this document.

**Follow this workflow:**

1. **Understand the project** — Read the repository's README to understand its purpose, scope, and current status.
2. **Check for existing work** — Search GitHub issues and pull requests to avoid duplicating efforts.
3. **Discuss substantial changes** — For features, major fixes, or architectural changes, open or comment on an issue to discuss your approach before investing significant effort.
4. **Fork or branch** — Fork the repository or create a feature branch following the repository's conventions.
5. **Make a focused change** — Keep your change scoped and purposeful. Include one logical concern per commit when practical.
6. **Update documentation and tests** — If your change affects behavior, add or update documentation and tests where applicable to the project's maturity level.
7. **Open a pull request** — Include a clear description of the problem, your solution, and any relevant issue numbers. Provide evidence that the change works (test results, screenshots, reproduction steps).
8. **Respond to feedback** — Engage constructively with review comments. Ask questions if feedback is unclear.

### What Maintainers Look For

Repository maintainers prioritize:

- Clear intent and scope
- Alignment with project goals
- Technical correctness and maintainability
- Appropriate testing and documentation
- Security and responsible practices
- Respectful, collaborative communication

---

## Developing a New Project Independently

You do not need prior approval from LatAI to begin developing a new project. Use your own repositories and development practices. This encourages experimentation and innovation.

**As you develop, consider:**

- **Define the problem** — Clearly state the problem your project solves or what learning objective it addresses.
- **Identify intended users** — Who will benefit from or learn from your project?
- **Maintain a usable README** — Document what your project does, how to use it, and how to contribute.
- **Document setup and execution** — Include clear steps to install, configure, and run your project.
- **Track progress visibly** — Use GitHub issues, milestones, or a roadmap to show direction and current limitations.
- **Protect sensitive information** — Never commit credentials, private keys, personal data, or unauthorized datasets.
- **Identify maintainers** — Clarify who owns the project and who is responsible for reviews.
- **Choose a license** — Select an open-source license compatible with LatAI's values (typically MIT or similar permissive licenses).
- **Prepare for demonstration** — Polish your README and ensure the project is in a demonstrable state before Show and Tell.

---

## Show and Tell

Show and Tell is a recurring LatAI community meeting where contributors present projects they are developing—whether early-stage prototypes or mature initiatives.

### Purpose and Announcements

Show and Tell meetings serve to:

- Share progress and get community feedback
- Discover projects happening in the community
- Discuss projects that may be candidates for LatAI organization adoption
- Celebrate and encourage peer learning

Meetings are announced through:

- **[LatAI WhatsApp Community](https://chat.whatsapp.com/LPgBVQcnDcRAk7Yi6WUWx7)** — Primary announcement channel
- **[LatAI Homepage](https://latai.org)** — Event calendar and details
- **[Discord](https://discord.gg/gH4XrVbbXM)** — Secondary announcements and discussion

### Who Can Present

Anyone in the LatAI community may present a project, regardless of maturity level.

### What to Demonstrate

When presenting your project at Show and Tell, explain:

- **The problem or learning objective** — What your project addresses or teaches
- **Current stage** — Alpha, beta, prototype, experimental, production, or other applicable description
- **What is implemented** — Working features and demonstrated capabilities
- **What remains experimental** — Known limitations, incomplete features, or areas under exploration
- **Community participation or support requested** — Feedback, code contributions, documentation, testing, ideas, or other specific needs
- **Adoption interest** — Whether you are interested in having the project considered for inclusion in the LatAI GitHub organization

### Important

- **Early-stage projects are welcome.** Show and Tell is a venue for feedback and community engagement, not a formal review process.
- **Presenting does not guarantee adoption.** It begins the evaluation process if you request it.
- **Projects seeking formal review** for LatAI adoption should be sufficiently documented and functional to undergo structured evaluation (see Project Review Checklist below).

---

## Requesting Project Adoption

If your project is mature enough for demonstration and you would like LatAI to consider it for official adoption, you can formally request inclusion in the `latai-community` GitHub organization.

### Process

1. **Present at Show and Tell** — Share your project during a Show and Tell meeting and indicate that you are interested in exploring adoption.

2. **Open a proposal issue** — In the [`.github` repository](https://github.com/latai-community/.github), open a GitHub issue with the following information:

   - **Project name and repository URL** — Exact name and link to your current repository
   - **Problem or learning objective** — What problem does it solve or what does it teach?
   - **Intended audience** — Who are the intended users or learners?
   - **Current development stage** — Alpha, beta, prototype, stable, production, etc.
   - **Working features** — What is implemented and functional?
   - **Known limitations and risks** — What is experimental, incomplete, or problematic?
   - **Technologies, AI models, datasets, or external services** — What dependencies or third-party systems are used? Document any licensing, API keys, or access requirements.
   - **License** — What open-source license does the project use?
   - **Current and proposed maintainers** — Who would maintain the project in the LatAI organization?
   - **Setup and demonstration instructions** — How can someone clone, build, and run your project?
   - **Roadmap or next milestones** — What is planned for future development?
   - **Requested support from LatAI** — What kind of help does the project need? (mentorship, code review, community testing, documentation, etc.)
   - **Confirmation of Show and Tell presentation** — Confirm that you have presented or are scheduled to present at Show and Tell.

### No Separate Application Form

We use GitHub issues for transparency and traceability. Your proposal becomes part of the community record and can be discussed openly.

---

## Project Review Checklist

When Steering Committee Members review a candidate project, they evaluate it against the following checklist. **The checklist is applied proportionately to the project's stage:** an educational prototype is evaluated differently than production software, but its maturity and limitations must be disclosed honestly.

- [ ] **Mission alignment** — Does the project align with LatAI's mission to support learning and building with artificial intelligence?
- [ ] **Clearly defined problem or learning objective** — Is the purpose obvious and valuable to the intended audience?
- [ ] **Honest description of maturity** — Are the project's stage, limitations, and experimental features clearly communicated?
- [ ] **Working demonstration or prototype** — Can reviewers see and interact with a functional artifact?
- [ ] **Complete README** — Does the repository have a clear, usable README?
- [ ] **Reproducible setup instructions** — Can someone new clone and run the project following the documented steps?
- [ ] **Clear open-source license** — Is the license declared and compatible with LatAI practices?
- [ ] **Identified maintainers** — Are project maintainers or responsible contributors clearly identified?
- [ ] **No exposed secrets or unsafe configuration** — Verify that credentials, API keys, private data, or unsafe defaults are not committed.
- [ ] **Appropriate data handling** — If the project processes personal, confidential, or copyrighted data, is it handled appropriately?
- [ ] **AI dependencies documented** — If the project uses AI models, datasets, or LLM APIs, are they documented and licensed appropriately?
- [ ] **Responsible AI considerations** — For projects involving AI systems, are known risks, biases, limitations, and necessary human review documented?
- [ ] **Reasonable repository hygiene** — Is the project structure organized and understandable?
- [ ] **Testing or validation** — Does the project include tests or documented manual validation appropriate to its stage?
- [ ] **Known issues and technical limitations** — Are limitations and known bugs documented?
- [ ] **Preliminary roadmap** — Are next milestones or future improvements outlined?
- [ ] **Realistic maintenance plan** — Can the project be maintained? Who will triage issues and review pull requests?
- [ ] **No malicious or deceptive functionality** — Is the project safe and transparent in its intent?

---

## Steering Committee Review

After you open a proposal issue, Steering Committee Members review it together in accordance with [governance.md](governance.md).

Their review considers:

- **Mission alignment** — Does the project support LatAI's goals?
- **Technical and documentation readiness** — Is the project sufficiently documented and functional?
- **Security, privacy, licensing, and responsible-AI concerns** — Are risks identified and mitigated?
- **Maintainership and sustainability** — Can the project be maintained within LatAI?
- **Collaborative fit** — Is the project appropriate for collaborative development in an open-source community?

### Possible Outcomes

- **Approved for integration** — The project is accepted. Integration planning begins.
- **Changes requested** — The project is promising but needs specific improvements before reconsideration.
- **Deferred** — The project is sound but may need additional maturity before adoption.
- **Not accepted** — The project is not a good fit for LatAI at this time. Feedback is provided when practical.

The Steering Committee follows the consensus-oriented decision model described in [governance.md](governance.md).

---

## Integration into the LatAI Organization

After your project is approved, Steering Committee Members and designated maintainers work with you to:

- **Determine repository strategy** — Decide whether to transfer your existing repository, import it into a new LatAI repository, or create a fresh repository with curated history.
- **Preserve history and attribution** — Maintain commit history and contributor attribution where practical.
- **Confirm licensing and ownership** — Verify that all contributors agree to the chosen license and that the organization has clear ownership rights.
- **Establish access and roles** — Add maintainers and contributors to the repository with appropriate permissions.
- **Apply community standards** — Ensure alignment with LatAI's code of conduct, documentation style, and security practices.
- **Plan initial improvements** — Identify high-impact documentation, issue templates, automation, or refactoring that would help the project thrive.
- **Announce the project** — Celebrate the addition through community channels (WhatsApp, Discord, GitHub).

**Acceptance into the organization marks the beginning of collaborative stewardship, not the end of the review process.** The project will continue to evolve with community input and maintainer guidance.

---

## Pull Request Expectations

When opening a pull request to any LatAI repository, aim for:

- **Focused scope** — Address one logical concern per pull request when practical.
- **Clear description** — Explain the problem being solved or feature being added.
- **Related issue** — Link to an existing issue when applicable (use `Closes #123` to auto-close).
- **Evidence of testing or validation** — Share test results, screenshots, or reproduction steps.
- **Documentation updates** — Update README or inline documentation if behavior changes.
- **No secrets or generated artifacts** — Verify that credentials, API keys, or unnecessary generated files are not included.
- **Respectful response to review** — Engage constructively with feedback and ask questions if guidance is unclear.
- **Disclose material AI assistance** — If AI tools significantly helped with coding, testing, or design validation, mention it in the PR description. This is particularly important if it affects authorship, confidence in the work, or licensing considerations.

---

## Community Conduct and Questions

### Code of Conduct

LatAI is committed to providing a welcoming, inclusive, and respectful environment for all contributors. Please review our community guidelines in [governance.md](governance.md) and the [New Joiner Checklist](new_joiner_checklist.md).

### Getting Help

**Questions about contributing?** Reach out through:

- **[LatAI WhatsApp Community](https://chat.whatsapp.com/LPgBVQcnDcRAk7Yi6WUWx7)** — Ask for help from the community
- **[Discord](https://discord.gg/gH4XrVbbXM)** — Join `#GeneralDev` for development discussion or `#Learning` for AI resources
- **GitHub Issues** — Open an issue in the relevant repository or in [`.github`](https://github.com/latai-community/.github) for organization-level questions

### Governance and Decision-Making

For details about how LatAI makes decisions, manages roles, and evolves as a community, see [governance.md](governance.md).

---

## Thank You

Your contributions—whether code, ideas, feedback, or mentorship—help make LatAI a thriving learning community. We look forward to collaborating with you.

**Let's build and learn together.** 🚀
