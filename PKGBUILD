pkgname=wsdd2
pkgver=1.8
pkgrel=2
url=""
pkgdesc="WSDD and LLMNR daemon"
arch=('x86_64' 'armv7h')
license=('GPL3')
sources=('wsd.c'
         'wsdd2.8'
         'wsdd.h'
         'llmnr.c'
         'Makefile'
         'wsdd2.c'
         'wsdd2.service'
         'wsd.h')

build() {
    cd ..
	make
}

package() {
    cd ..
	make DESTDIR="$pkgdir/" install
}
