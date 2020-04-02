pkgname=browsh-bin
_pkgname=browsh
pkgdesc='A fully interactive, realtime, and modern text-based browser rendered to TTYs and browsers'
pkgver=1.6.4
pkgrel=1
arch=('x86_64')
url=https://www.brow.sh/
license=('LGPLv2')
source=(https://github.com/${_pkgname}-org/${_pkgname}/releases/download/v${pkgver}/${_pkgname}_${pkgver}_linux_amd64)
sha256sums=('d0bbdfe07e1494bb097dcff6290f17f98f6e3e5546f17139223b75d97c1caab5')
depends=('firefox>=63')

package(){
	install -Dm755 ${srcdir}/${_pkgname}_${pkgver}_linux_amd64 ${pkgdir}/usr/bin/${_pkgname}
}
