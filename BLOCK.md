# Better Auth integration

Adds a Better Auth foundation to the generated project, including server configuration, client helpers, and example authentication flows.

## What it does

- Installs and configures Better Auth.
- Adds shared server and client authentication utilities.
- Includes example sign-in, sign-up, and session handling patterns.
- Prepares the project to protect authenticated routes and API endpoints.

## Requirements

- A database supported by the selected Better Auth adapter.
- Environment variables for the application URL and authentication secret.

## Configuration

Set the required authentication environment variables before starting the app. Configure providers, session behavior, and callbacks in the generated Better Auth configuration file.

## After generation

1. Add your production authentication secret and application URL.
2. Configure any OAuth providers you plan to support.
3. Run the required database migration or schema-generation command for your adapter.
4. Review the example routes and apply authorization rules for your application.
