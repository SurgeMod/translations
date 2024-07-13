# Surge Translations

Repository housing the translations for the Surge Launcher.

## Adding a new language

When creating a new translation we *highly* recommend you [opening an issue](https://github.com/SurgeMod/translations/issues/new/choose), this is to prevent communication errors and so others can track progress.

Once you have done that complete the following steps:
  - Copy the contents of the [`en.json`](https://github.com/SurgeMod/translations/blob/master/translations/en.json) file located in the "translations" directory
  - [Fork](https://github.com/SurgeMod/translations/fork) the repository
  - Create a new `.json` file and translate the text to your desired language
  - Rename your file to use the correct [language code](https://www.wikiwand.com/en/List_of_ISO_639-1_codes)

## Merging Changes

Upon translating the text, you can get merged by [creating a pull request](https://github.com/SurgeMod/translations/compare). From there, use the text field to accurately describe what was changed/implemented.


## Translating

For our translations we use JSON files, these files consist of key-value pairs:
```json
"key": "value"
```

Only the value should be translated, the key should remain consistent.

### Support

If you need help or have any questions regarding the translation process, feel free to ask in your respective language's GitHub issue or [join our Discord server](https://discord.gg/mMHUUCtvye). We'll be happy to assist you.

Thank you for contributing to Surge Launcher translations! Your efforts help make our project accessible to a wider audience.
