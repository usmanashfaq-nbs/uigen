Run a full npm security audit and fix cycle:

1. Run `npm audit` and report any vulnerabilities found (severity, package name, and advisory).
2. Run `npm audit fix` to apply safe, non-breaking updates.
3. Run `npm test` to verify the fixes didn't break anything.
4. Report a summary: how many vulnerabilities were found, how many were fixed, and whether tests passed.
