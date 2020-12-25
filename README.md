# scratch-l10n

Localisation of all Glitchy Scratch components.

## Using glitchyscratch-l10n in development

#### Installation

You can install this package with-
```Bash
npm install --save-dev glitchyscratch-l10n
```
#### Basic Use
```JavaScript
import locales, {localeData, isRtl} from 'scratch-l10n';
import editorMessages from 'scratch-l10n/locales/editor-messages';
```
* ``locales``: currently supported locales for the Scratch project
* ``isRtl``: function that returns true if the locale is one that is written right-to-left
* ``localeData``: locale data for the supported locales, in the format accepted by addLocaleData required by react-intl
* ``editorMessages``: the actual message strings for all supported locales for a particular resource. editorMessages collects all the strings for the interface, extensions and paint-editor.
