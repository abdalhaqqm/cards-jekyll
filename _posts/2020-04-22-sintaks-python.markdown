---
layout: post
title:  "Tutorial Python #3: Sintaks Python"
date:   2020-04-22 06:15:40
categories: python
img: python-green.webp
---
Selanjutnya, mari kita berkenalan dengan sintaks dasar Python.

Sebagaimana sudah kita pelajari sebelumnya, kode Python dapat dijalankan dengan cara ditulis langsung dalam interpreter:
{% highlight console %}
>>> print("Hello, World!")
Hello, World!
{% endhighlight %}
Bisa juga dengan membuat file Python (ekstensi .py) dan dijalankan melalui command line:
{% highlight console %}
python filesaya.py
{% endhighlight %}

Kita mulai dengan indentasi. Apa itu indentasi? Indentasi adalah spasi pada permulaan baris kode.

Inilah salah satu perbedaan Python dengan sebagian besar bahasa pemrograman lainnya. Python menggunakan indentasi untuk mengelompokkan blok.
 Blok yang dimaksud di sini adalah scope. Blok bisa berupa fungsi, perulangan, kelas, conditional statement, dan sebagainya.

Ini adalah contoh penulisan conditional statement dalam Python:
{% highlight python %}
if 5 > 2:
  print("Lima lebih besar daripada dua")
{% endhighlight %}
Pada bahasa pemrograman lain, untuk menandai scope biasanya digunakan tanda `{}` (kurung kurawa)
 Contoh conditional statement dalam JavaScript:
{% highlight js %}
if (5 > 2) {
        console.log("Lima lebih besar daripada dua");
}
{% endhighlight %}
Berbeda dengan JavaScript, Python akan menghasilkan error jika kamu tidak menggunakan indentasi.

Coba contoh berikut untuk membuktikannya:
{% highlight python %}
if 5 > 2:	
print("Lima lebih besar daripada dua")
{% endhighlight %}
Kita bebas menentukan jumlah spasi yang digunakan dalam indentasi, minimal satu spasi.
 Selain itu, kita harus konsisten saat menggunakan jumlah spasi untuk indentasi dalam satu blok.
 Kita boleh menggunakan indentasi yang berbeda untuk blok yang berbeda.

Contoh:
{% highlight python %}
if 5 > 2:
 print("Lima lebih besar daripada dua") 
if 5 > 2:
        print("Lima lebih besar daripada dua ")
{% endhighlight %}

Kemudian, kita akan mengenal variabel secara singkat.
 Dalam Python, variabel terdeklarasi secara otomatis ketika kamu memberikan nilai padanya:
Contoh:
{% highlight python %}
x = 5
y = "Hello, World!"
{% endhighlight %}
Python tidak mempunyai perintah untuk mendeklarasikan variabel.
 Artinya, kita hanya perlu memberikan nilai pada sebuah variabel untuk menciptakannya tanpa harus mendeklarasikannya.
 Tipe data variabel Python bersifat dinamis. Artinya, kamu bisa mengganti nilai variabelmu dengan tipe data yang berbeda-beda
 Python akan mendeteksinya secara otomatis.

Kamu akan belajar lebih banyak tentang variabel pada pembahasan Variabel dalam Python.

Python juga tidak memerlukan tanda titik koma `;` untuk mengakhiri baris. Ini membuat kita terhindar dari kelupaan menulis titik koma.

Selanjutnya adalah komentar. Komentar dalam Python diawali dengan tanda #. Python akan mengabaikan komentar dan tidak menjalankannya.

Contoh:
{% highlight python %}
#Ini adalah komentar.
print("Hello, World!")
{% endhighlight %}