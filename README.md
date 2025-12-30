Tech stack:
frontend:
  framework: React
  language: TypeScript
  styling: TailwindCSS

backend:
  language: Java
  framework: Spring

database:
  primary: PostgreSQL

infra:
  cloud: AWS
prompts
When generating code:

    Prefer existing patterns
    Keep functions small
    Match naming conventions exactly
    Reference colors.json for UI work
    Always use primary color for main CTA
    No gradients
    Rounded-md only
    Icons on the left
    Disabled state must reduce opacity

framework
{
  "framework": "react",
  "language": "typescript",
  "styling": "tailwind"
}

Colors to be used:
{
  "primary": "#257DF0",
  "secondary": "#1C1D21",
  "danger": "#F33A3A",
  "background": "#FFFFFF",
  "textTitle": "#2F3034",
  "textContent": "#767678",
  "hyperlink" : "#1557AF"
}


