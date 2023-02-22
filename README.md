Archiving in favor of https://github.com/marketplace/actions/bump-homebrew-formula

# brew-publish
Updates the given Homebrew formula version and sends a pull request with the
change.

Originally authored by [@mislav][mislav], this utility was extracted from
[ruby-build][]'s scripts. The brew-publish script itself has not been modified.
In addition to extracting the script to its own repo, a package.json has been
added so it can be installed via npm. (There is no intention of *publishing*
the script to npm. Rather, it can be installed via github URL.)

## Dependencies

- git
- [hub][]

[ruby-build]: https://github.com/rbenv/ruby-build
[mislav]: https://github.com/mislav
[hub]: https://github.com/github/hub
