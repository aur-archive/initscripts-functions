# Maintainer: Daniel YC Lin <dlin.tw at gmail>
# Contributor: sudokode <sudokode@gmail.com>
# Contributor: Tom Gundersen <teg@jklm.no>
# Contributor: Thomas Bächler <thomas@archlinux.org>
# Contributor: Aaron Griffin <aaron@archlinux.org>

pkgname=initscripts-functions
pkgver=2012.10.1
pkgrel=2
pkgdesc="Bash functions from the initscripts package"
arch=('any')
url="http://www.archlinux.org"
license=('GPL2')
depends=('bash')
conflicts=('initscripts')
source=("http://ftp.archlinux.org/other/initscripts/initscripts-${pkgver}.tar.xz")
md5sums=('a4a747e73819b81f2218cf5b9bd53703')
install=$pkgname.install

package() {
  cd ${srcdir}/initscripts-${pkgver}
  install -d -m755 ${pkgdir}/etc/rc.d
  install -m644 ./functions ${pkgdir}/etc/rc.d/functions
}
