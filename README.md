![FIDO2 & WebAuthn Status](./FIDO2%20WebAuthn%20Status.png)

[![License: CC0-1.0](https://licensebuttons.net/l/zero/1.0/80x15.png)](http://creativecommons.org/publicdomain/zero/1.0/)

## Overview
This image is a best effort to capture the current status of FIDO2 and WebAuthn adoption status across various platforms. I have made best efforts to confirm with the various browser and OS companies that this is up to date, and I will continue to update this image as the landscape evolves.

This image is public domain (CC0) -- there are no requirements for attribtuion or sharing back any changes or updates; however, I do like attribution and information about updates. :)

## About FIDO2 and WebAuthn
FIDO2 is a continuation of the FIDO Alliance's work to eliminate the hassles and threats posed by passwords. It has two pieces:
1. The FIDO Client to Authenticator Protocol (CTAP) which is used to talk to USB, NFC, BLE and other devices that verify users and perform authentication,
2. The W3C WebAuthn specification, which lays out the protocol, message formats, cryptographic objects, etc. and specifies how browsers should implement them.

While much of the excitement around FIDO2 is around browsers, it can be imlemented by nearly anything -- including the Operating Systems underlying the browsers. This is complicated by the fact that browsers and operating systems may choose to implement different features of CTAP (USB, BLE, NFC, OS APIs, etc).

Hopefully they all converge to the same feature set over time, but hopefully this diagram helps people understand the state of the evolving ecosystem.