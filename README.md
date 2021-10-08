# Fort Improvement Proposals (FIPs)
Fort Improvement Proposals (FIPs) describe standards for the Fort platform, including core protocol specifications, web UI, and Off-chain program.

## What is FIP?
FIP stands for Fort Improvement Proposal. FIP is a design document that provides information for the Fort community or describes new features of Fort or its processes or environment. FIP should provide a concise technical specification of the function and the basic principle of the function. FIP authors are responsible for building consensus within the community and recording disagreements.

## Proposal process
1. Discuss freely on [Issues](https://eips.ethereum.org/EIPS/eip-1) first, and there is no format restriction on the content of the discussion.
2. Issue managers will add valuable proposals to FIPs, and formally discuss them.

## FIP Formats and Templates
FIPs should be written in markdown format.

## Development of FIPs
In the initial stage, only markdown display mode was retained. When the number of proposals increases, Jekyll will be used to display FIPs. At the same time, it is also hoped that community members will actively participate in the management of Issues.

## FIPS example
'''
---
eip: <to be assigned>
title: <The EIP title is a few words, not a complete sentence>
description: <Description is one full (short) sentence>
author: <a list of the author's or authors' name(s) and/or username(s), or name(s) and email(s), e.g. (use with the parentheses or triangular brackets): FirstName LastName (@GitHubUsername), FirstName LastName <foo@bar.com>, FirstName (@GitHubUsername) and GitHubUsername (@GitHubUsername)>
discussions-to: <URL>
status: Draft
type: <Standards Track, Meta, or Informational>
category (*only required for Standards Track): <Core, Networking, Interface, or ERC>
created: <date created on, in ISO 8601 (yyyy-mm-dd) format>
requires (*optional): <EIP number(s)>
replaces (*optional): <EIP number(s)>
---

This is the suggested template for new EIPs.

Note that an EIP number will be assigned by an editor. When opening a pull request to submit your EIP, please use an abbreviated title in the filename, `eip-draft_title_abbrev.md`.

The title should be 44 characters or less. It should not repeat the EIP number in title, irrespective of the category. 

## Abstract
Abstract is a multi-sentence (short paragraph) technical summary. This should be a very terse and human-readable version of the specification section. Someone should be able to read only the abstract to get the gist of what this specification does.

## Motivation
The motivation section should describe the "why" of this EIP. What problem does it solve? Why should someone want to implement this standard? What benefit does it provide to the Ethereum ecosystem? What use cases does this EIP address?

## Specification
The technical specification should describe the syntax and semantics of any new feature. The specification should be detailed enough to allow competing, interoperable implementations for any of the current Ethereum platforms (go-ethereum, parity, cpp-ethereum, ethereumj, ethereumjs, and [others](https://github.com/ethereum/wiki/wiki/Clients)).

## Rationale
The rationale fleshes out the specification by describing what motivated the design and why particular design decisions were made. It should describe alternate designs that were considered and related work, e.g. how the feature is supported in other languages.

## Backwards Compatibility
All EIPs that introduce backwards incompatibilities must include a section describing these incompatibilities and their severity. The EIP must explain how the author proposes to deal with these incompatibilities. EIP submissions without a sufficient backwards compatibility treatise may be rejected outright.

## Test Cases
Test cases for an implementation are mandatory for EIPs that are affecting consensus changes.  If the test suite is too large to reasonably be included inline, then consider adding it as one or more files in `../assets/eip-####/`.

## Reference Implementation
An optional section that contains a reference/example implementation that people can use to assist in understanding or implementing this specification.  If the implementation is too large to reasonably be included inline, then consider adding it as one or more files in `../assets/eip-####/`.

## Security Considerations
All EIPs must contain a section that discusses the security implications/considerations relevant to the proposed change. Include information that might be important for security discussions, surfaces risks and can be used throughout the life cycle of the proposal. E.g. include security-relevant design decisions, concerns, important discussions, implementation-specific guidance and pitfalls, an outline of threats and risks and how they are being addressed. EIP submissions missing the "Security Considerations" section will be rejected. An EIP cannot proceed to status "Final" without a Security Considerations discussion deemed sufficient by the reviewers.

## Copyright
Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
'''



