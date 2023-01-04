# Docs reporting

Material for MkDocs is an actively maintained project that we constantly strive
to improve. With a project of this size and complexity, bugs may occur. If you
think you have discovered a bug, you can help us by submitting an issue in our
public [issue tracker], following this guide.

  [issue tracker]: https://github.com/squidfunk/mkdocs-material/issues


### Title

A good title is short and descriptive. It should be a one-sentence executive
summary of the issue, so the impact and severity of the bug you want to report
can be inferred from the title.

| <!-- --> | Example  |
| -------- | -------- | 
| :material-check:{ style="color: #4DB6AC" } __Clear__ | Docs:  
| :material-close:{ style="color: #EF5350" } __Wordy__ | The built-in `typeset` plugin changes the precedence of the nav title over the document headline
| :material-close:{ style="color: #EF5350" } __Unclear__ | Title does not work
| :material-close:{ style="color: #EF5350" } __Generic__ | Bug


### Description

Now, to the bug, you want to report. Provide a clear, focused, specific, and
concise summary of the bug you encountered. Explain why you think this is a bug
that should be reported to Material for MkDocs, and not to one of its
dependencies.[^3] Adhere to the following principles:

  [^3]:
    Sometimes, users report bugs on our [issue tracker] that are caused by one
    of our upstream dependencies, including [MkDocs], [Python Markdown],
    [Python Markdown Extensions] or third-party plugins. A good rule of thumb is
    to change the [`theme.name`][theme.name] to `mkdocs` or `readthedocs` and
    check if the problem persists. If it does, the problem is likely not
    related to Material for MkDocs and should be reported upstream. When in
    doubt, use our [discussion board] to ask for help.

-   __Explain the <u>what</u>, not the <u>how</u>__ – don't explain
    [how to reproduce the bug][Steps to reproduce] here, we're getting there.
    Focus on articulating the problem and its impact as clearly as possible.

-   __Keep it short and concise__ – if the bug can be precisely explained in one
    or two sentences, perfect. Don't inflate it – maintainers and future users
    will be grateful for having to read less.

-   __One bug at a time__ – if you encountered several unrelated bugs, please
    create separate issues for them. Don't report them in the same issue, as
    this makes attribution difficult.

---

:material-run-fast: __Stretch goal__ – if you found a workaround or a way to fix
the bug, you can help other users temporarily mitigate the problem before
we maintainers can fix the bug in our code base.

> __Why we need this__: in order for us to understand the problem, we
> need a clear description of it and quantify its impact, which is essential
> for triage and prioritization.

  [MkDocs]: https://www.mkdocs.org
  [Python Markdown]: https://python-markdown.github.io/extensions/
  [Python Markdown Extensions]: https://facelessuser.github.io/pymdown-extensions/
  [theme.name]: https://www.mkdocs.org/user-guide/configuration/#theme

### Links to the documentation

Of course, prior to reporting a bug, you have read our documentation and
[could not find a working solution][search for solutions]. Please share links
to all sections of our documentation that might be relevant to the bug, as it
helps us gradually improve it.

Additionally, since you have searched our [issue tracker] and [discussion board]
before reporting an issue, and have possibly found several issues or
discussions, include those as well. Every link to an issue or discussion creates
a backlink, guiding us maintainers and other users in the future.

---

__Stretch goal__ – if you also include the search terms you
used when [searching for a solution][search for solutions] to your problem, you
make it easier for us maintainers to improve the documentation.

> __Why we need this__: related links help us better understand what you were
> trying to achieve and whether sections of our documentation need to be
> adjusted, extended, or overhauled.

  [search for solutions]: #search-for-solutions

### Improvement proposals

A minimal reproduction is at the heart of every well-written bug report, as
it allows us maintainers to quickly recreate the necessary conditions to inspect
the bug and quickly find its root cause. It's a proven fact that issues with
concise and small reproductions can be fixed much faster.


> __Why we need this__: if an issue contains no minimal reproduction, or just
> a link to a repository with thousands of files, the maintainers would need to
> invest a lot of time into trying to recreate the right conditions to even
> inspect the bug, let alone fix it.

!!! warning "Don't share links to repositories"

    While we know that it is a good practice among developers to include a link
    to a repository with the bug report, we currently don't support those in our
    process. The reason is that the reproduction which is automatically
    produced by the [built-in info plugin] contains all of the necessary
    environment information that is often forgotten to be included.
    
    Additionally, there are many non-technical users of Material for MkDocs that
    have trouble creating repositories.

  [Create reproduction]: reproduction.md
  [built-in info plugin]: reproduction.md#creating-a-zip-file

### Checklist

Thanks for following the guide and creating a high-quality and complete bug
report – you are almost done. This section ensures that you have read this guide
and have worked to your best knowledge to provide us with everything we need to
know to help you.

__We'll take it from here.__
