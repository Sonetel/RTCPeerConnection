---
# Canonical repo classification — see docs/REPO-CLASSIFICATION.md.
# This front-matter is the source of truth; GitHub topics mirror from it.
content: code
domain: product
exposure: customer-facing
layer: shared-lib
lifecycle: inactive
---

# RTCPeerConnection

> A tiny browser module that normalizes and simplifies the WebRTC peer-connection API, wrapping offer/answer and ICE handling in an event-emitter interface (cross-browser).

## What it contains
JavaScript browser library (`rtcpeerconnection.js` plus a prebuilt `rtcpeerconnection.bundle.js` for non-browserify/AMD use). Inherits from WildEmitter so consumers listen for `ice`, `offer`, `answer`, `addStream`/`removeStream` and `close` events instead of raw PC callbacks. Published as the npm package `rtcpeerconnection`; `build.js` produces the bundle and `test/` holds bandwidth/ICE/basic browser tests.

## Ownership
- **Code owner:** Venkata Kuna (Venkatakuna)

## Notes
Keep temporarily. Remove with MIM decommission
