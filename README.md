# Scripts and notes for the IIPC COVID-19 web archive collection

This repository is intended for scripts and notes related to the work on
preparing the COVID-19 web archive collection by the International
Internet Preservation Consortium (IIPC) for publishing.

Currently, there are only 2 simple scripts: `list.sh` fetches the list
of files in the collection from the Web Archive Systems API (WASAPI),
and `get.sh` starts the file transfer job in parallel using
[llx](https://github.com/arcalex/llx).  Both scripts expect Archive-It
credentials to be in the `.netrc` file under the user's home directory.
