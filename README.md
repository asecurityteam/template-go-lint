<a id="markdown-template-go-lint" name="template-go-lint"></a>
# template-go-lint - Standard GolangCI-Lint configuration for Atlassian Security

<https://github.com/asecurityteam/template-go-lint>

- [template-go-lint - Standard GolangCI-Lint configuration for Atlassian Security](#template-go-lint)
    - [Overview](#overview)
    - [Quick Start](#quick-start)
    - [Configuration](#configuration)
    - [Status](#status)
    - [Contributing](#contributing)
        - [Building And Testing](#building-and-testing)
        - [Quality Gates](#quality-gates)
        - [License](#license)
        - [Contributing Agreement](#contributing-agreement)

<!-- /TOC -->

<a id="markdown-overview" name="overview"></a>
## Overview<!-- TOC -->

This project contains our standard linter configuration that we include with
all Go services. Currently, we leverage golangci-lint.

<a id="markdown-quick-start" name="quick-start"></a>
## Quick Start

Using our SDCLI helper:

```sh
sdcli go add-lint
```

Using cookiecutter (our template engine) directly:

```sh
pip install cookiecutter
cookicutter gh:asecurityteam/template-go-lint
```

<a id="markdown-status" name="status"></a>
## Status

This project is in incubation which means we are not yet operating this tool in production
and the interfaces are subject to change.

<a id="markdown-contributing" name="contributing"></a>
## Contributing

<a id="markdown-license" name="license"></a>
### License

This project is licensed under Apache 2.0. See LICENSE.txt for details.

<a id="markdown-contributing-agreement" name="contributing-agreement"></a>
### Contributing Agreement

Atlassian requires signing a contributor's agreement before we can accept a
patch. If you are an individual you can fill out the
[individual CLA](https://na2.docusign.net/Member/PowerFormSigning.aspx?PowerFormId=3f94fbdc-2fbe-46ac-b14c-5d152700ae5d).
If you are contributing on behalf of your company then please fill out the
[corporate CLA](https://na2.docusign.net/Member/PowerFormSigning.aspx?PowerFormId=e1c17c66-ca4d-4aab-a953-2c231af4a20b).
