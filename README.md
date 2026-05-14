# Nexus-Q CLI

This is the standalone Windows compiler for the **Nexus-Q** programming language.

## Installation

You can install the compiler globally on your system using `npm` directly from GitHub. This bypasses common browser download warnings and sets up the executable in your system PATH automatically.

```bash
npm install -g github:adornia0/nexusq-cli
```

## Usage

Once installed, you can use the `nexusq` command from any terminal:

```bash
# Check version
nexusq --version

# View AI reference manual
nexusq --docs

# Compile a file or directory to check syntax
nexusq compile <file.n6q|dir>

# Run a script locally
nexusq run script.n6q --payload '{"key": "value"}'

# Start the Web Host RESTful API
nexusq serve ./my_scripts --port 2823
```

*Note: Currently, only the Windows 64-bit architecture is supported.*

## License

Copyright © 2026 NEXUS-Q Project. All rights reserved.
