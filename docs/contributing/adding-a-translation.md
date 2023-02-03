# Adding a translation

Material for MkDocs supports 50+ languages with the help of community
contributions. Keeping all translations up-to-date is crucial, as new features 
or changes often require new translations. For us maintainers it's impossible to 
update all translations ourselfes (we just don't speak 50+ languages) and are 
greateful for our international community.

If you would like to help us make Material for MkDocs even more international 
and have noticed a missing translation in your language or want to add a new 
one, we have updated our process, to simplify contributions. Just follow our 
contribution template to submit new translations.

## Before adding a translation

Given the constant expansion of our project and the frequent translation updates, 
it is important to check the following things before submitting a translation 
contribution.

### Check the list of supported languages

Chances are that your language is already supported by Material for MkDocs.
Thus, before contribution a new tranlation for your language, ensure that your 
language is not already supported. Please check the [list of supported languages] 
to avoid duplicated work. 

[:material-translate-variant:&nbsp; List of supported languages][List of supported languages]{ .md-button .md-button--primary }

  [List of supported languages]: https://squidfunk.github.io/mkdocs-material/setup/changing-the-language/#site-language

### Search the issue tracker

The issue tracker might already contain an open issue with a translation 
contribution for your language, that has not yet been integrated by us 
maintainers. Therefore, you can avoid investing your time in duplicated work,
when chec 

Search our issue tracker, as another user might already have submitted 
the same translations for your language which we maintainers have not yet had a chance to 
release. Thus, no need to create a new issue and add new translations.

### Update a supported languages

If you would like to update translations for your language which is already 
supported 


and you would like to add the missing 
translations which are listed underneath each language, you can do so by 
clicking on "...translations missing". The issue template will automatically 
filled out and highlight all missing translations.


## Issue template

Opening a translation issue

- [Title]
- [Translations]
- [Country flag] <small>optional</small>
- [Checklist]

  [Title]: #title
  [Translations]: #translations
  [Country flag]: #country-flag
  [Checklist]: #checklist


https://squidfunk.github.io/mkdocs-material/setup/changing-the-language/#site-language



### Title

Add translations for ...

Update ... translations

### Translations



### Country flag



### Checklist

Thanks for following the guide and creating a high-quality and complete bug
report – you are almost done. This section ensures that you have read this guide
and have worked to your best knowledge to provide us with everything we need to
know to help you.


## 



## Adding a translation via pull request 

If you want to integrate this translation yourself, you can also create a pull 
request after following the issue and submitting it. Please 



find a missing translation in your language, please follow these 
guidelines to assist in the process:

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






