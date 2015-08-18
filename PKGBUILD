# Maintainer: Felix Yan <felixonmars@gmail.com>

pkgname=ydcv
pkgver=0.3.1
pkgrel=1
pkgdesc="YouDao Console Version - Simple wrapper for Youdao online translate (Chinese<->English) service API, as an alternative to the StarDict Console Version(sdcv)"
arch=("any")
url="https://github.com/felixonmars/ydcv"
license=("GPL")
depends=('python')
source=(
  "https://github.com/felixonmars/$pkgname/archive/$pkgver.tar.gz"
)

package() {
  install -Dm755 "${srcdir}/$pkgname-$pkgver/$pkgname.py" "${pkgdir}/usr/bin/$pkgname"
}

# vim:set ts=2 sw=2 et:
md5sums=('4a1d937dfd72f9911488b8e1e55d7ec5')
