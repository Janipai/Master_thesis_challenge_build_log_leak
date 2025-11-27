# challenge-build-log-leak

```md
# Description of the challenge (copy from readme.md)

  The user needs to look at 

  **Prerequisites**

  - Know or have heard about 
  - Be familiar and comfortable with 

  **Outcome**

  - Learn how to 

## GitHub Actions

- Workflows must be placed in the `.github/workflows/` directory to be detected by GitHub Actions. If a workflow file is located elsewhere (for example `workflows/` at the repository root), GitHub will not find it and the Actions tab will show "no workflows found".
- This repository contains a demo workflow `ctf-leak.yml` which demonstrates how secrets can leak if logs include non-masked values; the workflow lives in `.github/workflows/` so it can be executed.

## Security note

- Do not store real secrets in `.env` files committed to the repository. This repository includes an example `.env` with dummy data for demo purposes.
