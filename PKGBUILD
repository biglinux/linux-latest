# Maintainer: Barnabé di Kartola <barnabedikartola@gmail.com>

pkgname=('linux-latest' 'linux-latest-acpi_call' 'linux-latest-bbswitch' 'linux-latest-broadcom-wl' 'linux-latest-nvidia' 'linux-latest-nvidia-390xx' 'linux-latest-nvidia-470xx' 'linux-latest-r8168' 'linux-latest-rtl8723bu' 'linux-latest-tp_smapi' 'linux-latest-vhba-module' 'linux-latest-virtualbox-host-modules' 'linux-latest-zfs')
pkgver=6.2.6
kernelver=62
pkgrel=1
pkgdesc="Latest Kernel Version for BigLinux"
arch=('any')
url="https://github.com/biglinux/linux-latest"
license=('GPL3')
# depends=("linux${kernelver}" "linux${kernelver}-headers")
# provides=('linux-latest-headers')

package_linux-latest() {
depends=("linux${kernelver}" "linux${kernelver}-headers")
provides=('linux-latest-headers')
}

package_linux-latest-acpi_call() {
depends=("linux${kernelver}-acpi_call")
replaces=('linux60-acpi_call')
}

package_linux-latest-bbswitch() {
depends=("linux${kernelver}-bbswitch")
replaces=('linux60-bbswitch')
}
package_linux-latest-broadcom-wl() {
depends=("linux${kernelver}-broadcom-wl")
replaces=('linux60-broadcom-wl')
}
package_linux-latest-nvidia() {
depends=("linux${kernelver}-nvidia")
replaces=('linux60-nvidia')
}
package_linux-latest-nvidia-390xx() {
depends=("linux${kernelver}-nvidia-390xx")
replaces=('linux60-nvidia-390xx')
}
package_linux-latest-nvidia-470xx() {
depends=("linux${kernelver}-nvidia-470xx")
replaces=('linux60-nvidia-470xx')
}
package_linux-latest-r8168() {
depends=("linux${kernelver}-r8168")
replaces=('linux60-r8168')
}
package_linux-latest-rtl8723bu() {
depends=("linux${kernelver}-rtl8723bu")
replaces=('linux60-rtl8723bu')
}
package_linux-latest-tp_smapi() {
depends=("linux${kernelver}-tp_smapi")
replaces=('linux60-tp_smapi')
}
package_linux-latest-vhba-module() {
depends=("linux${kernelver}-vhba-module")
replaces=('linux60-vhba-module')
}
package_linux-latest-virtualbox-host-modules() {
depends=("linux${kernelver}-virtualbox-host-modules")
replaces=('linux60-virtualbox-host-modules')
}
package_linux-latest-zfs() {
depends=("linux${kernelver}-zfs")
replaces=('linux60-zfs')
}
