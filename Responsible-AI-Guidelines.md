# Responsible AI Guidelines

**Purpose**  
This file summarises ethical and safe use of AI in this project.

## Principles
1. **Transparency**
   - Mark clearly which code and documentation were AI-assisted.
   - Include screenshots showing Copilot suggestions and indicate what was accepted.

2. **Accountability**
   - Every AI-generated contribution is reviewed by a human before acceptance.
   - Tests must validate functionality and correctness.

3. **Privacy**
   - Do not paste or expose private data, credentials, or personal identifiable information to AI prompts or generated code.

4. **Safety**
   - Avoid using Copilot to generate unverified security-critical code; review and test thoroughly.
   - Use unit tests and CI to detect regressions.

5. **Bias & Fairness**
   - Ensure documentation or examples do not include biased content.
   - Document any limitations of the generated content.

## How this repo follows these principles
- All Copilot suggestions are saved with screenshots in `/screenshots`.
- The `tests/` suite validates changes and runs in GitHub Actions.
- Sensitive data is never committed (use `.gitignore` for secrets).

