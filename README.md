# 🕹️ Tetris - Classic WPF Game

![.NET](https://img.shields.io/badge/.NET-8.0-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![WPF](https://img.shields.io/badge/WPF-Windows-blue?style=for-the-badge)

Modern C# ve WPF (Windows Presentation Foundation) teknolojileri kullanılarak geliştirilmiş, klasik retro hissiyatını koruyan masaüstü Tetris oyunu.

---

## 🎓 Proje Hakkında

Bu proje, **Giresun Üniversitesi Bilgisayar Programcılığı** mezuniyet dönemimde C# nesne yönelimli programlama (OOP) ve WPF arayüz tasarımı yetkinliklerimi pekiştirmek amacıyla geliştirilmiştir. Oyun mimarisi, matris tabanlı ızgara mantığı ve olay güdümlü (event-driven) GUI bileşenleri üzerine inşa edilmiştir.

---

## ✨ Özellikler

- **Klasik Tetromino Blokları:** 7 temel Tetris bloğu (I, J, L, O, S, T, Z) ve özel renk/dokular.
- **WPF Arayüzü:** Akıcı animasyonlar, özel varlıklar (assets) ve kullanıcı dostu arayüz tasarımı.
- **Skor & İlerleme:** Temizlenen satır sayısına göre artan skor ve dinamik oyun temposu.
- **Modüler Kod Mimarisi:** Blok hareketleri, ızgara kontrolü ve oyun durumunu ayıran temiz OOP yapısı.

---

## 🎮 Kontroller & Nasıl Oynanır?

| Tuş | Eylem |
| :--- | :--- |
| **⬅️ Sol Ok** | Bloğu sola kaydır |
| **➡️ Sağ Ok** | Bloğu sağa kaydır |
| **⬇️ Aşağı Ok** | Hızlı düşüş (Soft Drop) |
| **⬆️ Yukarı Ok / Boşluk** | Bloğu döndür (Rotate) |

---

## 🛠️ Kullanılan Teknolojiler

- **Dil:** C#
- **Platform:** .NET 8.0 (Windows)
- **Arayüz Framework:** WPF (XAML)
- **Geliştirme Ortamı:** Visual Studio

---

## 🚀 Kurulum & Çalıştırma

1. Repoyu bilgisayarınıza klonlayın:
   ```bash
   git clone [https://github.com/kullanici-adiniz/Tetris.git](https://github.com/kullanici-adiniz/Tetris.git)
