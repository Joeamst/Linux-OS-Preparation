# Linux 20.04 Focal Fosa OS Preparation
Repository ini berisi tahapan memulai Linux untuk Skripsi

Library dan package yang di gunakan pada penyusunan Tugas Akhir diantara lain:

- Pip
- Git
- Drone Kit
- PyMavlink
- Numpy
- Matplolib
- Open CV & Open CV Contrib

## Menginstall Package dan Library

### Install Pypi 

Buka terminal pada linux
Masukan syntax di bawah ini:
```
$ sudo apt-get update
$ sudo apt-get upgrade

```

Lalu masukan

```
$ sudo apt install python3-pip

```

Jika sudah selesai maka masukan:

```
$ pip3 --version
```

### Install Git
Buka terminal pada linux
Masukan syntax di bawah ini: 

```
$ sudo apt install git
```
Tunggu hingga proses selesai, jika sudah maka masukan syntax di bawah ini untuk mengecek versi git

```
$ git --version
```

### Install Drone Kit
Buka terminal pada linux
Masukan syntax di bawah ini: 

```
$ sudo pip install dronekit
```
atau 
```
$ sudo pip3 install dronekit
```

### Install Pymavlink
Buka terminal pada linux
Masukan syntax di bawah ini: 

```
$ pip install pymavlink
```

### Install Numpy
Buka terminal pada linux
Masukan syntax di bawah ini:
```
$ pip install numpy
```

### Install Matplotlib
Buka terminal pada linux
Masukan syntax di bawah ini:
```
$ pip install matplotlib
```

### Install Open-CV Contrib
Buka terminal pada linux
Masukan syntax di bawah ini:
```
$ sudo apt-get update && sudo apt-get upgrade
```

Lalu install tools
```
$ sudo apt-get install build-essential cmake pkg-config
$ sudo apt-get install libjpeg-dev libtiff5-dev libjasper-dev libpng12-dev
$ sudo apt-get install libavcodec-dev libavformat-dev libswscale-dev libv4l-dev
$ sudo apt-get install libxvidcore-dev libx264-dev
$ sudo apt-get install libgtk2.0-dev libgtk-3-dev
$ sudo apt-get install libatlas-base-dev gfortran
```
