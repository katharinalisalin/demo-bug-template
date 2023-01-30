# Adding a translation

Material for MkDocs supports 50+ languages with the help of community
contributions. When new features are added, sometimes, new translations are
necessary as well. It's impossible for us maintainers of the project to update
all translations ourselfes (we just don't speak 50+ languages), so we have to 
rely on our contributors to update translations incrementally. This process is 
pretty simple, so if you find a translation missing in your language, follow 
these guidelines:

If you find a missing translation in your language, please follow these guidelines to assist in the process:

1.  Fork the repository.

2.  Open up the [translation file for your language] as well as the
    [English translations], as they are always up-to-date.
    
3.  Compare the languages side-by-side and add the missing translations.

    __Important__: add only the translations that are different from the 
    defaults, e.g., if your language is left-to-right, don't add the `direction` 
    translation, as English is left-to-right as well.
    The following translations are for technical purposes and should not be 
    updated, so if they're missing from your language, it's for a good reason:

    - `search.config.lang`
    - `search.config.pipeline`
    - `search.config.separator`

3.  Create a PR (see below) with your changes.

  [translation file for your language]: https://github.com/squidfunk/mkdocs-material/tree/master/src/partials/languages
  [English translations]: https://github.com/squidfunk/mkdocs-material/tree/master/src/partials/languages/en.html






