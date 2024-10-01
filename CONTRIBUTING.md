# Contributing to pyserial

Thank you for considering contributing to this fork of pyserial! This guide will help you get started with making minor updates and bugfixes to pyserial.

## Getting Started

To contribute to the fork you will need to have a basic understanding of Python and Git. If you are new to either of these, we recommend checking out the official documentation and tutorials to get started.

## Types of contributions accepted

The most important thing to keep in mind about contributing to this fork is that we will *not* be merging any major functional changes to pyserial. The objective is to allow the following types of changes only:
    - bugfixes (anything that fixes an existing functionality of pyserial without significantly modifying the feature)
    - documentation fixes
    - repository management updates (like adding to the CI/CD pipeline)
    - unit tests (for any features/cases not already covered)
    - updates to maintain compatibility (with, ofr example, new versions of python, or new versions of a supported operating system)

This will ultimately make getting these changes introduced into the main project easier, and lower risk. Please keep this in ming before submitting an issue, or PR.

## Making Changes

Once you have cloned the repository, you can start making changes to pyserial. Here are the steps to follow:

1. Clone your cloned repository to your local machine using the following command:
    ```
    git clone https://github.com/prosaicpudding/pyserial.git
    ```

2. Create a new branch for your changes. It is recommended to use a descriptive branch name that reflects the nature of your changes. For example:
    ```
    git checkout -b bugfix-serial-read
    ```

3. Make the necessary updates and bugfixes to the codebase.

4. Test your changes to ensure they work as expected.

5. Commit your changes with a clear and concise commit message:
    ```
    git commit -m "Fix issue with serial read function"
    ```

6. Push your changes to your forked repository:
    ```
    git push origin bugfix-serial-read
    ```

## Submitting a Pull Request

Once you have made your changes and pushed them to your forked repository, you can submit a pull request to the original pyserial repository. This will notify the original maintainers of your changes and allow them to review and merge your code.

1. Navigate to your forked repository on GitHub.

2. Click on the "New pull request" button.

3. Select the branch containing your changes from the "base" dropdown menu. This should be the branch you want to merge into the original repository.

4. Provide a clear and concise title and description for your pull request, explaining the changes you have made.

5. Click on the "Create pull request" button to submit your request.

## Conclusion

By following these guidelines, you can contribute to pyserial by making minor updates and bugfixes until the original maintainers return to the project. Your contributions are greatly appreciated and will help ensure the continued success of pyserial.

Thank you for your support!
