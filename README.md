# :construction: scan-action-tests :construction:

This repository holds some directories and Github Action workflows to exercise functional testing of the scan-action project.

## Separate workflows
There is one `.github/workflows` directory and another, top-level `workflows` directory. This is because the functional tests that require validation for failures use [act](https://github.com/nektos/act) a tool that runs Github workflows locally.

The workflows that rely on `act` aren't hooked up yet.
