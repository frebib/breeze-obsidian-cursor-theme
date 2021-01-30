# Maintainer: Jeremy Pope <jpope at jpope dot org> PGP-Key: E00B4261
pkgname=breeze-obsidian-cursor-theme
pkgver=1.0
pkgrel=4
pkgdesc="Breeze Obsidian cursor theme."
arch=("any")
url="https://kver.wordpress.com/2015/01/09/curses-i-mean-cursors/"
license=("GPL")
makedepends=("zstd")

source=("Breeze_Obsidian.tar.zst")
sha512sums=("ab9bec46ead51bcc90b1b2f4348ef2f88d9e7ff60bfe21133381a7e5869e5fd24e422307380e585021281f418349fa821a51987767bb459af901a77b052768da")

package() {
    cd $srcdir/Breeze_Obsidian
    install -d $pkgdir/usr/share/icons/Breeze_Obsidian
    cp -rf *   $pkgdir/usr/share/icons/Breeze_Obsidian
    chmod -R 644 $pkgdir/usr/share/icons/Breeze_Obsidian/*
    chmod 755 $pkgdir/usr/share/icons/Breeze_Obsidian
    chmod 755 $pkgdir/usr/share/icons/Breeze_Obsidian/cursors
}
