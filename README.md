# Brainions Website

This is the source code for the Brainions website.

## Deployment

This website is configured to be deployed to GitHub Pages using GitHub Actions.

### Setup Instructions

1.  **Enable GitHub Pages**:
    *   Go to your repository on GitHub.
    *   Navigate to **Settings** -> **Pages**.
    *   Under **Build and deployment** -> **Source**, select **GitHub Actions**.

2.  **Trigger Deployment**:
    *   Any push to the `main` branch will automatically trigger the deployment workflow.
    *   You can check the progress in the **Actions** tab of your repository.

### Workflow

The deployment workflow is defined in `.github/workflows/static.yml`. It handles:
*   Checking out the code.
*   Setting up the Pages environment.
*   Uploading the artifact.
*   Deploying existing static content to GitHub Pages.
