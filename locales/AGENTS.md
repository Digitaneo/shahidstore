# Project Instructions

## Shopify
- Use the current Shopify APIs and documentation.
- Prefer GraphQL Admin API where applicable.
- Follow Shopify's current app architecture.
- Do not use deprecated APIs without explicit approval.

## Theme
- Follow Online Store 2.0 architecture.
- Preserve existing section schema settings.
- Do not remove existing settings unless explicitly requested.
- Keep Liquid modular.
- Keep JavaScript and CSS modular.

## Code
- Use TypeScript where applicable.
- Do not introduce unnecessary dependencies.
- Follow the existing project conventions.

## Git
- Never reset, delete, or overwrite user changes.
- Never force-push.
- Before large changes, explain the planned changes.

## Validation
- Run the appropriate tests.
- Run lint/type checking.
- Run Shopify validation where applicable.
- Fix errors before reporting the task as complete.

## Security
- Never expose API keys or secrets.
- Never commit .env files.
- Never hardcode credentials.