# PDP-Connect

Personal Data Portability Protocol Connect. An [LF Decentralized Trust](https://www.lfdecentralizedtrust.org/) lab.

PDPP is an open, vendor-neutral standard for personal data portability: how a
person authorises an application to read a specific, bounded slice of their
data, and how a server enforces that grant. It builds on [OAuth 2.0](https://www.rfc-editor.org/rfc/rfc6749) and
[RFC 9396](https://www.rfc-editor.org/rfc/rfc9396), and it composes with the [Data Transfer Initiative](https://dtinit.org/) rather than
duplicating it (consent and authorisation here, transfer there).

## Repositories
- **[pdpp](https://github.com/PDP-Connect/pdpp)**: the Personal Data Portability Protocol specification.
  Rendered at https://pdpp.dev
- **[data-connect](https://github.com/PDP-Connect/data-connect)**: the reference implementation (desktop app)
- **[data-connectors](https://github.com/PDP-Connect/data-connectors)**: the connector library (Spotify, Google, Instagram,
  ChatGPT, Apple Health, GitHub, LinkedIn, Oura, and more)
- **[governance](https://github.com/PDP-Connect/governance)**: how the lab is run

## Status
PDPP v0.1.0 is an LFDT Community Specification. PDP-Connect is a live LFDT Lab.
[Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0).

## Get involved
- Read the spec: https://pdpp.dev
- Working sessions (August 2026): [LFDT community calendar link](https://zoom-lfx.platform.linuxfoundation.org/meetings/lf-decentralized-trust?view=week)
- Discord: [https://discord.lfdecentralizedtrust.org](https://discord.lfdecentralizedtrust.org/) ([#pdp-connect](https://discord.com/channels/905194001349627914/1527713223334166744))
- Good first issues: see the [data-connect](https://github.com/PDP-Connect/data-connect) and [data-connectors](https://github.com/PDP-Connect/data-connectors) repos

Your data should be yours. Portability is the test. This is the layer that
makes the test pass.
