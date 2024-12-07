# nixos-test

[![Hercules CI](https://hercules-ci.com/api/v1/site/github/account/beeman/project/nixos-test/badge)](https://hercules-ci.com/github/beeman/nixos-test/status)
# Usage as a flake

[![FlakeHub](https://img.shields.io/endpoint?url=https://flakehub.com/f/beeman/nixos-test/badge)](https://flakehub.com/flake/beeman/nixos-test)

Add nixos-test to your `flake.nix`:

```nix
{
  inputs.nixos-test.url = "https://flakehub.com/f/beeman/nixos-test/*.tar.gz";

  outputs = { self, nixos-test }: {
    # Use in your outputs
  };
}

```
