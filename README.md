> gh-install: Install pre-built binaries from github

[![Build Status](https://dev.azure.com/crate-ci/crate-ci/_apis/build/status/gh-install%20v1?branchName=master)](https://dev.azure.com/crate-ci/crate-ci/_build/latest?definitionId=8&branchName=master)

## Usage

Download the script for your platform:
- [bash](v1/install.sh)
- [powershell](v1/install.ps1)

and run it

```bash
$ ./install.sh --git <org>/<repo>
```

or use the Azure Pipeline template ([example](v1/azure-pipelines.yml)).

## License

Licensed under either of

 * Apache License, Version 2.0, ([LICENSE-APACHE](LICENSE-APACHE) or http://www.apache.org/licenses/LICENSE-2.0)
 * MIT license ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)

at your option.

### Contribution

Unless you explicitly state otherwise, any contribution intentionally
submitted for inclusion in the work by you, as defined in the Apache-2.0
license, shall be dual licensed as above, without any additional terms or
conditions.
