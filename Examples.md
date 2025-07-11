# OSSL Examples of Citation and Use

This document provides examples of how to cite and apply the Open Source Synthesised Licence (OSSL) with specific Option configurations. These examples demonstrate how a Licencor can communicate their selected Options clearly and unambiguously.

---

## Basic Example — Defaults Only

If the Licensor wishes to apply OSSL with no changes to the default Options, they may simply cite the licence as follows:
```
Licenced under the Open Source Synthesised Licence (OSSL) v1.0
```

Or, more compactly:
```
OSSL-v1.0
```

Since no Option Codes are specified, the defaults listed in the **Foundation** section of the licence apply.

---

## Example with Selected Options

Suppose the Licensor wishes to disallow Commercial Use, waive Royalties, and remove the ethical use restriction. The appropriate Option Codes would be:

- `CU2` — Commercial Use prohibited
- `R2` — Royalties waived
- `E2` — No ethical use restriction

The licence citation would then be written as:
```
Licenced under the Open Source Synthesised Licence (OSSL) v1.0 with options: CU2-R2-E2
```

Or, more compactly:
```
OSSL-v1.0-CU2-R2-E2
```

---

## Example in a README.md

Below is an example of how to include the licence and Options within a project’s README:
```
## Licence

This project is licensed under the Open Source Synthesised License (OSSL) v1.0 with the following Options:

- CU2 — Commercial Use prohibited
- R2  — Royalties waived
- E2  — No ethical use restriction

Full licence text is available in the [LICENSE.md](./LICENSE.md) file.
```
Or, more compactly:
```
Licensed under OSSL-v1.0-CU2-R2-E2
See LICENSE.md for full details.
```

---

## Example in Legal Notices or About Sections:
```
This software is licensed under the Open Source Synthesised License (OSSL) v1.0 (Options: CU2-R2-E2). See accompanying documentation for full terms.

```

---

## Guidance for Licensees

Licensees should always refer to the cited Option Codes (if any) when determining the permissions and obligations for the Licensed Work.  
If no Option Codes are given, the defaults listed in the **Foundation** section of the licence apply.
