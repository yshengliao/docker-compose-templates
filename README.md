# Docker Compose Templates

[English](README.md) | [繁體中文](README.hant.md)

---

Welcome to my Docker Compose template repository! 🎉 This is where I store all the handy scripts I use to spin up services quickly. Whether you need a simple development setup or something more sophisticated, this collection has you covered. Think of it as a toolbox—grab what you need and launch! 🚀

## Docker Guide

To get started with these templates, make sure you have Docker installed. You can follow the installation instructions on the [Docker website](https://docs.docker.com/get-docker/). Docker Compose is a powerful tool that simplifies managing multiple containers locally.

Once you’re set up, use the following command in any folder containing a `docker-compose.yml` file:

```bash
docker-compose up -d
```

When you’re finished, you can shut down all the containers with:

```bash
docker-compose down
```

That’s all it takes! 🚀

## Directory Structure

- `docker-compose.yml`: The default template for a quick start.
- Subdirectories: Specialized setups for specific environments or services.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/yshengliao/docker-compose-templates.git
   ```

2. Navigate to the template you want:

   ```bash
   cd docker-compose-templates/<template-directory>
   ```

3. Launch the services:

   ```bash
   docker-compose up -d
   ```

## Docker Compose Version Notice

As of newer versions of Docker Compose, the `version` attribute in the `docker-compose.yml` file is no longer required. I’ve removed it from all templates in this repository to ensure compatibility with the latest versions and reduce confusion.

## License

This work is licensed under the CC0 1.0 Universal (CC0 1.0) Public Domain Dedication. Feel free to copy, modify, or distribute it—even for commercial use—without needing to ask permission.

For more details, see the [LICENSE](./LICENSE) file or check the full legal text at <https://creativecommons.org/publicdomain/zero/1.0/legalcode>.

## Disclaimer

These templates are used by the author for personal development. Be sure to evaluate their suitability for your own needs, especially in production environments. The author makes no guarantees regarding the functionality, security, or stability of these configurations.
