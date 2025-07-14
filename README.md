RealLifeDeveloper: github-workflows
===================================

A number of reusable workflows and actions that are used when building and deploying [RealLifeDeveloper](https://reallifedeveloper.com/)
projects.

The `.github/workflows` directory also contains some workflows that are used to release this project and that are not reusable.
It is unfortunately not possible to place workflows under a `reusable` sub-directcory; GitHub requires all workflows to be in the
`workflows` directory. This makes it hard to see which workflows are reusable, and which are only used to build this project.
As a hint, if a workflow only has the trigger `on: workflow_call:`, it is reusable. The reusable workflows should also have a
comment stating this fact.

You are free to use this code in your own projects as you see fit, see the [license](LICENSE).

If you encounter any problems or have any suggestions for improvements, please use the Github issue tracking system:
https://github.com/reallifedeveloper/rld-build-tools/issues

For more information, see <https://reallifedeveloper.com/>.
