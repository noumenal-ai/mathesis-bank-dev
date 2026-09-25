# mathesis-bank-dev

A preview of the `dev` branch of [noumenal-ai/mathesis-bank](https://github.com/noumenal-ai/mathesis-bank), served at https://noumenal-ai.github.io/mathesis-bank-dev/. The published record is https://noumenal-ai.github.io/mathesis-bank/.

This repository holds only the workflow that builds it, [`preview.yml`](.github/workflows/preview.yml). Every 15 minutes it checks whether `dev` has moved and, if it has, rebuilds the site with mathesis-bank's own `bank/tools/build-site.sh`. To rebuild at once, open Actions → preview → Run workflow.
