# Revision history for haskell-flake

## `master` branch

- New features
  - #63: Add `config.haskellProjects.${name}.outputs` containing all flake outputs for that project.
- API changes
    - #37: Group `buildTools` (renamed to `tools`), `hlsCheck` and `hlintCheck` under the `devShell` submodule option; and allow disabling them all using `devShell.enable = false;` (useful if you want haskell-flake to produce just the package outputs).

## 0.1.0

- Initial release