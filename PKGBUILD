# Maintainer: Jeremie Astor <astor.jeremie@wanadoo.fr>
pkgname=tftray
pkgver=0
pkgrel=3
pkgdesc="minimal systray"
arch=(any)
url="http://sourceforge.net/projects/tftray"
license=('GPL')
groups=()
depends=('libx11')
source=(http://downloads.sourceforge.net/project/$pkgname/$pkgname-$pkgver.$pkgrel.tar.gz)

build() {
  cd "$srcdir"
  make
}

package() {
  cd "$srcdir"
  make DESTDIR="$pkgdir/" install
}
md5sums=('42d71539708bede97a6aa0f924ff109f')
