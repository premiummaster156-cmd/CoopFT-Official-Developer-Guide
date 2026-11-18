# Security and Delivery

## Credentials
- Never request tokens, passwords, private API keys, or database passwords in public channels.
- Do not place secrets in source files, screenshots, logs, commits, or ZIP archives.
- Use environment variables and provide an `.env.example` with placeholder names only.
- If a secret is exposed, tell the customer to rotate it and notify the project lead.

## Data
Use only customer data required for the project. Do not publish, reuse, or disclose private customer data or source code without permission.

## Discord permissions
Request only permissions and gateway intents required by agreed features. Explain privileged intents or powerful permissions. Never build hidden backdoors or undocumented owner access.

## Delivery checklist
- Source matches approved scope.
- Dependencies and runtime are documented.
- Setup instructions are included.
- Environment variable names are listed without secret values.
- Database setup/migrations are included where needed.
- Important workflows are tested.
- Known limitations are disclosed.
- ZIP contains no credentials or unrelated private files.

## Current service limitation
The commissioned deliverable is a source-code ZIP with setup notes. Hosting, deployment, and 24/7 operation are not included unless Owner Rank officially changes the service.

## Security incident
Stop work on the affected area, preserve relevant technical details, avoid public disclosure, and notify the authorized project lead.
