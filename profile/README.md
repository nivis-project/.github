<p align="center">
  <img src="https://nivis.tf/favicon.svg" alt="Nivis" width="120">
</p>

<h3 align="center">Terraform resources as Nix values.</h3>

<p align="center">
  Describe real infrastructure in a Nix flake instead of HCL. Nivis drives unmodified
  Terraform and OpenTofu providers, and what the cloud returns flows back into Nix.
</p>

<p align="center">
  <a href="https://nivis.tf">Website</a> ·
  <a href="https://github.com/nivis-project/nivis#quickstart">Quick start</a> ·
  <a href="https://registry.nivis.tf">Registry</a> ·
  <a href="https://github.com/nivis-project/nivis/discussions">Discussions</a>
</p>

| Project                                                       | Status           |                                                                                         |
|---------------------------------------------------------------|------------------|-----------------------------------------------------------------------------------------|
| [nivis](https://github.com/nivis-project/nivis)               | early but real   | The library and executor. Provider resources as Nix values, applied to a fixpoint.      |
| [registry](https://github.com/nivis-project/registry)         | alpha            | Providers, modules and blueprints with Nix-native documentation.                        |
| [nivis-tunnel](https://github.com/nivis-project/nivis-tunnel) | proof of concept | Deploy NixOS closures to machines with no inbound ports, over a Noise-encrypted relay. |
| [nivis-demos](https://github.com/nivis-project/nivis-demos)   |                  | Runnable examples, from offline fakes to real AWS.                                      |

Try it without cloning:

    nix run github:nivis-project/nivis#nivis -- --version
