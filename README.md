# furyctl

Fury Web Forge Data Cluster Command Line Tool

`furyctl` is a CLI tool designed for managing and interacting with the Fury Web Forge Data Cluster. It provides a suite of commands for managing jobs, crawling data, monitoring cluster health, and performing various administrative tasks.

## Features

- **Data Crawling**: Start, stop, and monitor data crawls on the Fury Web Forge Data Cluster.
- **Job Management**: Manage job configurations and executions.
- **Health Monitoring**: Check the health status of the cluster components, including databases and network connectivity.
- **Interactive and Command-Line Usage**: Use furyctl in interactive mode or directly with command-line arguments.

## Installation

### Prerequisites

- Go 1.18 or higher
- Linux, macOS, or Windows

### Building from Source

1. Clone the repository:
    ```bash
    git clone https://github.com/your-org/furyctl.git
    cd furyctl
    ```

2. Build the CLI:
    ```bash
    go build -o furyctl .
    ```

3. (Optional) Move the binary to a directory in your `PATH`:
    ```bash
    mv furyctl /usr/local/bin/
    ```

## Usage

After installing, you can use `furyctl` from your terminal. Use `furyctl --help` to see available commands.

```bash
furyctl [command]
