# See here for image contents: https://github.com/microsoft/vscode-dev-containers/tree/v0.140.1/containers/rust/.devcontainer/base.Dockerfile

FROM mcr.microsoft.com/vscode/devcontainers/rust:0-1

# Setup Nightly -- Rocket.rs requires nightly
# Update Rust & Cargo -- Rocket.rs requires Absolute latest
RUN rustup default nightly && rustup update && cargo update


# [Optional] Uncomment this section to install additional packages.
# RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
#     && apt-get -y install --no-install-recommends <your-package-list-here>
