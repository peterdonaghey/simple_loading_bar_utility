# Loading Bar

## Introduction

`loading_bar` is a simple, lightweight Python utility for displaying a customizable loading bar in the console. It's designed for ease of use and flexibility, ideal for adding a visual progress indicator to your Python scripts and applications.

## Features

- Customizable bar length.
- Options to display or hide the percentage and iteration indicators.
- Easy integration into existing Python projects.

## Installation

Currently, the package is not hosted on PyPI, so you can install it directly from the source:

```bash
git clone https://github.com/peterdonaghey/loading_bar.git
cd loading_bar
pip install .
```

## Usage

To use `loading_bar` in your project, simply import and call the function in a loop:

```python
from loading_bar.loading_bar import loading_bar

total = 1000

for i in range(total):
    loading_bar(i, total)
```

## Customization

You can customize the loading bar by adjusting the following parameters:

`i`: Current iteration (int).

`total`: Total iterations (int).

`length`: Length of the loading bar (default is 50).

`show_percentage`: Flag to show or hide percentage (default is True).

`show_iterations`: Flag to show or hide iterations completed (default is True).

## License

This project is under the CC0 1.0 Universal (CC0 1.0) Public Domain Dedication. For more information, see LICENSE.

## Contributions

Contributions, issues, and feature requests are welcome! Feel free to check issues page.
