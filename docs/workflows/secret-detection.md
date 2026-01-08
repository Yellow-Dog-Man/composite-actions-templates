# Secret Detection

This workflow runs secret detection on the target repository.

Due to the nature of reusable workflows, you will need to specify `secrets: inherit` when calling it for GitLeaks to find the license key.

::: .github/workflows/secret-detection.yml
