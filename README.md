# PyTorch Landscape

![PyTorch Landscape Logo](https://landscape.pytorch.org/images/left-logo.svg)

This landscape is intended as a map to explore open source projects and working groups hosted by PyTorch, open source projects in the energy and sustainability ecosystems, and also shows the PyTorch member companies. It is modeled after the Cloud Native Computing Foundation (CNCF) [landscape](https://landscape.cncf.io) and based on the same open-source code.

This repository contains the data files and images required to generate the [PyTorch landscape](https://landscape.pytorch.org). The software that generates it can be found at the [cncf/landscape2](https://github.com/cncf/landscape2) repository. Please see its [README file](https://github.com/cncf/landscape2#landscape2) for more information about how it works.

## New Entries

New entries to the landscape must be approved by the [PyTorch Ecosystem Working Group](https://github.com/pytorch-fdn/ecosystem). Projects wishing to become a PyTorch Ecosystem Project can apply [here](https://github.com/pytorch-fdn/ecosystem/issues/new).

## Corrections

Please open a pull request with edits to [landscape.yml](landscape.yml).

If the error is with data from [Crunchbase](https://www.crunchbase.com/) you should open an account there and edit the data. If you don't like a project description, edit it in GitHub. If your project isn't showing the license correctly, you may need to paste the unmodified text of the license into a LICENSE file at the root of your project in GitHub, in order for GitHub to serve the license information correctly.

### Updating PyTorch Members and Projects

PyTorch Member and Project data in this repository ( which in the [landscape.yml](landscape.yml) file are under categories `PyTorch Members` and `PyTorch Projects` ) are built nightly using the [LFX Landscape Tools](https://github.com/jmertic/lfx-landscape-tools). Any changes made directly in the data files in this repository for the above-referenced categories will be overwritten.

- For `PyTorch Members` entries, you can make these changes in [LFX Organization Dashboard](https://docs.linuxfoundation.org/lfx/organization-dashboard/organization-profile).
- For `PyTorch Projects` entries, those changes can be made in [LFX Project Control Center (PCC)](https://docs.linuxfoundation.org/lfx/project-control-center/v2-latest-version/operations/project-definition).

If you cannot access the above resources, please [create a helpdesk ticket](https://members.pytorch.org) to request those changes.

## Local Build and Install

You can build the landscape locally on your machine using the [landscape2](https://github.com/cncf/landscape2) tool. Once [installed](https://github.com/cncf/landscape2?tab=readme-ov-file#installation), you can use the commands below to build the landscape and serve it locally.

```shell
landscape2 build --data-file landscape.yml --settings-url https://raw.githubusercontent.com/cncf/landscape2-sites/refs/heads/main/pytorch/settings.yml --logos-path hosted_logos --output-dir build
landscape2 serve --landscape-dir build
```

## License

The generated landscape contains data received from [Crunchbase](http://www.crunchbase.com). This data is not licensed pursuant to the [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0.txt). It is subject to Crunchbase’s Data Access Terms, available at [https://data.crunchbase.com/docs/terms](https://data.crunchbase.com/docs/terms), and is only permitted to be used with PyTorch landscape projects.

Everything else is under the [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0.txt), except for projects and products logos, which are generally copyrighted by the company that created them, and are simply cached here for reliability. The generated landscape and the [landscape.yml](landscape.yml) file are alternatively available under the [Creative Commons Attribution 4.0 license](https://creativecommons.org/licenses/by/4.0/).
