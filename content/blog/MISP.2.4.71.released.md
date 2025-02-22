---
title: MISP 2.4.71 released
date: 2017-04-11
layout: post
banner: /img/blog/misp-small.png
---

A new version of MISP [2.4.71](https://github.com/MISP/MISP/tree/v2.4.71) has been released including new features, improvements and important bug fixes.

- Distribution can now be set in the free-text and modules import.
- Password complexity default tightened to allow passphrase-like in addition to password.
- Password regexp (can be considered a CTF-challenge for some users) is now available as a hint.
- **API** restsearch has been significantly improved allowing to support alternate download types from the restsearch (currently OpenIOC is supported). OpenIOC export and CIDR tool refactored.
- Organisation blacklist is now enabled by default and [sample UUIDs/organisations](https://www.circl.lu/doc/misp/book-convention/) are now blacklisted by default.
- **API** The "proposal to delete flag" is now available in the API output.
- Improved error handling when failing to add a tag.
- **API** Event history is now available via the API.
- Set comment field to an empty string in the attributes pre-validation (to avoid null comment field).
- Correlation can now be disabled for site admin even if (s)he is not the owner.

Various bugs fixed in the sharing group synchronisation and delegation. Improvements to the UI popups when using low-resolution (aka potato displays).

At the same time, a new version (2.4.71) of [PyMISP](https://github.com/MISP/PyMISP) has been released including multiple bug fixes.

Internet-Draft for [MISP core format](https://tools.ietf.org/html/draft-dulaunoy-misp-core-format-01) and [taxonomy](https://tools.ietf.org/html/draft-dulaunoy-misp-taxonomy-format-02) updated to the latest version along with the respective JSON schema used for validation.

The full change log is available [here](https://www.misp.software/Changelog.txt).

Don't hesitate to [open an issue](https://github.com/MISP/MISP/issues) if you have any feedback, found a bug or want to propose new features.
