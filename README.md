# meson-rhel

To install Meson on RHEL 8.7, you can follow these steps:

Open a terminal on your RHEL 8.7 system.

Ensure your system is up to date by running the following command:
```
sudo dnf update
```

Install the required dependencies for building Meson:
```
sudo dnf install python3-devel python3-pip ninja-build
```

Once the dependencies are installed, use pip to install Meson:
```
pip3 install meson
```

**Note:** If pip3 is not installed, you can install it using the following command:
```
sudo dnf install python3-pip
```

Verify the installation by checking the Meson version:
```
meson --version
```
This should display the installed Meson version if the installation was successful.
