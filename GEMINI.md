# Workspace Rules

Write simple, readable, and highly debuggable code. Prefer clarity over cleverness. Avoid unnecessary abstraction, deep nesting, and magic. Every function should do one clear thing and be easy to step through in a debugger.

Always keep documentation up to date. When using external libraries or frameworks, pull the latest official documentation via Context7 before writing or modifying related code. Never rely on outdated knowledge for APIs, configuration, or best practices.

## Additional Principles

- Prefer explicit over implicit
- Handle errors early and clearly
- Keep functions and files small
- Write code that is easy to delete later
- Add useful comments only when the “why” is not obvious
- Favor standard library solutions when they are good enough
- Make the happy path obvious and the error paths visible
- Optimize for the next person who has to read or debug this (including future you)

When in doubt, choose the simpler solution that is still correct and maintainable.
