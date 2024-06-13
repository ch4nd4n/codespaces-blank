# Editing this on GitHub

Monorepo example for [GitHub Codespaces](https://github.com/features/codespaces).

This is a monorepo that contains many sub-projects. Each sub-project could be a library, a website, a CLI tool, or anything else.

## Ok but what on earth is this?

Collection of source code that I try out. Refer to docs/about-source.md for more information.

But in short any self contained project that can be run in a browser or does something useful has a README.md file that explains how to use it.

## How to use

1. Open a terminal in the root of this repository
2. Run `yarn install`
3. Run `yarn start`
4. Open a browser and navigate to `http://localhost:3000`

## How to use this monorepo

1. Open a terminal in the root of this repository
2. Run `yarn install`
3. Run `yarn start`
4. Open a browser and navigate to `http://localhost:3000`

## How to use this monorepo with Codespaces

1. Open a terminal in the root of this repository
2. Run `yarn install`
3. Run `yarn build`
4. Run `yarn start`
5. Open a browser and navigate to `http://localhost:3000`


## Write up on cloudspace

### How it helps

**What is GitHub Codespaces?**

GitHub Codespaces provides a pre-configured development environment, for working on your GitHub repositories. You can start coding right away, without worrying about installing software or configuring your local machine. Codespaces are ideal for:

- **Quick Setup:** No need to install development tools or configure your local environment.
- **Collaboration:** Multiple developers can work on the same codebase simultaneously, regardless of their operating systems or machine configurations.
- **Scalability:** Access powerful computing resources based on your project's requirements.
- **Reproducibility:** Everyone working on the project has the same development environment, ensuring consistent results.

**Getting Started with GitHub Codespaces:**

There are three main ways to create a codespace for a GitHub repository:

1. **From the GitHub Web Interface:**
   - Navigate to the repository you want to work on in GitHub.com.
   - Click on the "Code" button and then select "Codespaces."
   - You can choose to create a codespace from the current branch, the default branch, or a specific branch.

2. **Using the `codespace.new` URL:**
   - In your web browser's address bar, type `codespace.new`. This will automatically create a codespace for the repository you're currently viewing on GitHub.

3. **From the GitHub CLI:**
   - If you have the GitHub CLI installed, you can use the `gh codespace` command to create a codespace for a repository.

**Once you've created a codespace, you can connect to it in two ways:**

1. **In the Browser:** GitHub Codespaces provides an integrated browser-based IDE experience, allowing you to code directly within your web browser.
2. **Using a Local IDE:** You can connect your preferred local IDE (like Visual Studio Code, JetBrains IDEs, etc.) to your codespace for a more familiar development experience.

**Additional Considerations:**

- **Free Tier:** GitHub offers a free tier for Codespaces, providing a limited amount of storage and compute time per month for personal accounts. You can find more details about pricing on the GitHub Docs [https://docs.github.com/billing/managing-billing-for-github-codespaces/about-billing-for-github-codespaces](https://docs.github.com/billing/managing-billing-for-github-codespaces/about-billing-for-github-codespaces).
- **Customization:** You can customize the development environment in your codespace using dev containers, allowing you to pre-install specific tools and libraries needed for your project.
