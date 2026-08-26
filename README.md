# VisitorAPI Personalize - Show/Hide Element

A Google Tag Manager Custom Template. Show or hide an element based on visitor country, language, currency, etc.

Built on [VisitorAPI](https://www.visitorapi.com) -- requires a VisitorAPI
project ID and domain allowlist (see https://app.visitorapi.com).

## Setup

1. Import `template.tpl` into your GTM container (Templates -> Tag
   Templates -> New -> Import), or install it from the Community
   Template Gallery once approved.
2. Create a tag from this template with your Project ID and one or
   more rules.
3. Preview and publish as usual.

## Source and engine

This template is one of six generated from
[visitor-api-personalize](https://github.com/visitorapi/visitor-api-personalize),
which is also where the underlying matching/DOM engine
(`personalize.js`, loaded from `cdn.visitorapi.com`), its tests, and
the other five use-case templates live. File issues or contribute
there, not here -- this repo is a frozen publish target for the
Community Template Gallery, kept in sync by hand with
`templates/show-hide.tpl` in that repo.

## License

Apache 2.0
