# Maintainer: Guinux <nuxgui@gmail.com>

pkgname=manjaro-release
pkgver=18.0.2
pkgrel=1
pkgdesc="Manjaro's release definition"
arch=("any")
url="https://manjaro.org/"
license=('GPL2')
depends=('lsb-release')
source=('lsb-release')
install="manjaro-release.install"
sha256sums=('dfdf114b58cb26e35c241ad955495fbde30e415900fbbf1a83936bf0fd75606c')

package() {
    # Copy files
    mkdir -p ${pkgdir}/etc
    install -m644 ${srcdir}/lsb-release ${pkgdir}/etc/

}
