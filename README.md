# Dark Nova

Dark Nova is a colorful theme with semantic token / highlighting support.

## Language Support

First-class language support:
- Rust
- TOML
- JSON
- YAML
- NASM / Assembly language

Basic, rudimentary support:
- JavaScript
- TypeScript
- Unix/Linux shell
- PowerShell
- Just

Other languages will be supported on a best-effort basis until I have more free time.

## Stability

**Unstable** / **pre-alpha** software.

Despite the theme being in its infancy, I am already using it as my "daily driver". Thus, you can be
sure that updates will be frequent and anything broken will promptly be fixed!

## Development Status

This project is under active development and will receive frequent updates until it reaches a point
of stability that I am comfortable with. Please use at your own risk, as there **will be** many
**breaking changes** as I iron out the issues and get the palette's colors to play well with each other.

### Roadmap

- [ ] CSS color parser
  - [ ] Hex strings (`#RRGGBB` / `#RRGGBBAA`)
  - [ ] RGB / RGBA
  - [ ] HSL / HSLA
- [ ] Theme generator
  - [ ] Automate process of adding, removing and modifying colors
  - [ ] Generate color variants to reflect context
    - This is to provide better support for modifiers such as `public`, `declaration`, etc.

### Miscellaneous

I am simply a developer and, although I try my best, I am not a designer. If you experience issues
regarding colors clashing in ways that you disapprove of, or if something is not working right, please
open an issue on GitHub.

## Contributing

Please visit the project [GitHub page][project-repo], open a new ticket that outlines the scope of
your contribution(s) and be ready to discuss your changes. I will respond to you as quickly as possible.
Once your changes are approved, you can open a pull request and I will merge your contribution.

Following the above steps is the best way to ensure your contribution is accepted.

Thank you!!

## License

This project is licensed under the [MIT license][license].

### Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted for inclusion in
[`dark-nova`][project-repo] by you, shall be licensed as MIT, without any additional terms or conditions.

<!-- Links section -->

[project-repo]: https://github.com/peter-donovan/dark-nova-theme/
[extension-url]: https://marketplace.visualstudio.com/items?itemName=dark-nova.dark-nova
[license]: https://github.com/peter-donovan/dark-nova-theme/blob/main/LICENSE