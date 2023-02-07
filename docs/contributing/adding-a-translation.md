# Adding a translation

Material for MkDocs supports 50+ languages with the help of community
contributions. Keeping all translations up-to-date requires lot of work, as new 
features or changes always need new translations. For us maintainers, it's 
impossible to update all translations ourselves (we just don't speak 50+ 
languages), therefore, we are grateful for our international supportive 
community. If you would like to help us make Material for MkDocs, even more, 
global and have noticed a missing translation in your language or want to add a 
new one, you can submit your contribution by following this guide.

## Before adding a translation

Given the constant expansion of our project and the frequent translation updates, 
it is important to check the following things before submitting a translation 
contribution.

### Check the list of supported languages

Chances are your language is already supported by Material for MkDocs. Hence, 
before investing your time and contributing a new translation for your language, 
ensure that your language is not already supported by checking the 
[list of supported languages].

[:material-translate-variant:&nbsp; List of supported languages][List of supported languages]{ .md-button .md-button--primary }

  [List of supported languages]: https://squidfunk.github.io/mkdocs-material/setup/changing-the-language/#site-language

Suppose Material for MkDocs already provides support for your language. In that 
case, you can check the completeness of the translations, which are displayed 
below every language in the list, and update them if needed. _Your language is 
not on the list of supported languages?_ You can contribute it by opening a new 
issue and [add a translation] with the help of this guide.

  [Add a translation]: https://github.com/squidfunk/mkdocs-material/issues/new?assignees=&labels=change+request&template=04-add-a-translation.yml&title=Add+translations+for+...


### Search the issue tracker

Our issue tracker might already contain an open issue with a contribution with 
missing translations for your language that still needs to be integrated by us 
maintainers. To avoid investing your time in duplicated work, please search the 
[issue tracker] beforehand.

[:octicons-issue-opened-24:&nbsp; Issue tracker][Issue tracker]{ .md-button .md-button--primary }

  [issue tracker]: https://github.com/squidfunk/mkdocs-material/issues

### Update supported languages

If, after checking the issue tracker, you have found that the missing 
translations for your language haven't been submitted by other users yet, you 
add them by clicking the number of missing translations under each language in 
the [list of supported languages]. This will redirect you to a new issue 
template that will be automatically filled with basic information and have 
highlighted fields that need to be adjusted by you.

 [List of supported languages]: https://squidfunk.github.io/mkdocs-material/setup/changing-the-language/#site-language


## Issue template

We have created a new issue template to make contributing translations for new 
languages as simple as possible. It is the result of our experience with +50
language contributions and updates over the last couple of years. The language 
contribution process was simplified, and the new template consists of the 
following parts:

- [Title]
- [Translations]
- [Country flag] <small>optional</small>
- [Checklist]

  [Title]: #title
  [Translations]: #translations
  [Country flag]: #country-flag
  [Checklist]: #checklist

### Title

Translation issue titles are simple. When adding a new language, the first part 
of the title with "Add translations for..." is already pre-filled in the 
template, and you need to replace the three dots with your language name. If 
adding missing translations for a language from the [list of supported languages], 
the title is already set with no need for adjustment. 

| <!-- --> | Example  |
| -------- | -------- | 
| :material-check:{ style="color: #4DB6AC" } __Clear__ | Add translations for German
| :material-close:{ style="color: #EF5350" } __Unclear__ | Add translations ...
| :material-close:{ style="color: #EF5350" } __Generic__ | German

 [List of supported languages]: https://squidfunk.github.io/mkdocs-material/setup/changing-the-language/#site-language

### Translations

With the preliminary work done, you can now add all missing translations for 
your language. Each label on the right side with the `⬅️ icon` needs to be 
translated. To ensure accuracy, consider double-checking the context of the 
words by looking at the English version. Once you have added the translation, 
delete the `⬅️ icon`.

### Country flag

Now, that you have added translations for a new language, please select the 
appropriate flag for your language from our documentation [Icons, Emojis site] 
by inserting the command `flag_` in the search field.

> __Why this might be helpful__: different countries often have unique 
> linguistic differences, making the flag a useful tool for us maintainers to 
> keep track of the origin of the new translation.

 [Icons, Emojis site]: https://squidfunk.github.io/mkdocs-material/reference/icons-emojis/#search


### Checklist

Thanks for following the guide and creating a high-quality and complete 
translation issue – you are almost done. This section ensures that you have read 
this guide and have worked to your best knowledge to provide us with everything 
we need to know to integrate your contribution to Material for MkDocs.

### Authors credits

We are attributing the authors in the commits without the need of creating a 
pull request. ???

## Adding a translation via pull request 

If you want to integrate the translation yourself, you can also create a pull 
request after filling out the issue template by following this guide.

1.  Fork the repository.

2.  Open the [translation file for your language] as well as the 
    [English translations], as they are always up-to-date.
    
3.  Compare the languages side-by-side and add the missing translations.

    __Important__: add only the translations that are different from the 
    defaults, e.g., if your language is left-to-right, don't add the `direction` 
    translation, as English is left-to-right as well.
    The following translations are for technical purposes, and __should not be 
    updated__, so if they're missing from your language, it's for a good reason:

    - `search.config.lang`
    - `search.config.pipeline`
    - `search.config.separator`

3.  Create a PR (see below) with your changes.

  [translation file for your language]: https://github.com/squidfunk/mkdocs-material/tree/master/src/partials/languages
  [English translations]: https://github.com/squidfunk/mkdocs-material/tree/master/src/partials/languages/en.html






