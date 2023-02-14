# Submitting a Pull Request (PR)

Material for MkDocs is a project that is driven by "hero developers", 80% of the 
contributions come from less than 20% of the developers.


pull request, short PR, is a proposed code chjange 


When submitting a Pull Request, please make sure that your contribution follows 
these guidelines:

- [x] Your code is properly formatted and follows the existing code style.
- [x] Your changes are well-documented, with clear explanations of what the code does and why it is necessary.
- [x] Your Pull Request includes test cases that confirm the correct functioning of the code.

Please also note that all contributions are subject to review and may not be accepted if they do not meet the project's standards or goals.


## Want to contribute and submit a pull request (PR)

Search GitHub for an open or closed PR that relates to your submission. You
don't want to duplicate effort. If you do not find a related issue or PR,
go ahead.

1.  **Development**: Fork the project, set up the [development environment],
    make your changes in a separate git branch and add descriptive messages to
    your commits.

2.  **Build**: Before submitting a pull request, [build the theme]. This is
    a mandatory requirement for your PR to get accepted, as the theme should be 
    installable through GitHub at all times.

3.  **Pull Request**: After building the theme, commit the compiled output,
    push your branch to GitHub and send a PR to `mkdocs-material:master`. If we
    suggest changes, make the required updates, rebase your branch and push the
    changes to your GitHub repository, which will automatically update your PR.

After your PR is merged, you can safely delete your branch and pull the changes
from the main (upstream) repository.

  [development environment]: https://squidfunk.github.io/mkdocs-material/customization/#environment-setup
  [build the theme]: https://squidfunk.github.io/mkdocs-material/customization/#building-the-theme

