# A repository of Forge models, checked on every pull request

The bagel shop of [Forge's guide](https://github.com/mollendorff-ai/forge/blob/main/docs/guide/02-a-first-model.md), `bagel.yaml` and the `costs.yaml` it includes, calculated, with the workflow of [the guide's pipeline page](https://github.com/mollendorff-ai/forge/blob/main/docs/guide/pipeline.md) in `.github/workflows/forge.yml`.

Its pull requests are the page's examples: one that changes the price and calculates (it passes), one that changes it and does not (it fails at `forge validate`), and one that adds a formula without its result (it fails at the JSON check).
