# rules-us

US Federal rules in Akoma Ntoso XML format.

## Structure

```
usc/                    # US Code (statutes)
├── 26/                 # Title 26 - Internal Revenue Code
│   ├── 32/             # Section 32 - EITC
│   └── ...
├── 7/                  # Title 7 - Agriculture (SNAP)
└── ...

cfr/                    # Code of Federal Regulations
├── 26/                 # Title 26 - IRS regulations
├── 7/                  # Title 7 - SNAP regulations
└── ...

guidance/               # Agency guidance documents
├── irs/                # IRS Rev Procs, Rulings, Notices
└── ssa/                # SSA POMS
```

## Format

All documents are in [Akoma Ntoso](https://www.oasis-open.org/committees/legaldocml/) XML format, 
the UN-backed OASIS standard for legislative documents.

## Related Repositories

- [rac-us](https://github.com/CosilicoAI/rac-us) - Executable encodings of these rules
- [arch](https://github.com/CosilicoAI/arch) - Source document archive and converters

## License

Public domain source material. Conversion tools under MIT license.
