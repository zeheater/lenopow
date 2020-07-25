# Maintainer: Helmut Stult <helmut[at]manjaro[dot]org>

# Based on the code from:
# TildeHacker <contact@tildehacker.com>
# Lenovsky    <lenovsky@pm.me>

pkgname=lenopow
pkgver=1.0.0
pkgrel=1
pkgdesc="A script to enable/disable battery conservation mode in Lenovo Ideapad/LEGION notebooks."
arch=('any')
url="https://github.com/schinfo/lenopow"
license=('GPL3')
source=("git://github.com/schinfo/lenopow.git")
md5sums=('SKIP')

package() {
	cd "ideapad-conservation-mode"
	install -D "$pkgname" "$pkgdir/usr/bin/$pkgname"
}
