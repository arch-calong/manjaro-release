# Maintainer: Guinux <nuxgui@gmail.com>

pkgname=manjaro-release
pkgver=20.2.1
pkgrel=1
pkgdesc="Manjaro's release definition"
arch=("any")
url="https://manjaro.org/"
license=('GPL2')
depends=('lsb-release')
source=('lsb-release')
install="manjaro-release.install"
sha256sums=('5d6b08e53b82ec3d69d7c0ba6be361d96f43e4f52e88d93f0f4b5e256f6d8ecf')

pkgver() {
    #parse lsb-release
    grep 'DISTRIB_RELEASE='  lsb-release | cut -d '=' -f2
}

package() {
    # Copy files
    mkdir -p ${pkgdir}/etc
    install -m644 ${srcdir}/lsb-release ${pkgdir}/etc/
}
