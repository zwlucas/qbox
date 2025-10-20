# QBox Basement

A ready-to-use QBox base, using Git Submodules for simplified resource management.

## 📋 Features

- Complete and configured QBox server
- Resource management via Git Submodules
- Simplified script updates
- No need for txAdmin for initial installation

## 🚀 Installation

### Prerequisites

- Git installed
- FiveM Server installed

### Steps

1. Clone the repository with submodules:
```bash
git clone --recurse-submodules https://github.com/zwlucas/qbox.git
```

2. Enter the project folder:
```bash
cd qbox
```

3. Configure your `server.cfg` as needed

4. Start the server

## 🔄 Updating Scripts

To update all resources to their latest versions:

```bash
git submodule update --remote --merge
```

To update a specific submodule:

```bash
git submodule update --remote --merge resources/[resource-name]
```

## 📦 Adding New Resources

To add a new resource as a submodule:

```bash
git submodule add [repository-URL] resources/[resource-name]
```

## 🤝 Contributing

Contributions are welcome! Feel free to open issues and pull requests.

## 📄 License

This project is under the MIT License.

