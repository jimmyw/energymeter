You need to checkout a specific esphome branch from

git@github.com:jimmyw/esphome.git

It should be possible to just:


external_components:
  - source: github://jimmyw/esphome
    components: [bl0910]

But i have not tested that.
