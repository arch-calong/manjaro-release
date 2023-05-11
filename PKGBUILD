# Maintainer: Guinux <nuxgui@gmail.com>

pkgname=manjaro-release
pkgver=22.1.1
pkgrel=1
pkgdesc="Manjaro's release definition"
arch=("any")
url="https://manjaro.org/"
license=('GPL2')
depends=('lsb-release')
source=('lsb-release')
install="manjaro-release.install"
sha256sums=('df337100f620985ef61656f9a44618361da99b69edc1346cde21d052b082b14f')

#pkgver() {
    #parse lsb-release
#    grep 'DISTRIB_RELEASE='  lsb-release | cut -d '=' -f2
#}

package() {
    # Copy files
    mkdir -p ${pkgdir}/etc
    install -m644 ${srcdir}/lsb-release ${pkgdir}/etc/
}
