# Source Code Part Time Program Hacktiv8
## Intro to Python for Data Science
### PYTHON-KS10 KAMPUS MERDEKA

Repositori ini merupakan arsip kode pada kelas PTP Python for Kampus Merdeka Batch 3 (PYTN-KS10).

## Catatan Instalasi
Tutorial ini memerlukan library berikut:

- Python versi 3.7+
- `numpy` versi 1.18 atau lebih: http://www.numpy.org/
- `scipy` versi 1.5 atau lebih: http://www.scipy.org/
- `matplotlib` versi 3.2 atau lebih: http://matplotlib.org/
- `ipython` versi 7.1 atau lebih, with notebook support: http://ipython.org
- `seaborn` versi 0.10 atau lebih

Instalasi termudah untuk mendapatkan library dengan versi yang kompatibel adalah dengan menginstal [conda](https://store.continuum.io/) environment manager.
Untuk yang versi compact, Anda dapat menginstall [miniconda](http://conda.pydata.org/miniconda.html).

Ketika conda telah terinstall, Anda dapat set virtual environment dan menginstall library yang dibutuhkan dengan cara:
```
$ conda create -n pelatihan_ml python=3.4.5 ipywidgets=5.2.2 numpy scipy matplotlib scikit-learn ipython-notebook seaborn pillow

$ activate pelatihan_ml

$ jupyter notebook --notebook-dir='<tutorial folder>'
```

Apabila anda tidak ingin repot menginstal library diatas secara terpisah, anda dapat menginstall bundel [Anaconda](https://anaconda.com/downloads), dengan catatan file ini cukup besar.

## Download Material Pelatihan
Untuk mendownload materi ini, saya menyarankan untuk menggunakan `git` agar dapat terus update repo ini dikemudian hari apabila ada perubahan. Pastikan anda sudah menginstall `git` pada komputer anda, lalu ketikkan perintah berikut pada *command prompt* atau *terminal*:

    git clone git@github.com:afifai/pythonks10-class.git

Apabila anda tidak / belum bisa menggunakan `git`, cara termudah adalah dengan klik tombol download yang ada diatas.
