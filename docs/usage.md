# Usage

To use Indonesia Name and Address Preprocessing in a project

```
from nama_alamat.preprocessing import Preprocessing
preprocessing_nama = Preprocessing(tipe='nama')
strings = 'IR SULAEMAN'
print(preprocessing_nama.preprocessing(strings))
```

```
from nama_alamat.preprocessing import Preprocessing
preprocessing_alamat = Preprocessing(tipe='alamat')
strings = 'JALAN GARUDA IX BLOK C/3 RT 003 RW 002, JAKARTA UTARA, DKI JAKARTA 12110'
print(preprocessing_alamat.preprocessing(strings))
```
