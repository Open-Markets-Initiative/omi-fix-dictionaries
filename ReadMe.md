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
| 175 | 96,329 |

## Open Markets Initiative

[![Omi](https://github.com/Open-Markets-Initiative/Directory/blob/main/About/Images/Logo.png)](https://github.com/Open-Markets-Initiative/Directory)  The Open Markets Initiative (Omi) is a group of technologists dedicated to enhancing the stability of electronic financial markets using modern development methods.

For a list of Omi projects: [Omi Projects](https://github.com/Open-Markets-Initiative/Directory/tree/main/Projects "Open Markets Initiative Projects")

For details of Omi rules and regulations: [Omi Directory](https://github.com/Open-Markets-Initiative/Directory "Open Markets Initiative Directory")
## Organizations

> [24X][24X.Directory] · [A2X][A2X.Directory] · [Aquis][Aquis.Directory] · [Asx][Asx.Directory] · [Bist][Bist.Directory] · [BlueOceanAts][BlueOceanAts.Directory] · [Box][Box.Directory] · [Cboe][Cboe.Directory] · [CixAts][CixAts.Directory] · [Coinbase][Coinbase.Directory] · [ElectronX][ElectronX.Directory] · [Eurex][Eurex.Directory] · [Euronext][Euronext.Directory] · [Hkex][Hkex.Directory] · [Iex][Iex.Directory] · [Ltse][Ltse.Directory] · [Memx][Memx.Directory] · [Miax][Miax.Directory] · [Nasdaq][Nasdaq.Directory] · [Nyse][Nyse.Directory] · [Odx][Odx.Directory] · [OtcMarkets][OtcMarkets.Directory] · [Sgx][Sgx.Directory] · [Taifex][Taifex.Directory] · [Txse][Txse.Directory]

## Exchanges

> [24XEquities][24XEquities.Exchange] · [A2XEquities][A2XEquities.Exchange] · [AmexEquities][AmexEquities.Exchange] · [AmexOptions][AmexOptions.Exchange] · [AquisEquities][AquisEquities.Exchange] · [ArcaEquities][ArcaEquities.Exchange] · [ArcaOptions][ArcaOptions.Exchange] · [AsxDerivatives][AsxDerivatives.Exchange] · [AsxSecurities][AsxSecurities.Exchange] · [BidsJapan][BidsJapan.Exchange] · [BlueEquities][BlueEquities.Ats] · [BorsaIstanbul][BorsaIstanbul.Exchange] · [BxeEquities][BxeEquities.Exchange] · [BxEquities][BxEquities.Exchange] · [BxOptions][BxOptions.Exchange] · [ByxEquities][ByxEquities.Exchange] · [BzxEquities][BzxEquities.Exchange] · [BzxOptions][BzxOptions.Exchange] · [C1Options][C1Options.Exchange] · [C2Options][C2Options.Exchange] · [CfeFutures][CfeFutures.Exchange] · [CoinbaseDerivatives][CoinbaseDerivatives.Exchange] · [CxaEquities][CxaEquities.Exchange] · [CxeEquities][CxeEquities.Exchange] · [CxjEquities][CxjEquities.Exchange] · [CxjSor][CxjSor.Exchange] · [EdgaEquities][EdgaEquities.Exchange] · [EdgxEquities][EdgxEquities.Exchange] · [EdgxOptions][EdgxOptions.Exchange] · [ElectricDerivatives][ElectricDerivatives.Exchange] · [EmeraldOptions][EmeraldOptions.Exchange] · [FixedIncome][FixedIncome.Exchange] · [GemxOptions][GemxOptions.Exchange] · [HkexSecurities][HkexSecurities.Exchange] · [IexEquities][IexEquities.Exchange] · [IexOptions][IexOptions.Exchange] · [IseOptions][IseOptions.Exchange] · [LinkAts][LinkAts.Ats] · [LinkEcn][LinkEcn.Ats] · [LinkNqb][LinkNqb.Ats] · [LtseEquities][LtseEquities.Exchange] · [MatchNow][MatchNow.Exchange] · [MemxOptions][MemxOptions.Exchange] · [MiaxOptions][MiaxOptions.Exchange] · [MoonAts][MoonAts.Ats] · [MrxOptions][MrxOptions.Exchange] · [NationalEquities][NationalEquities.Exchange] · [NeoEquities][NeoEquities.Exchange] · [NomOptions][NomOptions.Exchange] · [NsmEquities][NsmEquities.Exchange] · [NtxEquities][NtxEquities.Exchange] · [NyseEquities][NyseEquities.Exchange] · [OdxEquities][OdxEquities.Exchange] · [OdxSecurityToken][OdxSecurityToken.Exchange] · [PearlOptions][PearlOptions.Exchange] · [PhlxOptions][PhlxOptions.Exchange] · [PsxEquities][PsxEquities.Exchange] · [SapphireOptions][SapphireOptions.Exchange] · [TaifexDerivatives][TaifexDerivatives.Exchange] · [TexasEquities][TexasEquities.Exchange] · [TxseEquities][TxseEquities.Exchange]

## Platforms

> [CixAts CixAspen][CixAspen.Platform] · [Euronext Optiq][Optiq.Platform] · [Eurex T7][T7.Platform] · [Sgx TitanDt][TitanDt.Platform] · [Sgx TitanOtc][TitanOtc.Platform]

## Disclaimer

Any similarities between existing people, places and/or protocols is purely incidental.

Enjoy.


[24X.Directory]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/tree/main/24X "24 National Exchange"
[A2X.Directory]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/tree/main/A2X "A2X Markets"
[Aquis.Directory]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/tree/main/Aquis "Aquis Exchange"
[Asx.Directory]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/tree/main/Asx "Australian Securities Exchange"
[Bist.Directory]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/tree/main/Bist "Borsa İstanbul A.Ş."
[BlueOceanAts.Directory]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/tree/main/BlueOceanAts "Blue Ocean Technologies"
[Box.Directory]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/tree/main/Box ""
[Cboe.Directory]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/tree/main/Cboe "Chicago Board Options Exchange"
[CixAts.Directory]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/tree/main/CixAts "CIX Trading Inc."
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
[Odx.Directory]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/tree/main/Odx "Osaka Digital Exchange"
[OtcMarkets.Directory]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/tree/main/OtcMarkets "OTC Markets Group"
[Sgx.Directory]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/tree/main/Sgx "Singapore Exchange"
[Taifex.Directory]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/tree/main/Taifex "Taiwan Futures Exchange"
[Txse.Directory]: https://github.com/Open-Markets-Initiative/omi-fix-dictionaries/tree/main/Txse "Texas Stock Exchange"

[24XEquities.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/24X/Protocols/24XEquities "24X 24XEquities"
[A2XEquities.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/A2X/Protocols/A2XEquities "A2X A2XEquities"
[AmexEquities.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Nyse/Protocols/AmexEquities "Nyse AmexEquities"
[AmexOptions.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Nyse/Protocols/AmexOptions "Nyse AmexOptions"
[AquisEquities.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Aquis/Protocols/AquisEquities "Aquis AquisEquities"
[ArcaEquities.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Nyse/Protocols/ArcaEquities "Nyse ArcaEquities"
[ArcaOptions.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Nyse/Protocols/ArcaOptions "Nyse ArcaOptions"
[AsxDerivatives.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Asx/Protocols/AsxDerivatives "Asx AsxDerivatives"
[AsxSecurities.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Asx/Protocols/AsxSecurities "Asx AsxSecurities"
[BidsJapan.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Cboe/Protocols/BidsJapan "Cboe BidsJapan"
[BlueEquities.Ats]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/BlueOceanAts/Protocols/BlueEquities "BlueOceanAts BlueEquities"
[BorsaIstanbul.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Bist/Protocols/BorsaIstanbul "Bist BorsaIstanbul"
[BxeEquities.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Cboe/Protocols/BxeEquities "Cboe BxeEquities"
[BxEquities.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Nasdaq/Protocols/BxEquities "Nasdaq BxEquities"
[BxOptions.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Nasdaq/Protocols/BxOptions "Nasdaq BxOptions"
[ByxEquities.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Cboe/Protocols/ByxEquities "Cboe ByxEquities"
[BzxEquities.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Cboe/Protocols/BzxEquities "Cboe BzxEquities"
[BzxOptions.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Cboe/Protocols/BzxOptions "Cboe BzxOptions"
[C1Options.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Cboe/Protocols/C1Options "Cboe C1Options"
[C2Options.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Cboe/Protocols/C2Options "Cboe C2Options"
[CfeFutures.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Cboe/Protocols/CfeFutures "Cboe CfeFutures"
[CixAspen.Platform]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/CixAts/Protocols/CixAspen "CixAts CixAspen"
[CoinbaseDerivatives.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Coinbase/Protocols/CoinbaseDerivatives "Coinbase CoinbaseDerivatives"
[CxaEquities.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Cboe/Protocols/CxaEquities "Cboe CxaEquities"
[CxeEquities.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Cboe/Protocols/CxeEquities "Cboe CxeEquities"
[CxjEquities.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Cboe/Protocols/CxjEquities "Cboe CxjEquities"
[CxjSor.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Cboe/Protocols/CxjSor "Cboe CxjSor"
[EdgaEquities.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Cboe/Protocols/EdgaEquities "Cboe EdgaEquities"
[EdgxEquities.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Cboe/Protocols/EdgxEquities "Cboe EdgxEquities"
[EdgxOptions.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Cboe/Protocols/EdgxOptions "Cboe EdgxOptions"
[ElectricDerivatives.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/ElectronX/Protocols/ElectricDerivatives "ElectronX ElectricDerivatives"
[EmeraldOptions.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Miax/Protocols/EmeraldOptions "Miax EmeraldOptions"
[FixedIncome.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Cboe/Protocols/FixedIncome "Cboe FixedIncome"
[GemxOptions.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Nasdaq/Protocols/GemxOptions "Nasdaq GemxOptions"
[HkexSecurities.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Hkex/Protocols/HkexSecurities "Hkex HkexSecurities"
[IexEquities.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Iex/Protocols/IexEquities "Iex IexEquities"
[IexOptions.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Iex/Protocols/IexOptions "Iex IexOptions"
[IseOptions.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Nasdaq/Protocols/IseOptions "Nasdaq IseOptions"
[LinkAts.Ats]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/OtcMarkets/Protocols/LinkAts "OtcMarkets LinkAts"
[LinkEcn.Ats]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/OtcMarkets/Protocols/LinkEcn "OtcMarkets LinkEcn"
[LinkNqb.Ats]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/OtcMarkets/Protocols/LinkNqb "OtcMarkets LinkNqb"
[LtseEquities.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Ltse/Protocols/LtseEquities "Ltse LtseEquities"
[MatchNow.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Cboe/Protocols/MatchNow "Cboe MatchNow"
[MemxOptions.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Memx/Protocols/MemxOptions "Memx MemxOptions"
[MiaxOptions.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Miax/Protocols/MiaxOptions "Miax MiaxOptions"
[MoonAts.Ats]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/OtcMarkets/Protocols/MoonAts "OtcMarkets MoonAts"
[MrxOptions.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Nasdaq/Protocols/MrxOptions "Nasdaq MrxOptions"
[NationalEquities.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Nyse/Protocols/NationalEquities "Nyse NationalEquities"
[NeoEquities.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Cboe/Protocols/NeoEquities "Cboe NeoEquities"
[NomOptions.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Nasdaq/Protocols/NomOptions "Nasdaq NomOptions"
[NsmEquities.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Nasdaq/Protocols/NsmEquities "Nasdaq NsmEquities"
[NtxEquities.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Nasdaq/Protocols/NtxEquities "Nasdaq NtxEquities"
[NyseEquities.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Nyse/Protocols/NyseEquities "Nyse NyseEquities"
[OdxEquities.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Odx/Protocols/OdxEquities "Odx OdxEquities"
[OdxSecurityToken.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Odx/Protocols/OdxSecurityToken "Odx OdxSecurityToken"
[Optiq.Platform]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Euronext/Protocols/Optiq "Euronext Optiq"
[PearlOptions.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Miax/Protocols/PearlOptions "Miax PearlOptions"
[PhlxOptions.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Nasdaq/Protocols/PhlxOptions "Nasdaq PhlxOptions"
[PsxEquities.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Nasdaq/Protocols/PsxEquities "Nasdaq PsxEquities"
[SapphireOptions.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Miax/Protocols/SapphireOptions "Miax SapphireOptions"
[T7.Platform]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Eurex/Protocols/T7 "Eurex T7"
[TaifexDerivatives.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Taifex/Protocols/TaifexDerivatives "Taifex TaifexDerivatives"
[TexasEquities.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Nyse/Protocols/TexasEquities "Nyse TexasEquities"
[TitanDt.Platform]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Sgx/Protocols/TitanDt "Sgx TitanDt"
[TitanOtc.Platform]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Sgx/Protocols/TitanOtc "Sgx TitanOtc"
[TxseEquities.Exchange]: https://github.com/Open-Markets-Initiative/Directory/tree/main/Organizations/Txse/Protocols/TxseEquities "Txse TxseEquities"
