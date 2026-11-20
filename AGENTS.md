# NavBot documentation

## Project

- This is the independent NavBot documentation site, built with Mintlify.
- Pages use MDX with YAML frontmatter; site configuration lives in `docs.json`.
- Keep the `mint` theme and existing purple palette unless asked to change the visual style.
- Brand and product facts come from https://navbot.com/ and its official product pages.

## Terminology and content

- Use `NavBot` for the brand and the exact published names for individual robots.
- Write public documentation in English, using active voice and concise sentences.
- Use sentence case for headings and start body headings at `##`.
- Keep internal links root-relative and omit `.mdx` from navigation paths.
- Route support and sales links to `mailto:sales@navbot.com`.
- Do not invent API endpoints, installation commands, specifications, compatibility, or product availability.
- Verify model-specific information against that product's official resources.
- Keep Mintlify authoring instructions in README.md rather than public product pages.

## Verification

- Run `mint instructions` before Mintlify work. If unsupported, use `npx mint@latest instructions`.
- Run `mint validate` after changing configuration or MDX.
- Run `mint broken-links` after adding, moving, or removing links or pages.
- Preview changes with `mint dev` and check navigation, images, and support links.
