# Maintainer: Michal Kimle <kimle.michal@gmail.com>
pkgname=perun-slave-base
pkgver=3.1.8
pkgrel=1
pkgdesc="Perun slave base scripts"
arch=('any')
url="https://github.com/CESNET/perun"
license=('unknown')
depends=('bash')
source=("ftp://depot1.mc.cesnet.cz/pool/main/${pkgname}_${pkgver}_amd64.deb")
md5sums=('5368826e8ee92587312ffa15855f1c46')

package() {
        tar xfp ${srcdir}/data.tar.gz -C ${pkgdir}/
        rm -r ${pkgdir}/usr/
        rm -r ${pkgdir}/var/
        chmod -R 755 ${pkgdir}/opt/perun
}
