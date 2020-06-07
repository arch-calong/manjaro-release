# Maintainer: Guinux <nuxgui@gmail.com>

pkgname=manjaro-release
pkgver=20.0.3
pkgrel=1
pkgdesc="Manjaro's release definition"
arch=("any")
url="https://manjaro.org/"
license=('GPL2')
depends=('lsb-release')
source=('lsb-release')
install="manjaro-release.install"
sha256sums=('18110cf22edd39c9cc83e6135e6aa2b7af3b726840d7a154e03db84334f166ec')

package() {
    # Copy files
    mkdir -p ${pkgdir}/etc
    install -m644 ${srcdir}/lsb-release ${pkgdir}/etc/
}
