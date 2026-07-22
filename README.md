# setup terragrunt

- currently version 1.1.1

## install

- execute the script bash

```sh
curl -sSfL --proto '=https' --tlsv1.2 https://terragrunt.com/install | bash
```

```sh
==> Fetching latest version...
==> Installing Terragrunt v1.1.1 for linux/amd64
==> Downloading Terragrunt v1.1.1...
==> Downloading checksums...
Warning: Skipping release attestation verification: requires GitHub CLI (gh) v2.81.0 or later
==> Downloading GPG signature...
==> Importing Gruntwork GPG key...
==> Verifying GPG signature...
==> Signature verified
==> Verifying SHA256 checksum...
==> SHA256 checksum verified
==> Creating installation directory: /home/user/.terragrunt/bin
==> Installing to /home/user/.terragrunt/bin/terragrunt...
==> Terragrunt v1.1.1 installed successfully to /home/user/.terragrunt/bin/terragrunt

To add terragrunt to your PATH, run:

  echo 'export PATH="/home/user/.terragrunt/bin:$PATH"' >> /home/user/.bashrc
  source /home/user/.bashrc

Run 'terragrunt --help' to get started.
For documentation, visit: https://docs.terragrunt.com/
```

- please remember to add the following configuration

```sh
To add terragrunt to your PATH, run:

  echo 'export PATH="/home/user/.terragrunt/bin:$PATH"' >> /home/user/.bashrc
  source /home/user/.bashrc
```

## references

- please review [doc terragrunt install](https://docs.terragrunt.com/getting-started/install/)
