# mkdocs-template
MkDocs site template, including automated deployment workflows.

## Structure

Default folder structure in this template:
```sh
.
├─ config/
│    ├─ base.yml  # Shared base config file.
│    ├─ en/
│    │   └─ mkdocs.yml  # Override config file for "en".
│    └─ zh-Hans/
│        └─ mkdocs.yml  # Override config file for "zh-Hans".
│
├─ source/
│    ├─ en/
│    └─ zh-Hans/
│
├─ overrides/
│    ├─ assets/
│    │   └─ logo.png
│    └─ css/
│        └─ extra.css
│
└─ build/
```
