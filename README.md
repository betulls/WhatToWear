# WhatToWear 👗👔

> **Yapay Zekâ Destekli ve Bağlama Duyarlı Akıllı Gardırop & Stil Asistanı**  
> *AI-Powered Context-Aware Smart Wardrobe and Personal Style Assistant*

## 📌 Proje Hakkında
WhatToWear, kullanıcıların kıyafetlerini dijital ortama aktararak anlık hava durumu, seçilen giyim modu (rahat, klasik, sportif) ve geçmiş termal konfor geri bildirimlerine (üşüdüm/terledim) dayalı olarak kişiselleştirilmiş kombinler üreten mobil öncelikli bir web platformudur (PWA).

## 🚀 Temel Özellikler
- **Görüntü İşleme & Segmentasyon:** Kıyafet görsellerinin arka planını otomatik temizleme (`rembg`) ve öznitelik çıkarımı.
- **Akıllı Gardırop (Digital Closet):** Kıyafetleri kategorize etme, etiketleme ve yönetme.
- **Bağlama Duyarlı Kombin Motoru:** Anlık hava durumu (OpenWeatherMap) ve stil moduna göre kural/vektör tabanlı uyumluluk eşleştirmesi.
- **LLM Stilist Danışmanı:** Kombinin neden seçildiğini açıklayan interaktif doğal dil stil tavsiyeleri (Gemini API).
- **Adaptif Hafıza (Feedback Loop):** Gün sonu termal konfor geri bildirimleriyle öğrenen kişisel tolerans eşiği.

## 🛠️ Teknoloji Yığını (Tech Stack)
- **Frontend:** Next.js / React, Tailwind CSS (PWA)
- **Backend:** Python (FastAPI)
- **Yapay Zekâ & CV:** `rembg`, Hugging Face / Fashion-CLIP, Gemini API
- **Veritabanı:** PostgreSQL
- **Harici API:** OpenWeatherMap API

## 👥 Geliştirici
- **Betül Sefer** - Bilgisayar Mühendisliği Bitirme Projesi
