# Maintainer: Guinux <nuxgui@gmail.com>

pkgname=manjaro-release
pkgver=18.1.1
pkgrel=1
pkgdesc="Manjaro's release definition"
arch=("any")
url="https://manjaro.org/"
license=('GPL2')
depends=('lsb-release')
source=('lsb-release')
install="manjaro-release.install"
sha256sums=('ffafb74206207e98b9f5f0c6afd45f21ea7f372e2b4db40c5a0e10b1c7a1defd')

package() {
    # Copy files
    mkdir -p ${pkgdir}/etc
    install -m644 ${srcdir}/lsb-release ${pkgdir}/etc/

}
