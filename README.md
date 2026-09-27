# AffectNet

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FAffectNet-181717?logo=github)](https://github.com/biometric-community/AffectNet)
[![Access: register](https://img.shields.io/badge/access-register-important.svg)](http://mohammadmahoor.com/affectnet/)

**AffectNet** — tbiom catalog packaging for `affectnet` (expression; access `register`). Docs/helpers only; obtain data via upstream registration.

- **Dataset repository**: https://github.com/biometric-community/AffectNet
- **Upstream source**: http://mohammadmahoor.com/affectnet/
- **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
- **License (data)**: upstream terms — this packaging does **not** relicense or redistribute gated data

| Field | Value |
|-------|-------|
| Catalog id (tbiom) | `affectnet` |
| Category | `expression` |
| Access | `register` |
| Upstream homepage | http://mohammadmahoor.com/affectnet/ |

## TL;DR

- **Access**: **register** — obtain data from the upstream homepage / license process
- **This mirror**: documentation + download helpers only (no bulk payload in git)
- **Notes**: Large facial expression dataset; request required.

## Download

### Clone this repository

```bash
git clone git@github.com:biometric-community/AffectNet.git
cd AffectNet
```

### tbiom monorepo helper

```bash
bash projects/datasets/scripts/download_affectnet.sh
```

Place licensed archives under `projects/datasets/affectnet/` (gitignored).

## Dataset structure

```text
AffectNet/
├── README.md
├── LICENSE
├── .gitignore
└── extracted/   # local only after you obtain upstream data
```

## License

Helpers/docs: CC BY 4.0. Dataset files: upstream license / registration agreement.

## Contact

- Upstream: http://mohammadmahoor.com/affectnet/
- Packaging: https://github.com/biometric-community/AffectNet/issues
