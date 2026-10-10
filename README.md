# bromigOS Homebrew tap

This tap installs tools maintained by [bromigOS](https://bromigos.org).

To install [mehshell](https://github.com/bromigos-org/mehshell), the fast zsh prompt:

```bash
brew tap bromigos-org/tap
brew install mehshell
```

Initialise it in your zsh startup file:

```zsh
eval "$(mehshell init zsh)"
```

See mehshell's README for its config and bromigOS integration. Its release workflow
updates the formula here. Changes to the binary belong in the mehshell repository.
