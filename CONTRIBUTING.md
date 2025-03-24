# Contributing to Drippigg

Thank you for your interest in contributing to **Drippigg**! We welcome contributions that help improve our developer tools for game development.

## How to Contribute

### 1. Reporting Issues
If you encounter a bug, security vulnerability, or have a feature request, please open an issue in the repository. When submitting an issue:
- Provide a clear and concise title.
- Describe the problem or feature request in detail.
- Include steps to reproduce (if applicable).
- Attach relevant logs or screenshots.

### 2. Submitting Code Contributions
We accept pull requests (PRs) that improve the project. Follow these steps to contribute:

#### **Fork & Clone**
1. Fork the repository.
2. Clone your fork locally:
   ```sh
   git clone https://github.com/your-username/drippigg.git
   cd drippigg
   ```
3. Create a new branch for your changes:
   ```sh
   git checkout -b feature/your-feature-name
   ```

#### **Make Changes & Commit**
1. Write clean, well-documented code following project guidelines.
2. Run tests and ensure nothing is broken.
3. Commit with a meaningful message:
   ```sh
   git commit -m "feat: add new feature description"
   ```
4. Push to your fork:
   ```sh
   git push origin feature/your-feature-name
   ```

#### **Submit a Pull Request**
1. Open a pull request (PR) against the `main` branch.
2. Fill in the PR template and link any relevant issues.
3. Wait for a review and make requested changes if necessary.

## Code Style & Standards
- Follow the **Go** and **JavaScript/TypeScript** best practices.
- Use **ESLint** and **Prettier** for JavaScript/TypeScript formatting.
- Keep code modular and well-commented.
- Follow commit message conventions (e.g., Conventional Commits: `feat:`, `fix:`, `docs:`).

## Branching Strategy
- `main` – Stable production-ready code.
- `dev` – Active development branch.
- `feature/*` – New feature branches.
- `fix/*` – Bugfix branches.

## Testing
- Ensure your code passes existing tests.
- Add new tests if introducing a feature or fixing a bug.
- Use Jest (for JS/TS) and Go testing libraries for unit tests.

## Communication
- Join our [Discord](#) for discussions.
- Reach out via GitHub Discussions or Issues for questions.

We appreciate your contributions and look forward to building amazing developer tools together! 🚀
