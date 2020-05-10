# Maintainer: Guinux <nuxgui@gmail.com>

pkgname=manjaro-release
pkgver=20.0.1
pkgrel=1
pkgdesc="Manjaro's release definition"
arch=("any")
url="https://manjaro.org/"
license=('GPL2')
depends=('lsb-release')
source=('lsb-release')
install="manjaro-release.install"
sha256sums=('4973eaaa171b45abfab85b7cf456602c9be1861d8033ab50ab70aada9ec09f30')

package() {
    # Copy files
    mkdir -p ${pkgdir}/etc
    install -m644 ${srcdir}/lsb-release ${pkgdir}/etc/
}
