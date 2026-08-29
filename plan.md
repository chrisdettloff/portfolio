# Portfolio Site Improvement Plan

## Goal

Turn the current one-page résumé-style site into a portfolio that clearly communicates Chris Dettloff's cloud engineering value, demonstrates real-world work, and gives visitors an obvious way to make contact.

## Priority 1: Improve the professional message

- Rewrite the hero tagline to emphasize outcomes, not only AWS and GCP familiarity.
- Replace the first-person summary with a concise value proposition focused on cloud infrastructure, automation, reliability, security, or developer enablement.
- Add a prominent contact area with email, LinkedIn, GitHub, résumé, or other relevant professional links.
- Remove the tagline emojis or reserve them for the interests section to preserve a consistent professional tone.
- Update the page title and meta description to include the professional role and specialization.

## Priority 2: Add evidence of experience

### Selected projects

Add two or three project case studies. Each project should include:

- Project name and one-sentence overview
- The problem or goal
- Chris's role and contribution
- Technologies used
- Architecture, automation, or implementation details
- A measurable result where possible
- Links to source code, diagrams, demos, or write-ups

### Professional experience

Add a selected experience section with company, role, dates, and achievement-oriented bullets. Focus on outcomes such as:

- Infrastructure provisioning time reduced
- Deployment frequency or reliability improved
- Cloud cost or operational overhead reduced
- Security or compliance improvements
- Developer productivity increased

## Priority 3: Refine the skills and certifications content

- Group skills by capability: cloud platforms, infrastructure and automation, containers, CI/CD, observability, security, networking, and systems administration.
- Distinguish primary strengths from supporting or familiar technologies.
- Use consistent capitalization: GitHub, PowerShell, CloudWatch, 3D printing, and similar product names.
- Add text labels alongside certification badges.
- Include certification issue and expiration dates when applicable.
- Keep certifications after experience and projects so they support the evidence rather than lead it.

## Priority 4: Improve navigation and page structure

Organize the page in this order:

1. Hero and contact links
2. Professional summary
3. Selected projects
4. Professional experience
5. Skills
6. Certifications
7. Interests
8. Contact/footer

- Add simple navigation links to major sections if the page becomes longer.
- Use semantic structure: `header`, `main`, `section`, and `footer`.
- Use `h1` for the name and `h2` for primary section headings.
- Add meaningful IDs and accessible labels to sections and links.

## Priority 5: UI, accessibility, and polish

- Add visible keyboard focus styles to all links and interactive elements.
- Improve contrast for muted subtitle and footer text.
- Add descriptive link text and preserve meaningful alternative text for images.
- Add `rel="noopener noreferrer"` to external links opened in a new tab.
- Add a favicon and Open Graph metadata for better browser and social sharing previews.
- Consider project cards, architecture diagrams, or other lightweight visuals to make the page feel like a portfolio.
- Keep the layout responsive and ensure contact actions remain easy to tap on mobile.
- Update the footer year from the hard-coded value to the current year or a dynamic value.

## Cleanup

- Remove unused timeline CSS (`.ico`, `.desc`, `.timespan`, and `.entry-dot`) unless an experience timeline will be implemented.
- Keep the interests section short and secondary to professional content.
- Avoid listing every technology with equal emphasis; prioritize the tools supported by projects and experience.

## Suggested implementation sequence

1. Rewrite the hero, summary, and metadata.
2. Add contact and social links.
3. Add project case studies and professional experience.
4. Reorganize skills and certifications.
5. Add semantic markup and navigation.
6. Apply accessibility, responsive, and metadata polish.
7. Review the finished page on desktop, mobile, keyboard-only navigation, and a contrast checker.

## Definition of done

- A visitor can understand the role, specialty, and value proposition within a few seconds.
- The page contains at least two concrete examples of cloud engineering work.
- Visitors can reach Chris through at least one prominent professional contact method.
- Skills are curated and supported by project or experience evidence.
- The page is responsive, keyboard navigable, semantically structured, and free of stale or unused content.
