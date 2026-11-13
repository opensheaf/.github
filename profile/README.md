<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://opensheaf.org/resources/brand/opensheaf-logo-dark.svg">
  <img alt="OpenSheaf" src="https://opensheaf.org/resources/brand/opensheaf-logo.svg" width="360">
</picture>

**OpenSheaf is an open format for archives of scholarly documents and for collections of them.**

Anyone (a person, a group, an institution) can keep an archive of their documents as plain files on a static website: sources and PDFs, every version fixed by content hashes and verifiable from the files alone, described with standard metadata, and composable into collections across archives without copying. It builds on established standards: [OCFL 1.1](https://ocfl.io/1.1/spec/) for storage and [DataCite 4.7](https://schema.datacite.org/) for description.

- **Specification:** [OpenSheaf 0.1](https://opensheaf.org/opensheaf-specification-0.1.html), a draft, and its [FAQ](https://opensheaf.org/faq.html)
- **Site:** [opensheaf.org](https://opensheaf.org)
- **Repositories:**
  - [opensheaf/opensheaf](https://github.com/opensheaf/opensheaf): the specification, its JSON Schemas and the site; the place to discuss them: open an [issue](https://github.com/opensheaf/opensheaf/issues) for questions and problems, or a pull request to propose changes
  - [opensheaf/opensheaf-py](https://github.com/opensheaf/opensheaf-py): the Python tools for OpenSheaf archives, the `osheaf` command (deposit, collections, verification, Zenodo and arXiv), the reference implementation of the specification
- **First archive:** [Papers of Massimiliano Gubinelli](https://mgubi.org/papers/)

**Getting started:**

- **Your own archive of papers:** [opensheaf/archive-template](https://github.com/opensheaf/archive-template) ([use this template](https://github.com/opensheaf/archive-template/generate)): sources, every version, a website on GitHub Pages and DOIs, maintained with `osheaf`.
- **A curated collection** of papers from any archives, such as a seminar's reading list or an overlay journal: [opensheaf/collection-template](https://github.com/opensheaf/collection-template) ([use this template](https://github.com/opensheaf/collection-template/generate)).
- **Examples:** [opensheaf/example-papers](https://github.com/opensheaf/example-papers), sample papers (TeXmacs, arXiv and Zenodo) for trying the tools.

**Status:** version 0.1 is a draft, still being finalised; it may change in incompatible ways before version 1.0.

The specification and FAQ are licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/), the JSON Schemas are dedicated to the public domain under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/), and the tools are under the GNU GPL, version 3 or later.
