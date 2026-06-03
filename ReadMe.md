# Omi FIX Dictionaries

Omi FIX Dictionaries are QuickFIX-style dictionary XML files describing FIX session and application messages, fields, and value enumerations for each supported FIX dialect.

For more information on QuickFIX: [QuickFIX](https://quickfixengine.org "QuickFIX Open Source FIX Engine")
## Usage

Each dictionary is a self-contained QuickFIX dictionary `.xml` document. Point your QuickFIX (or QuickFIX-compatible) engine's `DataDictionary` configuration at the file matching your counterparty's FIX dialect and version.

For QuickFIX dictionary documentation: [QuickFIX Dictionary](https://quickfixengine.org/c/documentation/#data-dictionary "QuickFIX Data Dictionary Documentation")
## QuickFIX

QuickFIX is the long-standing open source FIX engine that defines the dictionary XML shape these files emit. The project is organized as a multi-repository GitHub organization, with the original C++ engine (`quickfix`), the Java port (`quickfixj`), and additional language ports each maintained as their own repository under the same umbrella.

Browse all QuickFIX repositories: [QuickFIX on GitHub](https://github.com/quickfix "QuickFIX GitHub Organization")

Each implementation reads the same dictionary schema — `<fix>`/`<header>`/`<trailer>`/`<messages>`/`<components>`/`<fields>` with `name`, `tag`, `type`, `required`, and `enum`/`value` attributes — so a dictionary published here can be consumed by any QuickFIX engine in its supported language.

## Development

This entire repository is source generated — including the words you are reading right now. To suggest updates, please open an issue describing the change and link the authoritative FIX specification. Time permitting, we will update the upstream models and regenerate.

## Open Markets Initiative

[![Omi](https://github.com/Open-Markets-Initiative/Directory/blob/main/About/Images/Logo.png)](https://github.com/Open-Markets-Initiative/Directory)  The Open Markets Initiative (Omi) is a group of technologists dedicated to enhancing the stability of electronic financial markets using modern development methods.

For a list of Omi projects: [Omi Projects](https://github.com/Open-Markets-Initiative/Directory/tree/main/Projects "Open Markets Initiative Projects")

For details of Omi rules and regulations: [Omi Directory](https://github.com/Open-Markets-Initiative/Directory "Open Markets Initiative Directory")
## Dictionaries

Dictionaries by exchange: ElectronX, Iex

## Disclaimer

Any similarities between existing people, places and/or protocols is purely incidental.

Enjoy.

