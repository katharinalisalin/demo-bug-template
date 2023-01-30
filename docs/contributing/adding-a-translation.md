# Adding a translation

Material for MkDocs supports 50+ languages with the help of community
contributions. When new features are released, new translations are required, 
which means translations need to be constantly updated. For us maintainers it's 
impossible to update all translations ourselfes (we just don't speak 50+ 
languages), so we rely on contributors to update translations incrementally.

If you find a translation missing in your language or want to add new language,
we have created a process which gives you two options:

Test


if  follow 
these guidelines:

If you find a missing translation in your language, please follow these guidelines to assist in the process:

1.  Fork the repository.

2.  Open up the [translation file for your language] as well as the
    [English translations], as they are always up-to-date.
    
3.  Compare the languages side-by-side and add the missing translations.

    __Important__: add only the translations that are different from the 
    defaults, e.g., if your language is left-to-right, don't add the `direction` 
    translation, as English is left-to-right as well.
    The following translations are for technical purposes and __should not be 
    updated__, so if they're missing from your language, it's for a good reason:

    - `search.config.lang`
    - `search.config.pipeline`
    - `search.config.separator`

3.  Create a PR (see below) with your changes.

  [translation file for your language]: https://github.com/squidfunk/mkdocs-material/tree/master/src/partials/languages
  [English translations]: https://github.com/squidfunk/mkdocs-material/tree/master/src/partials/languages/en.html






