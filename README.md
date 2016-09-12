# Avro phonetic for Fedora (Linux) in IBus
Avro phonetic implementation for Linux in IBus.
This Project is a copy project copied from
https://github.com/fa7ad/avro-fedora

Its copied for opensuse gnome user who want to use avro easyly without pain 

## Installation from source (m1)

* Open Yast->softwere-Managment and search and install the packege given below:
```bash
  
	*autoconf 
	*automake 
	*make 
	*gcc 
	*gjs 
	*ibus 
	*ibus-libs 
	*ibus-devel 
	*gjs-devel 
	*git
```
* Now Clone the repo and install
```bash
	git clone https://github.com/fa7ad/avro-fedora.git
	cd ibus-avro-fedora
	aclocal && autoconf && automake --add-missing
	./configure --prefix=/usr
	sudo make install

 
## Usage
 0. Reboot after installation
 1. Open **Settings** from **GNOME Dash**
 2. Navigate to **Region & Language** > *Input Sources*
 3. Click the add (**+**) button and add **Bengali (Avro Phonectic)**
 4. Close **Settings**
 5. Open any text editor and press `::(super) + <space>` to switch to Bengali
 6. Enjoy typing in Bangla using Avro Phonetic

## Contributors

 
__IBus Engine__ by [__Sarim Khan__](https://github.com/sarim)

[__Avro JavaScript Phonetic Library__](https://github.com/torifat/jsAvroPhonetic) by [__Rifat Nabi__](https://github.com/torifat)

__Avro Phonetic Dictionary Search Library__ by [__Mehdi Hasan Khan__](https://github.com/omicronlab)

__Fedora Build and minor adjustments__ by [__Fahad Hossain__](http://thewebaholic.ml)

_Licensed under Mozilla Public License 1.1 ("MPLv1.1"), an open source/free software license._
