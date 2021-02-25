# Sandbox Python SDK

Welcome to the FSI Sandbox SDK for Python. See the [fsi-sdk topic](https://github.com/topics/fsi-sdk) for other available SDKs

## Installation

```bash
pip3 install innovation-sandbox
```

> If you are using Python 2.7 use pip instead. Depending on your permissions, you might need to use `pip install --user innovation-sandbox` to install it.

You can also download the source code from [the repository](https://github.com/fsi-sandbox/fsi-sdk-python), and then just install the package using

```bash
python setup.py install
```

## Usage documentation for APIs currently supported by this SDK

*   [Nibss](https://github.com/fsi-sandbox/fsi-sdk-python/tree/main/nibss)
*   [Sterling](https://github.com/fsi-sandbox/fsi-sdk-python/tree/main/sterling)
*   [Atlabs](https://github.com/fsi-sandbox/fsi-sdk-python/tree/main/atlabs)
*   [Union](https://github.com/fsi-sandbox/fsi-sdk-python/tree/main/union)

## Tests

Just type in the following command to run the tests

```bash
py.test
```

This will run the test defined in the files of the `tests/` directory

## Dependencies

To Download and install all the module dependencies, just type

```bash
pip install -r requirements.txt
```