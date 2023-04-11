# Faqs – Frequently asked questions

- _Where can I ask questions?_
- _I want to become a sponsor, but I'm wondering XY_ 
- 


## Subscription & payment
- _Why a subscription-model?_
- _How can I set my billing to monthly or yearly?_
- _What is considered commercial use?_
- _What is_


_How can I set my billing to monthly or yearly?_

You can sponsor on a monthly or yearly basis. The [billing cycle] is an account 
level setting and can be easily changed by you in your account. If for some 
reason you cannot make this change, you can create a dedicated (bot-account) 
GitHub account with a yearly billing cycle, which you only use for sponsoring 
(some sponsors already do that).

If you have any problems or further questions, please reach out to
sponsors@squidfunk.com.

  [billing cycle]: https://docs.github.com/en/github/setting-up-and-managing-billing-and-payments-on-github/changing-the-duration-of-your-billing-cycle

- _Why can't my organizational account get access to Insiders?_
Due 

## Terms & conditions
- _What does your __fair use policy__ mean?_



- _What if my company doesn’t use GitHub?_
- _Do I need to fork this project?_
- _Do you offer free Insiders access to Open Source projects?_
- _Do you offer discounts for the Insiders version?_
- _We sponsored with our organisation, how do we get access?_


## Compatibility

_We're building an open source project and want to allow outside collaborators
to run and build our documentation locally without having access to Insiders.
Is this still possible?_

Yes. Insiders is compatible with Material for MkDocs. Almost all new features
and configuration options are either backward-compatible or implemented behind
feature flags. When working with outside collaborators, it should be rarely
necessary to change the general appearance of your site. Most Insiders features
enhance the overall experience, e.g. by adding icons to pages or providing a
feedback widget. While this features add value for the user of your site, they
shouldn't be necessary for previewing when making changes to content. Currently,
the only content-related features in Insiders that can't be properly previewed
by non-Insiders users are:

- [Annotations]
- [Card grids]

This means that outside collaborators are able to build the documentation
locally with Material for MkDocs and when they push their changes, your CI
pipeline will build it with Insiders. When using built-in plugins that are
exclusive to Insiders, it's recommended to split configuration into a base
`mkdocs.yml` and one with plugin overrides via [configuration inheritance].

See the [getting started guide] for more information.

  [configuration inheritance]: https://www.mkdocs.org/user-guide/configuration/#configuration-inheritance
  [getting started guide]: getting-started.md#caveats

### Terms

_Are we allowed to use Insiders under the same terms and conditions as
Material for MkDocs?_

Yes. Whether you're an individual or a company, you may use _Material for MkDocs
Insiders_ precisely under the same terms as Material for MkDocs, which are given
by the [MIT license]. However, we kindly ask you to respect our
__fair use policy__:

- Please __don't distribute the source code__ of Insiders. You may freely use
  it for public, private or commercial projects, privately fork or mirror it,
  but please don't make the source code public, as it would counteract the 
  sponsorware strategy.

- If you cancel your subscription, you're automatically removed as a
  collaborator and will miss out on all future updates of Insiders. However, you
  may __use the latest version__ that's available to you __as long as you like__.
  Just remember that [GitHub deletes private forks].

  [MIT license]: ../license.md
  [GitHub deletes private forks]: https://docs.github.com/en/github/setting-up-and-managing-your-github-user-account/removing-a-collaborator-from-a-personal-repository
