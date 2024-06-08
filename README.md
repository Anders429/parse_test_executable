# parse_test_executable

Simple program to extract executable path from `cargo test` output.

Specifically, this requires json output from running
`cargo test --no-run --message-format=json`. The executable path is printed to `stdout`.

The primary use of this program is in continuous integration, allowing the test executable to
be obtained programmatically.

## License
This project is licensed under either of

* Apache License, Version 2.0
([LICENSE-APACHE](https://github.com/Anders429/parse_test_executable/blob/HEAD/LICENSE-APACHE) or
http://www.apache.org/licenses/LICENSE-2.0)
* MIT license
([LICENSE-MIT](https://github.com/Anders429/parse_test_executable/blob/HEAD/LICENSE-MIT) or
http://opensource.org/licenses/MIT)

at your option.

### Contribution
Unless you explicitly state otherwise, any contribution intentionally submitted for inclusion in the work by you, as defined in the Apache-2.0 license, shall be dual licensed as above, without any additional terms or conditions.
