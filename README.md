# PyTorch Foundation Landscape

![P Landscape Logo](https://raw.githubusercontent.com/pytorch/pytorch/0d4cedaa47c7ee22042eb24e87eb3cfe95502404/docs/source/_static/img/pytorch-logo-dark.svg)

- [PyTorch Landscape](#pytorch-foundation-landscape)
  * [Interactive Version](#interactive-version)
  * [New Entries](#new-entries)
  * [Corrections and vulnerability-reporting](#Corrections-and-vulnerability-reporting)
  * [Non-Updated Items](#non-updated-items)
  * [License](#license)

This landscape is intended as a map to explore the projects in the PyTorch Foundation Ecosystem. It is modeled after the Cloud Native Computing Foundation (CNCF) [landscape](https://landscape.cncf.io) and based on the same open source code.

## Interactive Version

Please see [pytorch.landscape2.io](https://pytorch.landscape2.io/)

## New Entries

* Projects must be open source and hosted on or mirrored to GitHub.
* If you would like your project to be considered to join the Ecosystem, submit a request to [Join the Ecosystem](https://pytorch.org/ecosystem/join)
* New projects are submitted to the PyTorch Ecosystem Working Group, a sub-group of the PyTorch Technical Advisory Council.  If approved they will be added to the landscape by Foundation staff. 
* Projects are placed in the category that best suits them. We are unlikely to create a new category for projects as we'd rather find the best home with the current options.
* All projects need a logo and the logo needs to include the name. Once approved, please plan to submit a logo for your project.  If you need help with creating a logo, reach out the PyTorch Foundation team and they will assist you, by sending an email to support@pytorch.org. 
* Crunchbase organization should be the company or organization that manages the project. 


## Corrections and vulnerability-reporting
* Please open an [issue](https://github.com/pytorch/landscape/issues/new) or, for sensitive information, email  to support@pytorch.org.  

* If the error is with data from [Crunchbase](https://www.crunchbase.com/) you should open an account there and edit the data. If you don't like a project description, edit it in GitHub. If your project isn't showing the license correctly, you may need to paste the unmodified text of the license into a LICENSE file at the root of your project in GitHub, in order for GitHub to serve the license information correctly.

## External Data

The canonical source for all data is [landscape.yml](landscape.yml). Once a day, we download data for projects and companies from the following sources:

* Project info from GitHub
* Funding info from [Crunchbase](https://www.crunchbase.com/)
* Market cap data from Yahoo Finance
* CII Best Practices Badge [data](https://bestpractices.coreinfrastructure.org/)

The update server enhances the source data with the fetched data and saves the result in [processed_landscape.yml](processed_landscape.yml). The app loads a JSON representation of processed_landscape.yml to display data.

## Non-Updated Items

We generally archive open source projects that have not had a commit in over 1 year. Note that for projects not hosted on GitHub, we need them to mirror to GitHub to fetch updates, and we try to work with projects when their mirrors are broken. Here is view of projects sorted by last update: https://landscape.pytorch.io/grouping=no&license=open-source&sort=latest-commit

## License

This repository contains data received from [Crunchbase](http://www.crunchbase.com). This data is not licensed pursuant to the Apache License. It is subject to Crunchbase’s Data Access Terms, available at [https://data.crunchbase.com/v3.1/docs/terms](https://data.crunchbase.com/v3.1/docs/terms), and is only permitted to be used with this Landscape Project which is hosted by the Linux Foundation.

Everything else is under the Apache License, Version 2.0, except for project and product logos, which are generally copyrighted by the company that created them, and are simply cached here for reliability. The trail map, static landscape, serverless landscape, and [landscape.yml](landscape.yml) file are alternatively available under the [Creative Commons Attribution 4.0 license](https://creativecommons.org/licenses/by/4.0/).



