# Maintainer: Guinux <nuxgui@gmail.com>

pkgname=manjaro-release
pkgver=18.1.4
pkgrel=1
pkgdesc="Manjaro's release definition"
arch=("any")
url="https://manjaro.org/"
license=('GPL2')
depends=('lsb-release')
source=('lsb-release')
install="manjaro-release.install"
sha256sums=('040b3d92d2c263eb88347fd283aa83b1589ea0a2e72af8b38b081fad610fda96')

package() {
    # Copy files
    mkdir -p ${pkgdir}/etc
    install -m644 ${srcdir}/lsb-release ${pkgdir}/etc/

}
