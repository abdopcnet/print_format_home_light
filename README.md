# Print Format

![Version](https://img.shields.io/badge/version-19.1.2026-blue)


## Overview
Print Format is an application designed to provide customizable and efficient print templates for various business needs. It allows users to define and manage print formats for invoices, receipts, and other documents.

## Features
- Customizable print templates.
- Integration with ERP systems.
- Support for multiple document types.

## Requirements
- Python 3.8 or higher.
- Frappe Framework.

## Structure
The app is structured as follows:
- `print_format/`: Contains the main application logic.
- `templates/`: Includes HTML templates for print formats.
- `static/`: Holds static files like CSS and JavaScript.

## Versions
- Current Version: 1.0.0
- Compatible with Frappe Framework v15.

## References
- App Name: `print_format`
- App Title: `print_format`
- App Publisher: `future_support`
- App Description: `print_format`
- App Email: `abdopcnet@gmail.com`
- App License: `MIT`
- GitHub Repository: [Print Format Home Light](https://github.com/abdopcnet/print_format_home_light.git)

### Print Format

Print Format

### Installation

You can install this app using the [bench](https://github.com/frappe/bench) CLI:

```bash
cd $PATH_TO_YOUR_BENCH
bench get-app $URL_OF_THIS_REPO --branch develop
bench install-app print_format
```

### Contributing

This app uses `pre-commit` for code formatting and linting. Please [install pre-commit](https://pre-commit.com/#installation) and enable it for this repository:

```bash
cd apps/print_format
pre-commit install
```

Pre-commit is configured to use the following tools for checking and formatting your code:

- ruff
- eslint
- prettier
- pyupgrade

### License

mit
