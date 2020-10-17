# Maintainer: Guinux <nuxgui@gmail.com>

pkgname=manjaro-release
pkgver=20.2pre
pkgrel=1
pkgdesc="Manjaro's release definition"
arch=("any")
url="https://manjaro.org/"
license=('GPL2')
depends=('lsb-release')
source=('lsb-release')
install="manjaro-release.install"
sha256sums=('2f636b7ae44ed84bda3559fec9bd1c1f23d57075d07ec6a8a4d5b7c6e34c3f21')

package() {
    # Copy files
    mkdir -p ${pkgdir}/etc
    install -m644 ${srcdir}/lsb-release ${pkgdir}/etc/
}
