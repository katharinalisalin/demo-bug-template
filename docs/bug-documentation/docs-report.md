# Docs reporting

The documentation for Material for MkDocs contains over 20+ sites with information 
about our features, configurations, and everything you need to take advantage of 
Material for MkDocs's full capabilities. If you think you have discovered a bug 
in the docs or feel the need of improvement, you can help us by submitting an 
issue in our public [issue tracker], following this __docs reporting guide__.
  [issue tracker]: https://github.com/squidfunk/mkdocs-material/issues


## Docs issue template

Reporting a bug in the documentation differs from reporting a bug in the code; 
we, therefore, ask you to read the following docs-reporting-guide thoroughly 
before creating a new and helpful issue to report a bug in the docs.

### Title

A great issue title should be a short, one-sentence desbription of the bug and 
contain all information relevant to the bug. When reporting a bug in the 
documentation, the issue name should start with "Docs:" and including all 
relevant keywords. This makes search for relevant bug reports in the issue 
tracker faster for the community.

| <!-- --> | Example  |
| -------- | -------- | 
| :material-check:{ style="color: #4DB6AC" } __Clear__ | Docs: wrong feature flag code.action
| :material-close:{ style="color: #EF5350" } __Unclear__ | Bug in Documentation
| :material-close:{ style="color: #EF5350" } __Generic__ | Bug

### Description

Provide a clear and concise summary of the bug you encountered in the 
[Material for MkDocs documentation](https://squidfunk.github.io/mkdocs-material).
Explain why you think the documentation contains a bug or needs improvement. 
Furthermore, explain its impact. 

-   __Keep it short and concise__ – if the bug and it's impact can be precisely 
    explained in one or two sentences, perfect. Don't inflate it – maintainers 
    and future users will be grateful for having to read less.

-   __One bug at a time__ – if you encountered several unrelated bugs on 
    different sites of the documentation, please create separate issues for them. 
    Don't report them in the same issue, as this makes attribution difficult.

> __Why we need this__: in order for us to understand the problem you have found 
> or the clarification the documentation needs, we ask for a decription of the bug.


### Links to the documentation

Now, provide the link to the section of the documentation you decribed above and 
Make sure you link the subpages and anchor the headings directly.

> __Why we need this__: providing the links to the documentation help us 
> understand which sections of our documentation need to be adjusted, extended, 
> or overhauled.

  [search for solutions]: #search-for-solutions

### Improvement proposals



---

:material-run-fast: __Stretch goal__ – if you found a workaround or a way to fix
the bug, you can help other users temporarily mitigate the problem before
we maintainers can fix the bug in our code base.


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
