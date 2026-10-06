# Arabic translation for OpenCloud Web

One gettext `.po` file per package, matching the Transifex resources of the
`opencloud-eu` project (`web-files`, `web-pkg`, `web-runtime`, ...). Every
source string of the packages is translated (plural forms included).

OpenCloud takes translations through Transifex, not through pull requests
(`l10n/translations.json` is generated from Transifex), so these files are
meant to be uploaded there:

1. Join the Arabic team of https://app.transifex.com/opencloud-eu/opencloud-eu/
2. For each resource, open the Arabic language and use *Upload file*
   with the matching `.po` file (e.g. `web-app-files.ar.po` -> resource `web-files`).
3. The next `[tx] updated from transifex` commit in the repository picks them up.

The translations were produced from the source strings with a consistent
glossary and only checked mechanically (placeholders, plural forms); they should
be reviewed by a native speaker in Transifex.
