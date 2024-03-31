# Maintainer: Guinux <nuxgui@gmail.com>

pkgname=manjaro-release
pkgver=23.1.4
pkgrel=1
pkgdesc="Manjaro's release definition"
arch=("any")
url="https://manjaro.org/"
license=('GPL2')
depends=('lsb-release')
source=('lsb-release')
install="manjaro-release.install"
sha256sums=('3b1b7c541b9deec07ea18ddc7a4a7164e8f20fba1ea0a4ccebca97d6131cb338')

#pkgver() {
    #parse lsb-release
#    grep 'DISTRIB_RELEASE='  lsb-release | cut -d '=' -f2
#}

package() {
    # Copy files
    mkdir -p ${pkgdir}/etc
    install -m644 ${srcdir}/lsb-release ${pkgdir}/etc/
}
