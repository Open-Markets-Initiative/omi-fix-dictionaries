# Omi FIX Dictionaries

[![Validate](https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/actions/workflows/validate.yml/badge.svg)](https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/actions/workflows/validate.yml)

Omi FIX Dictionaries are QuickFIX-style dictionary XML files describing FIX session and application messages, fields, and value enumerations for each supported FIX dialect.

For more information on QuickFIX: [QuickFIX](https://quickfixengine.org "QuickFIX Open Source FIX Engine")
## Usage

Each dictionary is a self-contained QuickFIX dictionary `.xml` document. Point your QuickFIX (or QuickFIX-compatible) engine's `DataDictionary` configuration at the file matching your counterparty's FIX dialect and version.

For QuickFIX dictionary documentation: [QuickFIX Dictionary](https://quickfixengine.org/c/documentation/#data-dictionary "QuickFIX Data Dictionary Documentation")
## QuickFIX

QuickFIX is the long-standing open source FIX engine that defines the dictionary XML shape these files emit. The project is organized as a multi-repository GitHub organization, with the original C++ engine (`quickfix`), the Java port (`quickfixj`), and additional language ports each maintained as their own repository under the same umbrella.

Browse all QuickFIX repositories: [QuickFIX on GitHub](https://github.com/quickfix "QuickFIX GitHub Organization")
## Development

This entire repository is source generated — including the words you are reading right now. To suggest updates, please open an issue describing the change and link the authoritative FIX specification. Time permitting, we will update the upstream models and regenerate.

| Protocol Count | Generated Lines |
| --- | --- |
| 169 | 94,375 |

## Open Markets Initiative

[![Omi](https://github.com/Open-Markets-Initiative/Directory/blob/main/About/Images/Logo.png)](https://github.com/Open-Markets-Initiative/Directory)  The Open Markets Initiative (Omi) is a group of technologists dedicated to enhancing the stability of electronic financial markets using modern development methods.

For a list of Omi projects: [Omi Projects](https://github.com/Open-Markets-Initiative/Directory/tree/main/Projects "Open Markets Initiative Projects")

For details of Omi rules and regulations: [Omi Directory](https://github.com/Open-Markets-Initiative/Directory "Open Markets Initiative Directory")
## Organizations

> [24X][24X.Directory] · [A2X][A2X.Directory] · [Aquis][Aquis.Directory] · [Asx][Asx.Directory] · [Bist][Bist.Directory] · [Boats][Boats.Directory] · [Box][Box.Directory] · [Cboe][Cboe.Directory] · [Coinbase][Coinbase.Directory] · [ElectronX][ElectronX.Directory] · [Eurex][Eurex.Directory] · [Euronext][Euronext.Directory] · [Hkex][Hkex.Directory] · [Iex][Iex.Directory] · [Ltse][Ltse.Directory] · [Memx][Memx.Directory] · [Miax][Miax.Directory] · [Nasdaq][Nasdaq.Directory] · [Nyse][Nyse.Directory] · [Odx][Odx.Directory] · [OtcMarkets][OtcMarkets.Directory] · [Sgx][Sgx.Directory] · [Txse][Txse.Directory]

## Disclaimer

Any similarities between existing people, places and/or protocols is purely incidental.

Enjoy.


[24X.Directory]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/tree/main/24X "24 National Exchange"
[A2X.Directory]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/tree/main/A2X "A2X Markets"
[Aquis.Directory]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/tree/main/Aquis "Aquis Exchange"
[Asx.Directory]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/tree/main/Asx "Australian Securities Exchange"
[Bist.Directory]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/tree/main/Bist "Borsa İstanbul A.Ş."
[Boats.Directory]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/tree/main/Boats "Blue Ocean Technologies"
[Box.Directory]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/tree/main/Box ""
[Cboe.Directory]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/tree/main/Cboe "Chicago Board Options Exchange"
[Coinbase.Directory]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/tree/main/Coinbase "Coinbase"
[ElectronX.Directory]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/tree/main/ElectronX "ElectronX Markets"
[Eurex.Directory]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/tree/main/Eurex "Eurex Exchange"
[Euronext.Directory]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/tree/main/Euronext "Euronext"
[Hkex.Directory]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/tree/main/Hkex "Hong Kong Exchanges and Clearing"
[Iex.Directory]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/tree/main/Iex "Investors Exchange"
[Ltse.Directory]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/tree/main/Ltse "Long-Term Stock Exchange"
[Memx.Directory]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/tree/main/Memx "The Members Exchange"
[Miax.Directory]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/tree/main/Miax "Miami International Holdings"
[Nasdaq.Directory]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/tree/main/Nasdaq "National Association of Securities Dealers Automated Quotations (Nasdaq)"
[Nyse.Directory]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/tree/main/Nyse "New York Stock Exchange"
[Odx.Directory]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/tree/main/Odx ""
[OtcMarkets.Directory]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/tree/main/OtcMarkets "OTC Markets Group"
[Sgx.Directory]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/tree/main/Sgx "Singapore Exchange"
[Txse.Directory]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/tree/main/Txse "Texas Stock Exchange"
