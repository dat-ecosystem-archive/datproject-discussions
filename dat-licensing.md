# Dat Project licensing hygiene

All _Dat Project_ sub-projects and modules are free open source software. In order to ensure this remains so, that everyone can freely use our code, and that no authors or the project are sued later by trolls, we'll follow the following simple licensing hygiene steps.


All repositories:

- must be licensed with [BSD-2-clause](http://opensource.org/licenses/BSD-2-Clause), [BSD-3-clause](http://opensource.org/licenses/BSD-3-Clause), [MIT](http://opensource.org/licenses/MIT), or [Apache-2.0](http://opensource.org/licenses/Apache-2.0)
- must include a `LICENSE` file
- must include a `contributors.md` file
- must include a `cla-notice.md`
- should include a `collaborators.md`
- must be noted in the [dat-modules.md](dat-modules.md) list in this repo (this can get annoying for minor repos, so lazy load it: do it when you receive a PR?)

(`dat-project init`? :D)


Before merging a Pull Request:

- PR author must sign CLA
- PR merger must check for CLA ([clahub](http://www.clahub.com) will check this as a build step once it works)
- PR merger must make sure repo is in [dat-modules.md](dat-modules.md).


### `LICENSE`

See https://github.com/maxogden/dat/blob/master/LICENSE

### `contributors.md`

Use `contributor`. See: https://github.com/maxogden/dat/blob/master/contributors.md

### `collaborators.md`

Use `collaborator`. See: https://github.com/maxogden/dat/blob/master/collaborators.md

### `cla-notice.md`

We need something like this because we don't want to have individual CLAs per module (ZOMG THE FRICTION!), but we do want a blanket one for the whole project.

First draft:

> All contributions are done so under the Dat Project Contributors License Agreement, and are licensed accordingly. In order to protect the open source nature of Dat, all pull request authors must sign the aggreement at <link>. The agreement text can be viewed at https://github.com/datproject/meta/blob/master/dat-cla.md

See: https://github.com/maxogden/dat/blob/master/cla-notice.md (note: not there yet)
