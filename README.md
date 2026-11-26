# A repository of Forge models, checked on every pull request

The bagel shop of [Forge's guide](https://github.com/mollendorff-ai/forge/blob/main/docs/guide/02-a-first-model.md), `bagel.yaml` and the `costs.yaml` it includes, calculated, with the workflow of [the guide's pipeline page](https://github.com/mollendorff-ai/forge/blob/main/docs/guide/pipeline.md) in `.github/workflows/forge.yml`.

Its workflow installs Forge 10.0.0-rc.35, where `forge validate` itself fails a formula with no stored result, so one step checks every model: a stored result out of date or missing fails it, and the results come out as JSON and on the run's page.

Its pull requests are the page's examples: one that changes the price to 18 and calculates (it passes), one that changes it and does not (it fails at `forge validate`), and one that adds a formula without its result (it fails at `forge validate` too). The two that fail are not to be merged.
