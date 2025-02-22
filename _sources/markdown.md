# Sistem Persamaan Linear
### A. Definisi Sistem Persamaan Linear
Sistem persamaan linear merupakan salah satu topik yang penting dalam matematika. Sistem ini terdiri dari beberapa persamaan linear yang harus diselesaikan secara bersamaan. Persamaan linear sendiri merupakan persamaan yang memiliki bentuk umum seperti ax + by = c, di mana a, b, dan c adalah konstanta yang diketahui, sedangkan x dan y adalah variabel yang harus dicari.

Dalam sistem persamaan linear, terdapat dua jenis sistem yaitu sistem persamaan linear dengan dua variabel dan sistem persamaan linear dengan tiga variabel. Sistem persamaan linear dengan dua variabel memiliki dua persamaan dengan dua variabel yang harus dicari nilainya. Sedangkan sistem persamaan linear dengan tiga variabel memiliki tiga persamaan dengan tiga variabel yang harus dicari nilainya

### B. Persamaan Linear Satu variabel
persamaan linear yang hanya memiliki satu variabel saja memiliki pangkat satu.
*         Contoh: 2x-9=1
          Penyelesaian: 2x−9=1
                          2x  = 1+9
                           x  = 10/2
                           x  = 5

### C. Persamaan Linear Dua variabel 
persamaan linear yang memiliki dua varibel, dengan pangkat satu.
*         Contoh: 2x+y=12
                  4x−y=0
          Penyelesaian: Mengeliminasi variabel x
                        2x+y= 12
                        4x−y= 0
                        ________+
                        6x  =12
                         x  =12/6
                         x  =2
                        Subtitusi variabel x ke persamaan 2
                        4(2)-y= 0
                        8   -y= 0
                            -y= 0 - 8
                            -y= -8
                             y= 8

            Jadi nilai variabel x,y adalah : (2,8)
​
 

### D. Persamaan Linear Tiga variabel
persamaan linear yang memiliki tiga varibel yang saling berhubungan.
*           Contoh: 2x+y+z= 5
                    x-2y+3z= 4
                    3x−y+2z= 12
            Penyelesaian: Mengeliminasi Z dengan menggunakan persamaan 1 dan 2

                    2x+y+z= 5 | (3)
                    x-2y+3z= 4 | (1)
                    Karna kita ingin mengeliminasi variabel Z kita harus menyamakan 
                    nilai dari variabel Z nya

                    6x+3y-3z= 15
                    x-2y+3z= 4
                    ____________+
                    7x+y   = 19   (persamaan ke 4)
                    Selanjutnya kita mengeleminasi Z pada persamaan 1 dan 3

                    2x+y+z= 5  | (2)                
                    3x−y+2z= 12| (1)
                    Menyamakan nilai dari variabel Z

                    4x+2y+2z= 10
                    3x-y+2z= 12
                    _____________+
                    7x+3y  = 22  (Persamaan ke 5)
                    Kita telah mendapatkan 2 persamaan 2 variabel
                    Langkah selanjutnya mengeliminasi salah 1 variabel dari 2 
                    persamaan yang di dapat

                    7x+y= 19
                    7x+3y= 22
                    _____________-
                      -2y= -3
                        y= -3/-2 = 3/2 
                    Selanjutnya kita subtitusi nilai y ke persamaan ke 4

                    7x+3/2= 19
                    7x    = 19-3/2
                    7x    = 38/2 - 3/2
                    x     = 35/2 * 1/7
                    x     = 35/14
                    x      = 5/2
                    Setelah mendapat kan nilai X dan Y 
                    kita subtitusi kan nilai X dan Y dengan persamaan ke 1

                    2(5/2)+3/2-z = 5
                    5+3/2-z      = 5
                         -z      = 5-5-3/2
                         -z      = -3/2
                          z      = 3/2
      Jadi nilai dari variabel X,Y,Z adalah (5/2, 3/2, 3/2)

### E. Macam-Macam Solusi Sistem Persamaan Linear
#### 1.  Satu solusi 
Satu solusi adalah ketika 2 garis berpotongan pada 1 titik
Contoh: 
<iframe scrolling="no" title="Tentukan himpunan penyelesaian dari sistem persamaan linier dua variabel" src="https://www.geogebra.org/material/iframe/id/hk6eusad/width/700/height/500/border/888888/sfsb/true/smb/false/stb/false/stbh/false/ai/false/asb/false/sri/false/rc/false/ld/false/sdz/true/ctl/false" width="700px" height="500px" style="border:0px;"> </iframe>

Here is a "note" directive:

```{note}
Here is a note
```

It will be rendered in a special box when you build your book.

Here is an inline directive to refer to a document: {doc}`markdown-notebooks`.


## Citations

You can also cite references that are stored in a `bibtex` file. For example,
the following syntax: `` {cite}`holdgraf_evidence_2014` `` will render like
this: {cite}`holdgraf_evidence_2014`.

Moreover, you can insert a bibliography into your page with this syntax:
The `{bibliography}` directive must be used for all the `{cite}` roles to
render properly.
For example, if the references for your book are stored in `references.bib`,
then the bibliography is inserted with:

```{bibliography}
```

## Learn more

This is just a simple starter to get you started.
You can learn a lot more at [jupyterbook.org](https://jupyterbook.org).
