
# 1.1.0 (2016-02-06)

  * Merge branch 'master' of https://github.com/finboxio/node-safestart
  * accept literally any dependency version (doesn't have to follow semver semantics) if expected version is *

# 1.0.0 (2016-01-09)

  * upgrade packages
  * better test names
  * more accurate match
  * remove extra newline
  * ignore git branch mismatches when expected url has implicit head

# 0.8.0 (2015-07-29)

  * @mblakele: add support for file: dependencies

# 0.7.1 (2015-07-07)

  * @defunctzombie: fix regression

# 0.7.0 (2015-07-06)

  * @defunctzombie: fix handling of git dependencies
    - support for github:user/repo#hash shorthand
    - better normalization against installed _resolved url
    - add tests for git dependency matching
  * support "engine-strict" in addition to "engineStrict"

# 0.6.0 (2015-04-17)

  * fix cache install issues by using `_resolved` instead of `_from` for git repos

# 0.5.0

  * support for optionalDependencies

# 0.4.0

  * loose semver matching support (resolves weirdly formatted semver problems)

# 0.3.1

  * support for github style short dependencies

# 0.3.0

  * support git repos by checking `_from` field
  * add more information to error object

# 0.2.0

  * upgrade to semver 2.2.1

# 0.1.3

  * ignore http/https/git urls

# 0.1.2

  * only test engines.node if engineStrict is true

# 0.1.1

  * initial version
