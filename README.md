# UAS
Nama 	: Cuntoko Prastio
Nim	: 191011400435
Kelas	: 06TPLE019

1.	State Management adalah sebuah cara untuk mengatur data / state kita bekerja, bisa juga untuk memisahkan antara logic dan view dimana logic tersebut juga bisa re-usable
Cara kerja State Management seperti Provide and Listen, maksudnya adalah kita bisa memasukan state yang kemungkinan bisa berubah sewaktu waktu, lalu Widget yang Subscribe (Listen) dengan Provider yang kita buat akan berubah sesuai dengan state yang berubah.

2.	Local State
Sebagai contoh dari local state kita dapat melihat kode diatas. Variabel _index merupakan local variable atau juga bisa disebut dengan local state karena bersifat private sehingga tidak bisa diakses di kelas lain. Salah satu cara yang umum untuk memperbarui variabel tersebut kita dapat menggunakan cara setState() didalam class yang berisi variabel tersebut.

App State
Tetapi pada di beberapa kasus tentu membutuhkan state yang dapat berjalan di seluruh layar aplikasi atau juga bisa disebut dengan app state. Berdasarkan dokumentasi Flutter untuk mengimplementasikannya terdapat beberapa cara yaitu InheritedWidget, InheritedModel, Redux, Fish-Redux, BLoC, GetIt, MobX, Binder, GetX, Riverpod, dan Provider. Disini saya akan membahas bagaimana mengimplementasikan BottomNavigationBar dan Parse JSON menggunakan app state dengan Provider.

General overview
	Provider
	Riverpod
	setState
	InheritedWidget & InheritedModel
	Redux
	Fish-Redux
	BLoC / Rx
	GetIt
	MobX
	Flutter Commands
	Binder
	GetX
	states_rebuilder
	Triple Pattern (Segmented State Pattern)

3.	
