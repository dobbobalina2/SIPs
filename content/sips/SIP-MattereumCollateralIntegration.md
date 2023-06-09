---
sip: <to be assigned>
title: <SIP title>
network: <Ethereum>
status: <Draft>
type: < Governance>
author: dobbobalina2 
implementor: <a list of the author's or authors' name(s) and/or username(s), or name(s) and email(s), e.g. (use with the parentheses or triangular brackets): FirstName LastName (@GitHubUsername), FirstName LastName <foo@bar.com>, FirstName (@GitHubUsername) and GitHubUsername (@GitHubUsername)>
release: (Release Name)
implementation-date:
discussions-to: <Create a new thread on https://research.synthetix.io and drop the link here>
proposal: <snapshot.org proposal link> (*optional)
created: <date created on, in ISO 8601 (yyyy-mm-dd) format>
requires: <SIP number(s)> (*optional)
---

<!--You can leave these HTML comments in your merged SIP and delete the visible duplicate text guides, they will not appear and may be helpful to refer to if you edit it again. This is the suggested template for new SIPs. Note that an SIP number will be assigned by an editor. When opening a pull request to submit your SIP, please use an abbreviated title in the filename, `sip-draft_title_abbrev.md`. The title should be 44 characters or less.-->

This is the suggested template for new SIPs. Note that an SIP number will be assigned by an editor. When opening a pull request to submit your SIP, please use an abbreviated title in the filename, `sip-draft_title_abbrev.md`. The title should be 44 characters or less.

## Simple Summary

<!--"If you can't explain it simply, you don't understand it well enough." Simply describe the outcome the proposed changes intends to achieve. This should be non-technical and accessible to a casual community member.-->
 
Mattereum Gold NFTs can be added as collateral for Synthetix V3 markets, introducing a new dimension to the decentralized finance (DeFi) ecosystem. By integrating Mattereum's technology with Synthetix, users can leverage their ownership of physical gold stored by centruies old trust gold custodians to access a wider range of synthetic assets and liquidity.

## Abstract

<!--A short (~200 word) description of the proposed change, the abstract should clearly describe the proposed change. This is what *will* be done if the SIP is implemented, not *why* it should be done or *how* it will be done. If the SIP proposes deploying a new contract, write, "we propose to deploy a new contract that will do x".-->

 Syntethix should deploy a new liqudity pool for V3 supporting NFT types. Specification for the NFT standard ( 721 or 1155) can be discussed at a future date. A standard unit of gold should be used as well to ensure minimal burden on the smart contract to calculate the gold value

## Motivation

<!--This is the problem statement. This is the *why* of the SIP. It should clearly explain *why* the current state of the protocol is inadequate.  It is critical that you explain *why* the change is needed, if the SIP proposes changing how something is calculated, you must address *why* the current calculation is innaccurate or wrong. This is not the place to describe how the SIP will address the issue!-->

In the current DeFi landscape, there is a pressing need to diversify from fiat-based stablecoins and enhance stability and resilience by incorporating tangible assets as collateral. While digital assets have dominated the space, their volatility and inherent risks raise concerns for users seeking a more secure and diverse portfolio.

Furthermore, the lack of connection to real-world value limits the adoption and trust in purely digital collateral. Users are seeking alternatives that provide stability and a tangible link to assets with a proven track record of preserving value during economic uncertainties.

## Specification

<!--The specification should describe the syntax and semantics of any new feature, there are five sections
1. Overview
2. Rationale
3. Technical Specification
4. Test Cases
5. Configurable Values
-->

### Overview

<!--This is a high level overview of *how* the SIP will solve the problem. The overview should clearly describe how the new feature will be implemented.-->

Firstly, gold has long been recognized as a store of value and a hedge against economic uncertainty. By accepting Mattereum's gold NFTs as collateral, Synthetix introduces a tangible and reliable asset into its ecosystem. This allows users to diversify their holdings beyond fiat-based stablecoins, reducing their exposure to the volatility and potential risks associated with purely digital assets. Gold's historical stability can provide a sense of security and act as a reliable anchor within the Synthetix protocol.

Moreover, gold's intrinsic value and global recognition make it a highly liquid and widely accepted asset. By utilizing gold NFTs as collateral, Synthetix ensures that users have access to a stable and resilient form of collateral that can weather market fluctuations. This strengthens the overall stability and security of the protocol, reducing the potential impact of volatility in purely digital collateral assets.

Additionally, integrating Mattereum's gold NFTs as collateral aligns with the growing demand for asset-backed and real-world value representation within DeFi. It bridges the gap between the physical and digital realms, offering users a tangible connection to a widely accepted and trusted asset. This integration attracts users seeking stability, diversification, and a more robust collateral framework, enhancing the overall appeal and adoption of Synthetix as a DeFi platform.

 If we the liqudity pools added support for ERC-1155 then all of the RWA that Mattereum onboards will be available to the community to use with the all the legal protection required to sleep well at night
 ### Rationale

<!--This is where you explain the reasoning behind how you propose to solve the problem. Why did you propose to implement the change in this way, what were the considerations and trade-offs. The rationale fleshes out what motivated the design and why particular design decisions were made. It should describe alternate designs that were considered and related work. The rationale may also provide evidence of consensus within the community, and should discuss important objections or concerns raised during discussion.-->

This is where you explain the reasoning behind how you propose to solve the problem. Why did you propose to implement the change in this way, what were the considerations and trade-offs. The rationale fleshes out what motivated the design and why particular design decisions were made. It should describe alternate designs that were considered and related work. The rationale may also provide evidence of consensus within the community, and should discuss important objections or concerns raised during discussion.

### Technical Specification

<!--The technical specification should outline the public API of the changes proposed. That is, changes to any of the interfaces Synthetix currently exposes or the creations of new ones.-->

The technical specification should outline the public API of the changes proposed. That is, changes to any of the interfaces Synthetix currently exposes or the creations of new ones.

### Test Cases

<!--Test cases for an implementation are mandatory for SIPs but can be included with the implementation..-->

Test cases for an implementation are mandatory for SIPs but can be included with the implementation.

### Configurable Values (Via SCCP)

<!--Please list all values configurable via SCCP under this implementation.-->

Please list all values configurable via SCCP under this implementation.

## Copyright

Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
