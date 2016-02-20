TOML-ABNF
====
#### TOML-ABNF is the unofficial [ABNF](https://en.wikipedia.org/wiki/Augmented_Backus%E2%80%93Naur_Form) for the latest ([v0.4.0](https://github.com/mojombo/toml/blob/master/versions/en/toml-v0.4.0.md)) tagged version of TOML.
The ABNF under the abnf branch of the [toml-lang/toml](https://github.com/toml-lang/toml) is out of date and doesn't allow a lot of things that examples and tests in the official TOML repository do. I added new productions and changed existing ones to allow for the example behaviors and changed formatting a bit to match advice given in RFC 4234. Since my pull request of ABNF changes hasn't been merged I'm declaring this repository the **Official Location of the Unofficial TOML ABNF**.

TOML
====
Tom's Obvious, Minimal Language.

By Tom Preston-Werner.

Latest tagged version:
[v0.4.0](https://github.com/mojombo/toml/blob/master/versions/en/toml-v0.4.0.md).

Be warned, this spec is still changing a lot. Until it's marked as 1.0, you
should assume that it is unstable and act accordingly.

Objectives
----------

TOML aims to be a minimal configuration file format that's easy to read due to
obvious semantics. TOML is designed to map unambiguously to a hash table. TOML
should be easy to parse into data structures in a wide variety of languages.

See [toml-lang/toml](https://github.com/toml-lang/toml) for a detailed non-formal specification of TOML v0.4.0.
