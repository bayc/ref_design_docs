### Making Changes

1. **Create a New Branch**: For each new change, create a separate branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
2. **Add or Update Files**: Make your changes to the reference files as needed.

3. **Commit Your Changes**: Commit your changes with a clear, descriptive message:
   ```bash
   git add .
   git commit -m "Add/update reference file for [specific purpose]"
   ```

4. **Push Your Changes**: Push your branch to your fork:
   ```bash
   git push origin feature/your-feature-name
   ```

### Adding Tests

- **Test Files**: If your changes involve adding or modifying files that could benefit from automated tests (e.g., validation scripts for file formats), include test files in the `tests/` directory within the repository (see [Organization](#organization)).
  
- **Test Instructions**: Add instructions for running tests in a `README.md` or a `TESTING.md` file if appropriate. Ensure your tests are clear, reproducible, and relevant to the changes made.

### Creating a Pull Request

1. Go to your repository on GitHub.
2. Click the **Compare & pull request** button next to your branch.
3. Provide a detailed description of the changes you made, including any relevant context and test results.
4. Submit the pull request.

### Review and Merge Process

- **Review**: Repository maintainers will review your pull request, check for any issues, and provide feedback if necessary.
- **Merge**: Once approved, your changes will be merged into the main branch.

### Code of Conduct

We strive to maintain a positive and respectful community.