# Maintainer: Guinux <nuxgui@gmail.com>

pkgname=manjaro-release
pkgver=18.1.0
pkgrel=1
pkgdesc="Manjaro's release definition"
arch=("any")
url="https://manjaro.org/"
license=('GPL2')
depends=('lsb-release')
source=('lsb-release')
install="manjaro-release.install"
sha256sums=('c4c8bf7064a36d505c2db50c4d92e44f36eee18aa5c8d847b84a4101e52955bc')

package() {
    # Copy files
    mkdir -p ${pkgdir}/etc
    install -m644 ${srcdir}/lsb-release ${pkgdir}/etc/

}
