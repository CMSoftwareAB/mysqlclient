In a Linux environment:

install wget if not installed
dnf -y install wget

download source code for mysqlclient:
https://pypi.org/project/mysqlclient/#files

Unpack:
tar axvf mysqlclient-<version>

Install dependencies (dnf install):
- mysql-devel
- pkgconfig

/opt/python-3.12.2/bin/python3 -m pip install build
