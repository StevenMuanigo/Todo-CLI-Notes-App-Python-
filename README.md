# Todo-CLI-Notes-App-Python-
Proje Açıklaması  Bu komut satırı aracı, yapılacak görevlerinizi kolayca yönetmenizi sağlar. Görev ekleme, listeleme ve silme işlemlerini destekler. Veriler tasks.json dosyasında kalıcı olarak saklanır.

Özellikler

Özellikler

 Görev ekleme (add)

 Tüm görevleri listeleme (list)

 Görev silme (delete)

 Kalıcı depolama (JSON dosyası)

 Renkli çıktı (Colorama)

 GEREKSİNİMLERİ

Python 3.8+

colorama kütüphanesi

pip install colorama

 KULLANILIM

1️ Görev ekleme:

python todo.py add "Kitap oku"


 

Added task: Kitap oku


2️ Görevleri listeleme:

python todo.py list



3️ Görev silme:

python todo.py delete 2


 Çıktı:

Deleted task: Spor yap

Klasör Yapısı
TodoCLI/
├── todo.py
├── tasks.json
└── README.md


```
