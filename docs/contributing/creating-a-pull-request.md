# Submitting a pull request (PR)



pull request, short PR, is a proposed code change 

Small features and bugs can be crafted and directly submitted as a Pull Request. 
However, there is no guarantee that your feature will make it into the master, 
as it's always a matter of opinion whether if benefits the overall functionality 
of the project.


## Before opening a pull request

### When should I open a pull request?

With more than 20.000 users, issues are created every other day. The maintainers
of this project are trying very hard to keep the number of open issues down by
fixing bugs as fast as possible. By following this guide, you will know exactly
what information we need to help you quickly.

__But first, please follow these steps before opening a pull requesr.__

### Start searching

Now, before you go through the trouble of creating a pull request that is
answered and closed right away with a link to relevant documentation section or
another already reported or closed issue or discussion, you can save time for
us and yourself by doing some research:

1.  [Search our documentation][documentation] and look for the relevant sections 
    that could be related to your pull request.

2.  [Search our pull requests][pull request] to learn if other users
    may have had similar ideas and created pull requests. Find out if they got 
    merged or why they got denied.

3.  [Search our issue tracker][issue tracker], as another user might already
    have suggested the same issue and may be working on a solution or found 
    another workaround.

4.  [Search our discussion board][discussion board] read about other approaches 
    or exchange ideas with the community.

__Keep track of all <u>search terms</u> and <u>links</u>, to add mention them 
in the pull request description
them in the bug report.__

  [documentation]: https://squidfunk.github.io/mkdocs-material/
  [pull request]: https://github.com/squidfunk/mkdocs-material/pulls
  [issue tracker]: https://github.com/squidfunk/mkdocs-material/issues
  [discussion board]: https://github.com/squidfunk/mkdocs-material/discussions

### Get in contact


### Keep in mind 

#### Code style and format


#### Code documentation

#### Test cases

---

At this point, when you completed the search, contacted us to discuss your 
pull request, and would like to create a pull request, please make sure you 
comply with the following pull request guide.


## 

Material for MkDocs is a project that is driven by "hero developers", 80% of the 
contributions come from less than 20% of the developers.



## Pull request guide

We have created a new issue template to make the pull request as simple
as possible and more efficient for the community and us. It is the result of
our experience answering and fixing more than 1,600 issues (and counting) and
consists of the following parts:

- [Branch name]
- [Context] <small>optional</small>
- [Description]
- [Related issues and discussions]

  [Branch name]: #branch-name
  [Context]: #context
  [Description]: #description
  [Related issues and discussions]: #related-issues-and-discussions

### Branch name

When you create a pull request, the name of the branch will be authomatically 
set as the title of the pull request. good title is short and descriptive. This
is why it is important to 

| <!-- --> | Example  |
| -------- | -------- | 
| :material-check:{ style="color: #4DB6AC" } __Clear__ | Built-in `typeset` plugin changes precedence of nav title over `h1`
| :material-close:{ style="color: #EF5350" } __Wordy__ | The built-in `typeset` plugin changes the precedence of the nav title over the document headline
| :material-close:{ style="color: #EF5350" } __Unclear__ | Title does not work
| :material-close:{ style="color: #EF5350" } __Generic__ | Please help

### Context <small>optional</small>
### Description
### Related issues and discussions


### How to create a pull request

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

## Checklist

When submitting a Pull Request, please make sure that your contribution follows 
these guidelines:
Make sure that your

- [x] ...code is properly formatted and follows the existing code style.
- [x] ...changes are well-documented, with clear explanations of what the code does and why it is necessary.
- [x] ...pull request includes test cases that confirm the correct functioning of the code.

Please also note that all contributions are subject to review and may not be 
accepted if they do not meet the project's standards or goals.

## Declined and closed PRs














If you want to contribute missing translations by creating a pull request to be 
listed as the sole author of the commit, you can open a PR after submitting the 
translation issue. Ensure you thoroughly read the pull request guide below to 
prevent breaking functionality in the translation file.

1.  Fill out a [translation issue] according to the guide and submit it in the 
    [issue tracker].

2.  Tick the box for the last point in the "Before submitting..." section.
    - [x]  __Optional__: I want to integrate this translation myself and create a 
            pull request following the [contribution guide](https://github.com/squidfunk/mkdocs-material/blob/master/CONTRIBUTING.md).

3.  Fork the Material for MkDocs repository, set up a [development environment] 
and create a separate git branch on which you make all your changes.

4.  Please review all [existing language files] in the repository and search for 
your language. If a file for your language already exists, please use it for 
your edits or create a new file if your language is not listed by copying one of 
the existing files.
    
5.  Add the missing translations for your language to the best of your knowledge
    and save the changes.

    !!! warning "Important"
        Only add the translations that are different from the defaults. For 
        example, if your language is left-to-right, don't add the `direction` 
        translation, as English is also left-to-right. The following 
        translations are for technical purposes, and __should not be updated__. 
        If they're missing from your language, it's for a good reason:

        - `search.config.lang`
        - `search.config.pipeline`
        - `search.config.separator`

6.  Open the [English translations] file and compare your translations with the 
    up-to-date English translations file. 

7.  Before submitting a pull request, build the theme. This is a mandatory 
requirement for your PR to get accepted, as the theme should be installable 
through GitHub at all times.

8.  After building the theme, commit the compiled output, push your branch to 
GitHub and send a PR to mkdocs-material:master. If we suggest changes, make the 
required updates, rebase your branch, and push the changes to your GitHub 
repository, which will automatically update your PR.

9. After your PR is merged, you can safely delete your branch and pull the 
changes from the main (upstream) repository.
