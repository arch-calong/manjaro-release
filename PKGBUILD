# Maintainer: Guinux <nuxgui@gmail.com>

pkgname=manjaro-release
pkgver=21.1.0rc1
pkgrel=2
pkgdesc="Manjaro's release definition"
arch=("any")
url="https://manjaro.org/"
license=('GPL2')
depends=('lsb-release')
source=('lsb-release')
install="manjaro-release.install"
sha256sums=('e6244adc93001c5d05f92fcf47ff7d71441da976afdbb66e48ecb25737bd9a16')

#pkgver() {
    #parse lsb-release
#    grep 'DISTRIB_RELEASE='  lsb-release | cut -d '=' -f2
#}

package() {
    # Copy files
    mkdir -p ${pkgdir}/etc
    install -m644 ${srcdir}/lsb-release ${pkgdir}/etc/
}
