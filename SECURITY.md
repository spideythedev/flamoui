# Security Policy

## Reporting a Vulnerability

If you discover a security issue, please do NOT open a public issue.

Contact us directly:
- GitHub: [spideythedev](https://github.com/spideythedev)
- Website: [FlamicsLLC](https://flamics-llc.vercel.app)

We will respond within 48 hours.

## Scope

FlamoUI is a CSS framework. Security concerns are limited to:
- CSS injection vectors
- Data exfiltration via CSS
- Accessibility issues that could impact security

## Best Practices

- Always validate user input before rendering with FlamoUI classes
- Use Content Security Policy headers
- Keep your dependencies updated