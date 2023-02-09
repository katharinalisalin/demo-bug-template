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

### List of supported languages

Chances are your language is already supported by Material for MkDocs. Therefore, 
before investing your time and contributing a new translation, ensure that your 
language is not included in the [list of supported languages].

[:material-earth-plus:&nbsp; Search for your language][Search for your language]{ .md-button .md-button--primary }

  [list of supported languages]: https://squidfunk.github.io/mkdocs-material/setup/changing-the-language/#site-language
  [Search for your language]: https://squidfunk.github.io/mkdocs-material/setup/changing-the-language/#site-language

If your language is already supported, you can review the completeness of the 
translations, which are displayed below each language in the list. If any 
updates are needed, you can make the necessary changes.

If your language is not on the list of supported languages, you can contribute 
by opening a new issue and [adding a translation] with the help of the provided 
guide.

Please note that we grouped languages. If you would like to add specific 
linguistic variations for your country, please open a new issue and include your 
country's flag along with the details.

  [Add a translation]: https://github.com/squidfunk/mkdocs-material/issues/new?assignees=&labels=change+request&template=04-add-a-translation.yml&title=Add+translations+for+...

### Issue tracker

Our issue tracker might already contain an open issue with a contribution with 
missing translations for your language that still needs to be integrated by us 
maintainers. To avoid investing your time in duplicated work, please search the 
[issue tracker] beforehand.

[:octicons-issue-opened-24:&nbsp; Search our issue tracker][Search our issue tracker]{ .md-button .md-button--primary }
  
  [issue tracker]: https://github.com/squidfunk/mkdocs-material/issues
  [search our issue tracker]: https://github.com/squidfunk/mkdocs-material/issues


### Update supported languages

If, after checking the issue tracker, you have found that the missing 
translations for your language haven't been submitted by other users yet, you 
add them by clicking the number of missing translations under each language in 
the [list of supported languages]. This will redirect you to a new issue 
template that will be automatically filled with basic information and have 
highlighted fields that need to be adjusted by you.

[:material-translate-variant:&nbsp; Add missing translations][Update your translations]{ .md-button .md-button--primary }

 [List of supported languages]: https://squidfunk.github.io/mkdocs-material/setup/changing-the-language/#site-language
 [Update your translations]: https://squidfunk.github.io/mkdocs-material/setup/changing-the-language/#site-language

---

At this point, when you have made sure, that Material for MkDocs doesn't support
language already, you can add translations for your language by following the 
issue template.

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
your language. Each label on the right side containing the `⬅️ icon` is missing 
a translation. To ensure accuracy of your translation, consider double-checking 
the context of the words by looking at the [English version].

[English version]: https://github.com/squidfunk/mkdocs-material/tree/master/src/partials/languages

#### Translation context



After adding the translation, remove the `⬅️ icon` from each translated line. If 
you couldn't find translations for some required fields, simply leave them for 
other contributors to complete.

### Country flag

Now, that you have contributed translations for a new language, please select 
the appropriate flag for your language from our documentation's [Icons, Emojis site] 
by entering the command `flag` in the search field.

!!! warning "Icon limitation by Twemoji"

    Please note that only icons provided by Twemoji can be used. If your flag is 
    not available on the list on the [Icons, Emojis site], choose an alternative 
    or leave the field empty.

> __Why this might be helpful__: providing us with the correct country flag 
> helps us to integrate the new language to the list of supported languages
> faster and easier as we spend less time searching. 

 [Icons, Emojis site]: https://squidfunk.github.io/mkdocs-material/reference/icons-emojis/#search

### Checklist

Thanks for following the guide and creating a high-quality and complete 
translation issue – you are almost done. This section ensures that you have read 
this guide and have worked to your best knowledge to provide us with everything 
we need to know to integrate your contribution to Material for MkDocs.

### Authors credits

Authors who submit a translation using the template above will be 
__credited as co-authors__ in commits for Material for MkDocs. To list your 
account as a co-author without knowing or revealing your email address, we will 
use your GitHub-provided no-reply email, following 
[GitHub's recommended workaround], to protect your privacy. This way, your 
commit will count as a contribution without the need to open a pull request.

 [GitHub's recommended workaround]: https://docs.github.com/en/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/creating-a-commit-with-multiple-authors

## Committing new translations via PR

If you want to contribute missing translations for a new or supported language 
by creating a pull request in order to be listed as the solo author on the 
commit, you can open it after submitting the translation issue. Ensure that you 
thoroughly read the pull request guide below to prevent breaking functionality 
in the translation file.

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



Twemoji, which we take the flags from, does not provide a Catalan flag, which is why we've chosen the closest option that is the Spanish flag (go to our icon search and search for flag). We're aware that this is not perfect, but it's only meant for visual orientation. It's not political by any means. We'll add a note to the documentation.


