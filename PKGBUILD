pkgname=2gis-ulanude
pkgver=42
pkgrel=1
pkgdesc="Map of Ulan-Ude for 2GIS, July 2014"
arch=('i686' 'x86_64')
url="http://info.2gis.ru/ulan-ude/products/download#linux"
license=('custom')
depends=('2gis>=3.14.7.0')
source=("http://download.2gis.com/arhives/2GISData_Ulanude-42.orig.zip")
md5sums=('7c5a826bb268e18e61aeca58bf38e88f')

package() {
  install -D -m 644 "${srcdir}/2gis/3.0/Data_Ulanude.dgdat" "${pkgdir}/opt/2gis/2gis-ulanude.dgdat" || return 1
  
}
