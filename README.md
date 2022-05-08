# Simple Recipes Cookbook

> _Create your own online cookbook with minimal effort_

To get your own online cookbook set up:

- [Fork](https://github.com/engeir/simple-recipes-cookbook/fork) this repository.
- Change the links set up in [retype.yml](./retype.yml)
  - This means that you change `engeir` to your own GitHub username. (Note that you can
    change everything else as well, but these two must be updated.)
- Set up workflows to be run in the forked repository.
  - Workflows are not run by default in repositories that are forked, but this can be
  turned on. Move to the `Actions` page of you repository to turn them on.
- Finally, go to `Settings -> Pages` in your repository, and set GitHub pages to be
  built from the `retype` branch.