# Maintainer: Guinux <nuxgui@gmail.com>

pkgname=manjaro-release
pkgver=22.0.3
pkgrel=1
pkgdesc="Manjaro's release definition"
arch=("any")
url="https://manjaro.org/"
license=('GPL2')
depends=('lsb-release')
source=('lsb-release')
install="manjaro-release.install"
sha256sums=('507dc2c5eecdacd2076a338373a3b921507b6dd0cff566cf3e863439e5690bad')

#pkgver() {
    #parse lsb-release
#    grep 'DISTRIB_RELEASE='  lsb-release | cut -d '=' -f2
#}

package() {
    # Copy files
    mkdir -p ${pkgdir}/etc
    install -m644 ${srcdir}/lsb-release ${pkgdir}/etc/
}
