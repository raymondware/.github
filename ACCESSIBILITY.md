# Accessibility

These projects aim to provide documentation, interfaces, and examples that can be used by people with a range of abilities, devices, and input methods.

## Commitments

Where applicable, contributions should:

- Preserve keyboard access and visible focus behavior.
- Avoid relying on color alone to communicate meaning.
- Use readable contrast and scalable text.
- Provide descriptive labels and alternative text for meaningful images.
- Keep documentation structured with clear headings, link text, and code examples.
- Respect reduced-motion and other user preferences when the platform exposes them.
- Avoid introducing unnecessary barriers for screen readers or other assistive technology.

## Supported environments

Accessibility support varies by project and by the host environment, such as a terminal, editor, browser, operating system, or third-party runtime. Each repository's README defines its supported technical environment. Upstream platform limitations may affect what a project can provide directly.

## Known limitations

Not every project has undergone a formal accessibility audit. Terminal applications, editor plugins, generated examples, and older packages may have limitations that are not yet documented.

## Reporting a barrier

Open an issue in the affected repository and apply the `accessibility` label when available. Include:

- The repository, version, or commit
- The task you were trying to complete
- The barrier you encountered
- Relevant browser, editor, terminal, operating system, or assistive technology
- A suggested improvement, if you have one

Do not include private medical information, credentials, or other sensitive data. Accessibility reports are welcome even when the reporter cannot propose a technical fix.
