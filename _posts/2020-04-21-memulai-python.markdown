---
layout: post
title:  "Tutorial Python #2: Memulai Python"
date:   2020-04-21 17:07:40
img: python-purple.webp
categories: python
---
Pada tutorial kali ini, kita akan mulai berinteraksi dengan bahasa pemrograman Python.
 Namun sebelumnya, pastikan Python telah terinstall pada komputer kamu.

Tidak seperti Windows, komputer dengan sistem operasi Linux dan Mac biasanya telah terpasang Python.
 Untuk mengecek apakah Python telah terpasang pada komputer kamu, jalankan perintah berikut pada command line:

{% highlight console %}
python --version
{% endhighlight %}

Jika muncul informasi mengenai versi Python yang terinstall pada komputermu, selamat!
 Kamu tidak perlu menginstallnya lagi.

Jika tidak, maka kamu bisa mengunduhnya secara gratis dari website resmi Python:

[https://www.python.org/](https://www.python.org/ "Python Site")
<div class="alert">Ingat untuk menginstall Python 3 agar kamu bisa mengikuti tutorial ini dengan baik. Jika kamu menggunakan Windows Installer, jangan lupa centang pilihan "Add Python to PATH"</div>

Sebagaimana sudah dijelaskan sebelumnya, Python adalah bahasa pemrograman interpreter.
 Artinya, kamu bisa menulis file Python (.py) dalam text editor dan membukanya dalam interpreter Python untuk dijalankan secara langsung tanpa perlu compile.

Cara menjalankan file Python pada command line adalah sebagai berikut:

{% highlight console %}
python helloworld.py
{% endhighlight %}

<div class="alert">"helloworld.py”adalah nama file Python kamu.</div>

Mari kita coba menulis file Python pertama kita. Ini dapat dilakukan dengan text editor apa saja.

{% highlight python %}
print("Hello, World!")
{% endhighlight %}

Ringkas dan sederhana, itulah Python.

Simpan file-mu dengan ekstensi .py, misalnya `helloworld.py`.
 Buka command line dan bukalah folder di mana kamu menyimpan file-mu lalu jalankan perintah: 

{% highlight console %}
python helloworld.py
{% endhighlight %}

Kira-kira, outputnya akan seperti ini: 

{% highlight console %}
Hello, World!
{% endhighlight %}

Selamat, kamu telah menulis dan menjalankan program Python pertamamu.

Selain ditulis dalam file, Python juga bisa dijalankan langsung lewat interpreter.
 Ketikkan perintah berikut dalam command line untuk membuka interpreter:

{% highlight console %}
python
{% endhighlight %}

Jika perintah `python` tidak bekerja, kamu bisa mencoba `py`, `py3`, atau `python3`

Dalam interpreter, kamu dapat menulis kode Python dan menjalankannya secara langsung.
 Misalkan kita akan menulis contoh program hello world:

{% highlight console %}
Python 3.6.4 (v3.6.4:d48eceb, Dec 19 2017, 06:04:45) [MSC v.1900 32 bit (Intel)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>> print("Hello, World!")
{% endhighlight %}
Ia akan menghasilkan output “Hello, World!” dalam command line:

{% highlight console %}
Python 3.6.4 (v3.6.4:d48eceb, Dec 19 2017, 06:04:45) [MSC v.1900 32 bit (Intel)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>> print("Hello, World!")
Hello, World!
{% endhighlight %}
Jika sudah selesai menggunakan Python interpreter, ketikkan perintah berikut untuk menutupnya:

{% highlight console %}
exit()
{% endhighlight %}