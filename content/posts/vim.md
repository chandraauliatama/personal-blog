---
title: "Catatan: VIM"
date: 2022-01-27T18:07:58+07:00
draft: false
description: "Catatan saya tentang VIM dan shortcut yang saya ketahui"
tags: [Personal, Catatan, Pengetahuan]
---

{{< figure src="/images/vim-photo.jpg" caption="Photo by [Christin Hume](https://unsplash.com/christinhumephoto) on Unsplash" >}}

Dalam rangka menjadi _programmer_ yang lebih baik(jahh, sok iye luu!!) pada awal tahun 2022 ini saya memutuskan untuk mulai belajar menggunakan VIM lebih tepatnya _shortcut_ VIM, saya berharap dengan belajar _shortcut_ VIM ini kecepetan dan ketepatan saya sewaktu menulis code menjadi makin meningkat. nah buat yang belum tahu VIM itu apa mari saya jelaskan sedikit.

Simpelnya VIM merupakan sebuah program komputer berupa _text editor_ berbasis terminal, yang membedakan VIM dengan _text editor_ lain adalah kecanggihan atau banyaknya _shortcut_ yang bisa kita gunakan ketika melakukan pengeditan teks, sehingga kecepatan kita dalam mengedit suatu teks bisa lebih meningkat.

Keunggulan dalam hal _shortcut_ sendiri merupakan alasan terbesar saya untuk mulai belajar menggunakan VIM, sebenarnya saya tidak menggunakan VIM secara langsung, saya mengintegrasikan VIM dengan _code editor_ yang biasa saya gunakan yaitu [VS Code](https://code.visualstudio.com/), caranya sendiri terbilang sangat mudah, kita hanya perlu menginstal [ekstensi VIM](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim) pada VS Code.

## Shortcut yang sudah saya pelajari

Hanya berlaku pada normal mode:

| Syntax     | Fungsi                                                                                         |
| ---------- | ---------------------------------------------------------------------------------------------- |
| h          | mengeser kursor ke kiri                                                                        |
| j          | mengeser kursor ke atas                                                                        |
| k          | mengeser kursor ke bawah                                                                       |
| l          | mengeser kursor ke kanan                                                                       |
| w          | memindahkan kursor 1 kata                                                                      |
| W          | meminndahkan kursor 1 KATA                                                                     |
| e          | memindahkan kursor ke akhir kata berikutnya                                                    |
| E          | memindahkan kursor ke akhir KATA berikutnya                                                    |
| b          | memindahkan kursor 1 kata ke belakang                                                          |
| B          | memindahkan kursor 1 KATA ke belakang                                                          |
| f{char}    | (Find)mencari karakter sesuai pada parameter char                                              |
| F{char}    | (Find)mencari karakter sesuai pada parameter char ke belakang                                  |
| t{char}    | (unTil) mencari karakter sebelum karakter pada parameter char                                  |
| T{char}    | (unTil) mencari karakter sebelum karakter pada parameter char ke belakang                      |
| ;          | mengulangi perintah f, F, t, T                                                                 |
| ,          | mengulangi perintah f, F, t, T tapi secara terbalik                                            |
| gg         | pergi ke baris pertama                                                                         |
| G          | pergi ke baris terakhir                                                                        |
| zz         | memusatkan cursor agar berada pada tengah layar                                                |
| /{keyword} | mencari kata sesuai keyword kedepan pada semua baris                                           |
| ?{keyword} | mencari kata sesuai keyword kebelakang pada semua baris                                        |
| n          | mengulangi perintah /{keyword} dan ?{keyword} atau menuju ke hasil berikutnya yang sesuai      |
| p          | paste(tempel)                                                                                  |
| u          | undo(membatalkan perubahan terakhir)                                                           |
| ctrl+r     | membatalkan undo                                                                               |
| x          | menghapus karakter yang berada di kursor                                                       |
| s          | menghapus karakter yang berada di kursor dan masuk ke insert mode                              |
| i          | masuk ke insert mode                                                                           |
| I          | masuk ke insert mode pada awal baris                                                           |
| a          | masuk ke insert mode setelah kursor                                                            |
| A          | masuk ke insert mode pada akhir baris                                                          |
| o          | menambahkan baris baru di atas kursor dan masuk ke insert mode                                 |
| O          | menambahkan baris baru di atas kursor dan masuk ke insert mode                                 |
| d          | (Delete) menghapus. Harus dikombinasikan contoh "dd" menghapus 1 baris, "d2w" menghapus 2 kata |
| c          | (Change) mengubah, sama dengan perintah "d" hanya setelahnya masuk ke insert mode              |
| .          | mengulangi perubahan terakhir                                                                  |
| v          | masuk ke mode visual(seperti select dengan mouse)                                              |
| y          | copy atau yank(dalam VIM) untuk menyalin. Harus dikombinasikan dengan tombol lain              |
| Esc        | keluar dari insert mode atau visual mode                                                       |

Catatan:

1. KATA dan kata pada daftar shortcut merupakan 2 hal berbeda, (TES) = 3 kata, (TES) = 1 KATA.
2. List _shortcut_ akan terus di _update_ ketika saya mengetahui shortcut lain.
