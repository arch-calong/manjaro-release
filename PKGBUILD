# Maintainer: Guinux <nuxgui@gmail.com>

pkgname=manjaro-release
pkgver=19.0.0
pkgrel=1
pkgdesc="Manjaro's release definition"
arch=("any")
url="https://manjaro.org/"
license=('GPL2')
depends=('lsb-release')
source=('lsb-release')
install="manjaro-release.install"
sha256sums=('f1c003a91af544b26b9a59d17a0dfd9e643f8c12ebd3c18880e5afd282f936ae')

package() {
    # Copy files
    mkdir -p ${pkgdir}/etc
    install -m644 ${srcdir}/lsb-release ${pkgdir}/etc/

}
