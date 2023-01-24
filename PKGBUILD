# Maintainer: Guinux <nuxgui@gmail.com>

pkgname=manjaro-release
pkgver=22.0.1
pkgrel=1
pkgdesc="Manjaro's release definition"
arch=("any")
url="https://manjaro.org/"
license=('GPL2')
depends=('lsb-release')
source=('lsb-release')
install="manjaro-release.install"
sha256sums=('1ee7a669440f5778e9cd10b5404927e6b88f8c2c4e3c151e2e658fb7536450ca')

#pkgver() {
    #parse lsb-release
#    grep 'DISTRIB_RELEASE='  lsb-release | cut -d '=' -f2
#}

package() {
    # Copy files
    mkdir -p ${pkgdir}/etc
    install -m644 ${srcdir}/lsb-release ${pkgdir}/etc/
}
