all runs: check
- `cmd.log`: full command line used to run the suite
- `git_head`: reference to master branch when the suite was run

* run01: first try run, took 24 hours
* run02: run with the same parameters (bar bugs :) ) of node-kubelet-serial in CI
* run03: run excluding the Eviction tests. Run 3 times to rule out lucky run.
