# Contributor: max1m <mr[dot]mxm86[at]gmail[dot]com>
     
pkgname=2gis-ulanude
pkgver=25
pkgrel=1
pkgdesc="Map of Ulan-Ude for 2GIS, February 2013"
arch=('i686' 'x86_64')
url="http://ulanude.2gis.ru/how-get/linux/"
license=('custom')
depends=('2gis>=3.12.0.2')
source=("http://download.2gis.ru/arhives/2GISData_Ulanude-25.orig.zip")
md5sums=('8b6c2161c88da7669aff99401e78187e')
     
build() {
     
   cd $startdir
     
# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Ulanude.dgdat "${startdir}/pkg/opt/2gis/ulanude.dgdat" || return 1
  install -D -m 644 ${startdir}/src/2gis/3.0/Plugins/DGisLan/Ulanude.dglf "${startdir}/pkg/opt/2gis/Plugins/DGisLan/Ulanude.dglf" || return 1
     
}

