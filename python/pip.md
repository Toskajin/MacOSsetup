# pip

macOS comes with Python so there's a chance `pip` is already installed on your machine.

### Installation <a id="installation"></a>

```text
$ curl https://bootstrap.pypa.io/get-pip.py > get-pip.py
$ sudo python get-pip.py
```

To verify `pip` is installed properly run

```text
$ pip --version
```

If it returns a version `pip` was successfully installed.

### Usage <a id="usage"></a>

Here are a few `pip` commands to get you started.

Install a Python package

```text
$ pip install <package>
```

Upgrade a package

```text
$ pip install --upgrade <package>
```

See what's installed

```text
$ pip freeze
```

Uninstall a package

```text
$ pip uninstall <package>
```

