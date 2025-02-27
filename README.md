# Rebooting the Web of Trust XI: The Hague (September 2022)

This repository contains documents related to RWOT11, the eleventh Rebooting the Web of Trust design workshop, which will be held in the Hague, Netherlands, September, 2022

The goal of the workshop is to generate five technical white papers and/or proposals on topics decided by the group that would have the  greatest impact on the future.

## Final Papers

## [*Linking Credentials with Data Exchange Agreements through Secured Inclusive Interfaces*](final-documents/data-exchange-agreements-with-oca.pdf) [(Text)](final-documents/data-exchange-agreements-with-oca.md)

#### by  Lal Chandran, Lotta Lundin, Fredrik Lindén,  Philippe Page,  Paul Knowles,  Víctor Martínez Jurado,  Andrew Slack

> On the need to link verifiable credentials with the right to use data in a secure, inclusive user interaction.

> In this collaborative work from RWOT11, we revisit the issue of patient data exchange in a setting requiring cross-border, multi jurisdiction, and inclusive access to all participants. A fundamental problem in developing large-scale real-world solutions based on verifiable credentials is keeping the simplicity of usage for individuals in different contexts without sacrificing security.

> We aim to highlight selected technical challenges and outline how the DEXA and OCA protocols contribute to scalable solutions.

## [*Taking out the CRUD: Five Fabulous DID Attacks*](final-documents/taking-out-the-crud-five-fabulous-did-attacks.pdf) [(Text)](final-documents/taking-out-the-crud-five-fabulous-did-attacks.md)
#### by Shannon Appelcline, Cihan Saglam, Kate Sills, Carsten Stöcker

> Decentralized identity solutions, such as DID methods, tend to be designed to protect against certain attacks, but the purpose of that design usually is not explicitly stated in any architectural description or threat documentation. In particular, some DID methods have costly on-chain requirements that must have had a reasoning behind their requirement. We can today see that these DID methods were purposefully shaped, but it’s not clear why such decisions were made. The purpose of this paper is to describe a few colorful attacks on DID methods so that we can better understand what threats a system might be vulnerable to.

> Although we derived the examples in this paper by examining current DID methods, we believe these attack vectors are more general, even for systems not using DIDs. The goal is to support engineers and developers who are developing decentralized identity solutions to safeguard their work and make it secure and compliant.

## [*Verifiable Issuers & Verifiers*](final-documents/verifiable-issuers-and-verifiers.pdf) [(Text)](final-documents/verifiable-issuers-and-verifiers.md)
#### by Manu Sporny, Oskar van Deventer, Isaac Henderson Johnson Jeyakumar, Shigeya Suzuki, Konstantin Tsabolov, Line Kofoed, Rieks Joostena

> Enabling anyone to share information about the Issuers and Verifiers for whom they assure trust

> This work focuses on how a party or its agent can decide whether or not to engage with a counterparty in a transaction. The purpose of this work is to enable the sharing of a list of Verifiable Issuers and Verifiers in a way that is useful to a particular transaction. A set of use cases provide examples where verification of an Issuer ("Is that diploma from a recognized university?") or Verifier ("Should the wallet block an unauthorized Verifier?") is needed. The studied prior art highlights various solutions to verify Issuers and Verifiers and identifies a lack of standards. Important contributions from this paper include a unified set of requirements, a data model, and multiple serializations of the data model --- including but not limited to Verifiable Credentials, DNSSEC, and blockchain-based serializations --- that could then be incubated and sent onto the standards track at global standards setting organizations.

## Advance Readings

In advance of the design workshop, all participants are invited to contribute a one-or-two page topic paper to be shared with the other attendees on either:

   * A specific problem that they wanted to solve with a web-of-trust solution, and why current solutions (PGP or CA-based PKI) can't address the problem?
   * A specific solution related to the web-of-trust that you'd like others to use or contribute to?

Please see the [Advance Readings directory](./advance-readings/advance-reading-primer.md) for all the current papers (and how to upload yours). Advance readings from RWOT10 (cancelled due to COVID) are also included.

## Complete Rebooting the Web of Trust Listing

A different repository is available for each of the Rebooting the Web of Trust design workshops:

* [Rebooting the Web of Trust XI: Netherlands (September 2022)](https://github.com/WebOfTrustInfo/rwot11-netherlands)
* [Rebooting the Web of Trust X: Buenos Aires (March 2020)](https://github.com/WebOfTrustInfo/rwot10-buenosaires)
* [Rebooting the Web of Trust IX: Prague (September 2019)](https://github.com/WebOfTrustInfo/rwot9-prague)
* [Rebooting the Web of Trust VIII: Barcelona (March 2019)](https://github.com/WebOfTrustInfo/rwot8-barcelona)
* [Rebooting the Web of Trust VII: Toronto (September 2018)](https://github.com/WebOfTrustInfo/rwot7-fall2018)
* [Rebooting the Web of Trust VI: Santa Barbara (March 2018)](https://github.com/WebOfTrustInfo/rebooting-the-web-of-trust-spring2018)
* [Rebooting the Web of Trust V: Boston (October 2017)](https://github.com/WebOfTrustInfo/rebooting-the-web-of-trust-fall2017)
* [Rebooting the Web of Trust IV: Paris (April 2017)](https://github.com/WebOfTrustInfo/rebooting-the-web-of-trust-spring2017)
* [Rebooting the Web of Trust III: San Francisco (October 2016)](https://github.com/WebOfTrustInfo/rebooting-the-web-of-trust-fall2016)
* [Rebooting the Web of Trust II: ID2020 (May 2016)](https://github.com/WebOfTrustInfo/ID2020DesignWorkshop)
* [Rebooting the Web of Trust I: San Francisco (November 2015)](https://github.com/WebOfTrustInfo/rebooting-the-web-of-trust)

## License

All of the contents of this directory are licensed [Creative Commons CC-BY](https://github.com/WebOfTrustInfo/rebooting-the-web-of-trust/blob/master/final-documents/LICENSE-CC-BY-4.0.md) their contributors.
