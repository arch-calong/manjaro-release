# Maintainer: Guinux <nuxgui@gmail.com>

pkgname=manjaro-release
pkgver=18.0.4
pkgrel=1
pkgdesc="Manjaro's release definition"
arch=("any")
url="https://manjaro.org/"
license=('GPL2')
depends=('lsb-release')
source=('lsb-release')
install="manjaro-release.install"
sha256sums=('6c9f0427f49f1070a18caa878f675c2211caa6d429b43c289ea717e43cb13a90')

package() {
    # Copy files
    mkdir -p ${pkgdir}/etc
    install -m644 ${srcdir}/lsb-release ${pkgdir}/etc/

}
