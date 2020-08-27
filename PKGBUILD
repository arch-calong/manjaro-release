# Maintainer: Guinux <nuxgui@gmail.com>

pkgname=manjaro-release
pkgver=20.1
pkgrel=0.1
pkgdesc="Manjaro's release definition"
arch=("any")
url="https://manjaro.org/"
license=('GPL2')
depends=('lsb-release')
source=('lsb-release')
install="manjaro-release.install"
sha256sums=('e71c9db543ecf82d3b056a3cfabbdccf20efb4ca3e427a0062ad936dfbf3435a')

package() {
    # Copy files
    mkdir -p ${pkgdir}/etc
    install -m644 ${srcdir}/lsb-release ${pkgdir}/etc/
}
