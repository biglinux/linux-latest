# Maintainer: Barnabé di Kartola <barnabedikartola@gmail.com>

pkgname=linux-latest
pkgver=6.1.7
kernelver=61
pkgrel=2
epoch=1
pkgdesc="Latest Kernel Version for BigLinux"
arch=('any')
url="https://github.com/biglinux/$pkgname"
license=('GPL3')
depends=("linux${kernelver}" "linux${kernelver}-headers")
provides=('linux-latest-headers')
replaces=('linux60' 'linux60-headers')
source=("git+${url}.git")
md5sums=('SKIP')
if [ -e "${pkgname}.install" ];then
    install=${pkgname}.install
fi
