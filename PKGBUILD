pkgname=ttf-baloo-2
pkgver=1.0.0
pkgrel=1
pkgdesc="Baloo 2 sans-serif font"
arch=('any')
license=('OFL')
source=("https://gwfh.mranftl.com/api/fonts/baloo-2?download=zip&subsets=latin&variants=500,600,700,800,regular&formats=ttf")
sha256sums=("0cb95c8120e34454978e521caeb2c74060869cc3b82653a24ee90f033dea02c9")

package() {
	install -dm 755 "$pkgdir"/usr/share/fonts/TTF
	install -Dm644 ./*.ttf "$pkgdir"/usr/share/fonts/TTF
}
