---
title:  "Cara menghapus total atom editor"
date:   2017-01-05 07:00:00
categories: [developer, editor]
tags: [developer, editor, atom]
---

Setelah menimbang dsb, mengingat dsb, akhirnya saya memutuskan untuk beralih ke Visual Studio Code (VS Code). Entah apa karena saya masih agak awam dengan Atom Editor, saya mencoba dengan beralih ke VS Code.

Nah, agar saya tidak mengingat lagi kenangan lama saya dengan Atom Editor (`biar move on`), saya akan menghapus yang berhubungan dengan Atom Editor.

Ternyata, untuk menghapus sampai bersih saja harus teliti dimana letaknya. Tidak cukup hanya mengandalkan aplikasi Clean My Mac 3.

``` ruby
rm -rf ~/.atom
rm -rf /usr/local/bin/atom
rm -rf /usr/local/bin/apm
rm -rf /Applications/Atom.app
rm -rf ~/Library/Preferences/com.github.atom.plist
rm -rf "~/Library/Application Support/com.github.atom.ShipIt"
rm -rf "~/Library/Application Support/Atom"
rm -rf "~/Library/Saved Application State/com.github.atom.savedState"
rm -rf ~/Library/Caches/com.github.atom
rm -rf ~/Library/Caches/Atom
```

Nah, copas saja code di atas, ke dalam Terminal, kemudian tekan `Enter`.
Semoga bermanfaat dan bisa `move on` ke VS Code.