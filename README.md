# Alchemize avatar library

The avatar models offered in the Alchemize platform's look library. The platform's catalog pins each file
here by tag and sha256, and fetches it on install and boot. Nothing in this repository is required at build time.

Layout: `looks/<id>@<version>/model.vrm` and `picture.png` (256 px, full body). A version is immutable: a changed model is a new version. `SHA256SUMS`
lists every file with its hash and size.

| Look | File |
|---|---|
| Genie (blue) | `looks/genie-blue@2/model.vrm` |
| Genie wizard | `looks/genie-wizard@1/model.vrm` |
| Genie tech | `looks/genie-tech@1/model.vrm` |
| Alchemist | `looks/alchemist@1/model.vrm` |
| Earth | `looks/earth@1/model.vrm` |
| Water | `looks/water@1/model.vrm` |
| Kosmos (companion) | `looks/companion-kosmos@1/model.vrm` |
| Alchemist (male) | `looks/alchemist-male@1/model.vrm` |
| Genie wizard (female) | `looks/genie-wizard-female@1/model.vrm` |

## License

© Alchemize Tech LLC. Free for anyone to use, modify and redistribute, with or without Alchemize.
