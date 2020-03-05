# Maintainer: Guinux <nuxgui@gmail.com>

pkgname=manjaro-release
pkgver=19.0.2
pkgrel=1
pkgdesc="Manjaro's release definition"
arch=("any")
url="https://manjaro.org/"
license=('GPL2')
depends=('lsb-release')
source=('lsb-release')
install="manjaro-release.install"
sha256sums=('be3e8378c4f70c67654648cc0171bc3fb1d41eb844714c8929fab339d59bc682')

package() {
    # Copy files
    mkdir -p ${pkgdir}/etc
    install -m644 ${srcdir}/lsb-release ${pkgdir}/etc/

}
