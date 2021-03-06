# Fort Improvement Proposals (FIPs)
Fort Improvement Proposals (FIPs) describe standards for the Fort platform, including core protocol specifications, web UI, and Off-chain program.

## What is FIP?
FIP stands for Fort Improvement Proposal. FIP is a design document that provides information for the Fort community or describes new features of Fort or its processes or environment. FIP should provide a concise technical specification of the function and the basic principle of the function. FIP authors are responsible for building consensus within the community and recording disagreements.

## Proposal process
1. Discuss freely on [Issues](https://github.com/FORT-Protocol/FIPs/issues) first, and there is no format restriction on the content of the discussion.
2. Issue managers will add valuable proposals to FIPs, and formally discuss them.

## FIP Formats and Templates
FIPs should be written in markdown format.There is a [template](https://github.com/FORT-Protocol/FIPs/blob/main/README.md#fips-example) to follow.

## Development of FIPs
In the initial stage, only markdown display mode was retained. When the number of proposals increases, Jekyll will be used to display FIPs. At the same time, it is also hoped that community members will actively participate in the management of Issues.

## FIPS example
```
---
fip: <to be assigned>
title: <The FIP title is a few words, not a complete sentence>
description: <Description is one full (short) sentence>
author: <a list of the author's or authors' name(s) and/or username(s), or name(s) and email(s), e.g. (use with the parentheses or triangular brackets): FirstName LastName (@GitHubUsername), FirstName LastName <foo@bar.com>, FirstName (@GitHubUsername) and GitHubUsername (@GitHubUsername)>
discussions-to: <URL>
created: <date created on, in ISO 8601 (yyyy-mm-dd) format>
---

This is the suggested template for new FIPs.

## Abstract
Abstract is a multi-sentence (short paragraph) technical summary. This should be a very terse and human-readable version of the specification section. Someone should be able to read only the abstract to get the gist of what this specification does.

## Motivation
The motivation section should describe the "why" of this FIP. What problem does it solve? Why should someone want to implement this standard? What benefit does it provide to the Fort ecosystem? What use cases does this FIP address?

## Specification
The technical specification should describe the syntax and semantics of any new feature. The specification should be detailed enough to allow competing.

## Rationale
The rationale fleshes out the specification by describing what motivated the design and why particular design decisions were made. It should describe alternate designs that were considered and related work, e.g. how the feature is supported in other languages.

## Backwards Compatibility
All FIPs that introduce backwards incompatibilities must include a section describing these incompatibilities and their severity. The FIP must explain how the author proposes to deal with these incompatibilities. FIP submissions without a sufficient backwards compatibility treatise may be rejected outright.

## Test Cases
Test cases for an implementation are mandatory for FIPs that are affecting consensus changes.  If the test suite is too large to reasonably be included inline, then consider adding it as one or more files in `../assets/fip-####/`.

## Reference Implementation
An optional section that contains a reference/example implementation that people can use to assist in understanding or implementing this specification.  If the implementation is too large to reasonably be included inline, then consider adding it as one or more files in `../assets/fip-####/`.

## Security Considerations
All FIPs must contain a section that discusses the security implications/considerations relevant to the proposed change. Include information that might be important for security discussions, surfaces risks and can be used throughout the life cycle of the proposal. E.g. include security-relevant design decisions, concerns, important discussions, implementation-specific guidance and pitfalls, an outline of threats and risks and how they are being addressed. FIP submissions missing the "Security Considerations" section will be rejected.
```



