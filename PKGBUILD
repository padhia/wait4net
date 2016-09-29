pkgname=wait4net
pkgver="1.3"
pkgrel="1"
pkgdesc="wait for network to get connected, then optionally run a command"
arch=('any')
license=('GPL')
source=("$pkgname")
md5sums=('SKIP')

package() {
    install -Dm755 "${srcdir}/$pkgname" "${pkgdir}/usr/bin/$pkgname"
}
