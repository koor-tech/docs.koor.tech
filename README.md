# docs.koor.tech

## Development

Any documentation to the [koor-tech/koor Repository](https://github.com/koor-tech/koor) are automatically pushed from the CI in that repo to this repositories' `gh-pages` branch with a combination of [`mike`](https://github.com/jimporter/mike) and [`mkdocs`](https://www.mkdocs.org/).

At this momentn, to make changes to the "website" code, you should add/make changes on the main branch (via pull requests) and then `git cherry-pick COMMIT` them over to the `gh-pages` branch.
