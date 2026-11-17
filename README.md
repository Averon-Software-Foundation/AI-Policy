
## AI Contribution Policy

This policy governs the use of generative AI and AI-assisted tools in Averon Software Foundation projects.

### 1. Core Principles

People ( not AI ) are responsible for every contribution. Anyone submitting work must understand it, verify it, and be able to explain why it is correct and should be merged. This allows us to prevent openclaw agents and etc from making PRs.

### 2. Vibe Coding and Blind AI Use

Vibe coding and blindly using AI are prohibited due to bias or a million or so issues I can think off the top of my head

Do not:

- Ask AI to generate code or changes and submit them without understanding them.
- Blindly copy, merge, or rely on AI-generated code, tests, documentation, or recommendations.
- Use AI to perform substantial implementation work or replace independent reasoning.
- Treat AI output as proof that code is correct, secure, compliant, or ready for release.
- Submit AI-generated work without disclosure and human review.

AI output may be incomplete, incorrect, biased, outdated, insecure, or fabricated.

### 3. Permitted Minor Contributions

Minor AI-assisted contributions are permitted only when they are carefully moderated and reviewed.

AI may be used to assist with:

- Suggestions for wording or documentation.
- Explanations of unfamiliar errors or concepts.
- Small, localized code suggestions.
- Identifying possible improvements or edge cases.
- Assistance with routine administrative or organizational tasks.
- Basic Decision making eg When should i release version 1 of x 

AI may assist, but it must not replace the contributor’s own judgment or understanding.

Substantial features, complex implementations, architectural decisions, or work outside the contributor’s expertise must not be submitted as minor AI contributions.

### 4. Required Human Review

Before submitting a contribution, the contributor must:

1. Review the complete output.
2. Understand every material change.
3. Verify correctness, security, privacy, licensing, and compatibility.
4. Run appropriate tests and checks ( including their own tests not just our CI) 
5. Remove unsupported claims, secrets, and sensitive information.
6. Confirm that the submitted work is accurate and appropriate.

Passing automated checks does not replace human review.

### 5. AI Disclosure

Every AI-assisted contribution must be labeled as `AI-assisted` in the pull request or submission.

The disclosure should briefly describe:

- Which parts used AI.
- How the contribution was reviewed.
- Which tests or checks were performed.

Example:

> AI-assisted: AI suggested a small documentation revision and an error-handling example. I reviewed, verified, and edited the changes. Relevant tests were run.

The disclosure must not claim that the work is wholly original or unaided.

### 6. Review and Acceptance

AI-assisted changes require careful human review. Reviewers should evaluate:

- Whether the contribution is accurate and necessary.
- Whether the contributor understands the change.
- Whether the work was independently tested and verified.
- Whether the AI-assisted portions comply with security, privacy, and licensing requirements.

Maintainers may request revisions, additional testing, or clarification. They may reject a contribution that does not meet this policy.

### 7. Confidentiality and Data Protection

Do not submit private, personal, confidential, proprietary, credential, or sensitive information to an AI service unless that use has been explicitly approved.

All use must comply with project security requirements and applicable privacy, confidentiality, and data-handling rules.

### 8. Questions and Exceptions

When uncertain whether a use is minor, appropriate, or permitted, ask a project maintainer before proceeding.

Maintainers may apply this policy to all current and future AI tools at their own discretion
