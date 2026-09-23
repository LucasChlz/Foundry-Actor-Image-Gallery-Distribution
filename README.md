# Actor Image Gallery — Free Distribution

Public distribution repository for the Free edition of **Actor Image Gallery**, a system-agnostic Foundry VTT module for organizing Actor images, editing non-destructive portrait/token presets, and switching appearances quickly.

## Install in Foundry VTT

Use this manifest URL in **Add-on Modules → Install Module → Manifest URL**:

```text
https://github.com/LucasChlz/Foundry-Actor-Image-Gallery-Distribution/releases/latest/download/module.json
```

The release assets contain only the Foundry runtime (`scripts`, `styles`, `lang`, `module.json`, and `LICENSE`). Development files, tests, internal documentation, and local Patreon test overrides are not included.

## Editions

- **Free:** the public package available here.
- **Patreon:** premium extensions will be developed in a separate private repository and will use the Free module as their base.

Issues for the distributed module can be reported in this repository.

## Release integrity

Each release includes:

- `module.json`
- `actor-image-gallery-VERSION.zip`
- `actor-image-gallery-VERSION.zip.sha256`

The checksum can be used to verify that the downloaded ZIP matches the validated build.
