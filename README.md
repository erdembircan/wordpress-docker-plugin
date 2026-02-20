# wordpress-docker-plugin

A Claude Code plugin that sets up a WordPress development environment using Docker with WP-CLI, MariaDB, and Xdebug.

## Features

- WordPress with Xdebug pre-configured for debugging
- MariaDB database with health checks
- WP-CLI for automated WordPress installation and management
- Query Monitor plugin installed by default
- Interactive environment configuration

## Installation

```bash
claude plugin add erdembircan/wordpress-docker
```

## Usage

Invoke the skill with:

```
/wordpress-docker:wordpress-docker-setup
```

The skill will guide you through:

1. Copying Docker template files to your project
2. Configuring environment variables (database, admin credentials, ports, etc.)
3. Setting up project-specific Docker volume and network names
4. Providing access details for the WordPress site

## License

AGPL-3.0-or-later. See [LICENSE](LICENSE) for details.
