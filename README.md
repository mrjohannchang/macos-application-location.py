# macos-application-location.py

This tiny module helps you to obtain the path of an Application (.app) that the current process is running from on macOS.

## Installation

```sh
pip install macos-application-location
```

## Usage

```py
import pathlib

import macos_application_location


app_path: pathlib.Path = macos_application_location.get()
```
