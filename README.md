# Release Please Monorepo Example

Welcome to the **Release Please Monorepo Example** repository! 
This repository is designed to showcase the usage of **release-please** in a monorepo setup.

## Overview

This example demonstrates how to automate versioning and changelog generation for multiple packages within a single repository using **release-please**. 

## Project Structure

This repository includes the following projects:

1. **Cargo Crate**: A Hello World Rust project managed using Cargo.
2. **React Project**: A Hello World JavaScript project built with React.

## Key Files

- **[.release-please-manifest.json](.release-please-manifest.json)** - This file contains the version declarations for the packages in the repository.
- **[release-please-config.json](release-please-config.json)** - Configuration for release please.
- **[release-please.yml](.github%2Fworkflows%2Frelease-please.yml)** - GitHub workflow that triggers the automated release process. This action relies on the **.release-please-manifest.json** and **release-please-config.json** files.

If you're configuring release please for your project, check out [different strategy types](https://github.com/googleapis/release-please?tab=readme-ov-file#strategy-language-types-supported) for handling releases.
In this project `rust` and `node` are used.

## Learn More

For detailed instructions on automating GitHub releases with Release Please, read my guide [Automate GitHub Releases with Release Please](https://www.amarjanica.com/automate-github-releases-with-release-please)
or [watch my youtube tutorial](https://youtu.be/70YgbPh6pXA).

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
