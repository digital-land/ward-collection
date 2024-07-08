# Ward collection

[![License](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/digital-land/ward-collection/blob/main/LICENSE)
[![Run pipeline](https://github.com/digital-land/ward-collection/actions/workflows/run.yml/badge.svg)](https://github.com/digital-land/ward-collection/actions/workflows/run.yml)

The data and pipeline to build the [Ward dataset](https://www.digital-land.info/dataset/ward).

# Updating the collection

We recommend working in [virtual environment](http://docs.python-guide.org/en/latest/dev/virtualenvs/) before installing the python [requirements](requirements.txt), [makerules](https://github.com/digital-land/makerules) and other dependencies. Requires Make v4.0 or above.

    $ make makerules
    $ make init
    $ make collect

# Building the datasets

The collected files can then be converted into a national dataset:

    $ make

# Licence

The software in this project is open source and covered by the [LICENSE](LICENSE) file.

Individual datasets copied into this repository may have specific copyright and licensing, otherwise all content and data in this repository is
[© Crown copyright](http://www.nationalarchives.gov.uk/information-management/re-using-public-sector-information/copyright-and-re-use/crown-copyright/)
and available under the terms of the [Open Government 3.0](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/) licence.
