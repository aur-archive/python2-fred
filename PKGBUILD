# Maintainer: Your Name <oliver DOT sherouse AT gmail DOT com>
_pkgname=fred
pkgname=python2-$_pkgname
pkgver=2.5
pkgrel=1
pkgdesc="Python wrapper of the St. Louis Federal Reserve Bank's FRED API"
arch=('any')
url="http://pypi.python.org/pypi/fred/2.5"
license=('custom')
depends=('python2-requests' 'python2-relaxml')
options=(!emptydirs)
source=(http://pypi.python.org/packages/source/f/$_pkgname/$_pkgname-$pkgver.tar.gz)
md5sums=('8dc9fb8c7ee301096ac250422a33be7f')

package() {
  cd "$srcdir/$_pkgname-$pkgver"
  python2 setup.py install --root="$pkgdir/" --optimize=1
}

# vim:set ts=2 sw=2 et:
