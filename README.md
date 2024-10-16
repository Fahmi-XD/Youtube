Script tampilan Youtube sederhana yang dibuat menggunakan html dan css. Ini belum responsive jadi kalau dibuka di laptop / pc akan berantakan. Jika ingin membuatnya jadi responsive, silahkan tambahkan kode css ini:

``` Css
/* Untuk desktop */
@media screen and (min-width: 1024px) {
  // Kode css
}

/* Tablet */
@media screen and (min-device-width: 768px) and (max-device-width: 1024px) {
  // Kode css
}

/* Ponsel ( Portrait ) */
@media screen and (max-device-width: 480px) and (orientation: portrait) {
  // Kode css
}

/* Ponsel ( Landscape ) */
@media screen and (max-device-width: 640px) and (orientation: landscape) {
  // Kode css
}

/* Ponsel ( Portrait atau Landscape ) */
@media screen and (max-device-width: 640px) {
  // Kode css
}

/* Untuk iPhone 4 ( Portrait atau Landscape ) */
@media screen and (min-device-width: 320px) and (-webkit-min-device-pixel-ratio: 2) {
  // Kode css
}

/* Untuk iPhone 5 ( Portrait atau Landscape ) */
@media (device-height: 568px) and (device-width: 320px) and (-webkit-min-device-pixel-ratio: 2) {
  // Kode css
}

/* Untuk iPhone 6 dan 6 plus ( Portrait atau Landscape ) */
@media (min-device-height: 667px) and (min-device-width: 375px) and (-webkit-min-device-pixel-ratio: 3) {
  // Kode css
};
```

Perlu diingat ini hanya untuk media querynya saja, selebihnya bisa kamu tambahkan sendiri.
