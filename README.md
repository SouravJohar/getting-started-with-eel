# getting-started-with-eel
The simplest and fastest way to create applications with a Web UI and a Python backend.


## Getting Started
- Install eel, pyqrcode, and pyinstaller

```sh
$ pip install eel pyqrcode pyinstaller
```

- Run the app

```sh
$ python QRCode.py
```

## Packaging the app
YOu can pass any valid `pyinstaller` flag in the following command to further customize the way your app is built.
```sh
$ python -m eel web QRCode.py --noconsole --onefile -icon=barcode.icns
```
