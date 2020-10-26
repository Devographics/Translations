This repo contains all the locale files for the State of JS, CSS, etc. surveys, including questions, results, homepages, and more. 

## Getting Started

The YAML files to translate all exist in this current repo. [COMING SOON]

**IMPORTANT: first, check that there aren't any [existing PRs](https://github.com/StateOfJS/state-of-js-graphql-results-api/pulls) for the language you want to translate first!**

## Getting Credit

Every translator will be credited on any site that makes use of the translations, starting with the survey-taking app. You can add your name here if it's not already there.

- https://github.com/StateOfJS/Translations/blob/master/locales.yml

## Translation API

You can get extra data such as the completion percentage for a locale or the untranslated strings via our API, available at: 

- https://graphiql.stateofjs.com/

Here is a sample query: 

```graphql
query GetLocaleData {
  locale(localeId: "ru-RU") {
    completion
    totalCount
    translatedCount
    translators
    untranslatedKeys
  }
}
```

## Joining Translation Teams

It's recommended you join the [translation team](https://github.com/orgs/StateOfJS/teams/translators/teams) for the language you want to translate.

## Previous Translations

You may also want to take a look at previous year's translations if that helps: 

- [State of JS 2019](https://github.com/StateOfJS/StateOfJS-2019/tree/master/src/translations)
- [State of CSS 2019](https://github.com/StateOfJS/StateOfCSS-2019/tree/master/src/translations)
