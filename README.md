# 🌌 NatalKit — Kurumsal Astroloji Hesaplama Motoru & Çoklu Sistem API'si

[![Hassasiyet](https://img.shields.io/badge/Astronomik_Hassasiyet-Swiss_Ephemeris_2.10.03-blue?style=for-the-badge)](https://natalkit.com)
[![API Sürümü](https://img.shields.io/badge/API-REST_v1_Aktif-brightgreen?style=for-the-badge)](https://natalkit.com/v1/docs)
[![Sistem Sayısı](https://img.shields.io/badge/Kadim_Sistemler-9_Gelenek-purple?style=for-the-badge)](https://natalkit.com)
[![Yanıt Süresi](https://img.shields.io/badge/Yan%C4%B1t_H%C4%B1z%C4%B1-%3C_5ms-orange?style=for-the-badge)](https://natalkit.com)

> **NatalKit**, milisaniyenin altında yanıt veren, yüksek hassasiyetli bir astrolojik hesaplama motoru ve geliştirici API'sidir. Altın standart kabul edilen **Swiss Ephemeris** astronomik hesaplama motorunu kullanan NatalKit, **9 kadim ve modern astroloji ekolünü** tek bir güçlü, hızlı ve tutarlı API platformunda birleştirir.

İster yeni nesil yapay zeka astroloji asistanları, ister flört uygulamaları için astrolojik uyum algoritmaları, ister zamanlama/öngörü motorları geliştirin; NatalKit uydurma veya tahmine yer bırakmayan, matematiksel olarak kesin ve milimetrik veri sunar.

---

## ⚡ Öne Çıkan Özellikler & Neden NatalKit?

* 🛰️ **Milimetrik Astronomik Hassasiyet:** Gezegenler, asteroitler (Kiron, Lilith), gerçek/ortalama ay düğümleri, ev girişleri ve durağan/retro dereceleri için yay saniyesi altı (sub-arcsecond) hassasiyet.
* 🏛️ **Tek API'de 9 Kadim Sistem:** Batı (Placidus/Whole Sign), Vedik Jyotish (Lahiri), Çin BaZi (Dört Sütun), Maya Tzolk'in, Mısır Dekanları, Pers Firdaria, İslam Ay Menzilleri, Tayland Mahabote ve Japon Eto.
* 🤖 **Yapay Zekaya Hazır Markdown Raporları:** En yeni nesil akıl yürütme modelleri (Claude Opus 4.6 / 3.7 Sonnet, Gemini 3.7 Flash, DeepSeek V4 / R1, OpenAI o3 / GPT-5, Grok 3/4) için sıfır halüsinasyon garantili, yapılandırılmış Markdown çıktıları.
* 📈 **Öngörüsel Zaman & Döngüler:** İkincil İlerletimler (Secondary Progressions), Solar Arc, Yıllık Profection (Yılın Yöneticisi), Firdaria ve kişiselleştirilmiş transit puanlaması (0–100).
* 💘 **Gelişmiş Sinastri & Eşleşme Analizi:** Çapraz açı ızgarası ve 4 boyutlu uyum motoru (Romantik, Duygusal, Zihinsel, Kalıcılık).
* 🚀 **Ultra Düşük Gecikme & Kurumsal Altyapı:** Milisaniyeler mertebesinde (<5ms) ultra hızlı JSON yanıtları, yüksek eşzamanlı istek kapasitesi, güvenli API anahtarı mimarisi ve %99.9 çalışma güvencesi.

---

## 🏛️ Desteklenen 9 Kadim ve Evrensel Astroloji Sistemi

| Sistem | Motor / Yöntem | Temel Çıktılar & Hesaplamalar |
|---|---|---|
| **Batı Astrolojisi (Western)** | Tropikal, Placidus / Whole Sign / Koch | Gezegenler, Evler, Açılar (Yaklaşan/Uzaklaşan), Açı Kalıpları (T-Kare, Büyük Üçgen, Yod, Stellium), Dispositör Ağaçları, Asaletler. |
| **Vedik / Jyotish** | Lahiri Ayanamsa, Sidereal | D1 Rashi, D9 Navamsha, D10 Dashamsha, 27 Nakshatra & Pada, Shadbala Gezegen Güçleri, Sarvashtakavarga (SAV) Binduları, Vimshottari Maha/Antar Dasha. |
| **Çin BaZi (Dört Sütun)** | Solar Term (Jie Qi), 60'lık Döngü | Yıl/Ay/Gün/Saat Sütunları, Gün Efendisi (Day Master), Saklı Kökler (Cang Gan % dağılımı), 10 Tanrı (Shi Shen), 10 Yıllık Büyük Şans (Da Yun). |
| **Maya Astrolojisi** | Tzolk'in & Haab Korelasyonu | Kin Numarası, Solar Mühür (Seal), Galaktik Ton (Tone), Trezena Rehberi, Maya Kehanet Matrisi. |
| **Mısır Astrolojisi** | 36 Dekan & Mısır Terimleri | Yıldız Dekanı Yöneticileri, Egyptian Bounds (Terim Yöneticileri), Yükselen Yıldız Mimarisi. |
| **Pers Astrolojisi** | Sasani / Ortaçağ Geleneği | Firdaria (Gündüz/Gece Haritası Çizelgesi), Kronokratörler, Kura (Lot) Yöneticilikleri. |
| **İslam / Arap Astrolojisi** | Menâzilü'l-Kamer | 28 Ay Menzili, 7 Helenistik Arap Noktası (Ruh, Şans, Zafer, Cesaret, Zorunluluk, Sevgi Kuraları). |
| **Tayland Astrolojisi** | Mahabote (7 Gezegen / 8 Yön) | Doğum Günü Rengi/Ruhu, Mahabote Evi, Gezegensel Güç Matrisi. |
| **Japon Geleneği** | Eto & Rokuyo | Junishi (12 Hayvan), Jikkan (10 Göksel Gövde), Sanmêigaku Element Dengesi, Gün Uğuru (Rokuyo). |

---

## 🔬 İleri Düzey Teknik & Mikro-Derece Analizleri

NatalKit yalnızca yüzeysel burç yerleşimlerini değil, profesyonel astrolojinin en derin katmanlarını çözer:

* **0° ve 29° Anaretik Dereceler:** Yeni başlangıçlar (inisiyasyon) ve karmik ustalık/kriz noktalarının anlık tespiti.
* **Antiscia & Contra-Antiscia:** Solstis eksenine göre bilinçaltı gölge dereceler ve gizli gezegen temasları.
* **Helyak Fazlar & Cazimi:** Güneş'in kalbinde (Cazimi), ışınlar altında (Combust) veya görünürlük evresindeki gezegenlerin güç analizi.
* **Kozmobiyoloji & Orta Noktalar (Ebertin 90°):** $A/B = C$ orta nokta tetiklemeleri ($\le 1.5^\circ$ orb).
* **Harmonik Haritalar:** H4 (Kariyer/Hedef), H7 (Ruhsal/İlham), H9 (Navamsha/Dharma/Ruh Eşi).
* **Sabit & Kraliyet Yıldızları:** Regulus, Aldebaran, Antares, Fomalhaut, Sirius, Algol, Spica ($\le 1^\circ$ orb).
* **360 Sabian Sembolü:** Jones/Wheeler derece sembolizmi ve derece imgeleri.

---

## 🛠️ REST API Dokümantasyonu (v1)

NatalKit API, `X-API-Key` başlığı üzerinden kimlik doğrulaması yapar.

```http
X-API-Key: astr_live_xxxxxxxxxxxxxxxxxxxxxxxxxxxx
Content-Type: application/json
```

### 1. Doğum Haritası Hesaplama (`POST /v1/natal`)

Doğum haritası, evler, açılar, mikro-dereceler ve seçilen kadim sistemlerin verilerini döner.

#### Örnek İstek (Request):
```bash
curl -X POST "https://natalkit.com/v1/natal" \
  -H "Content-Type: application/json" \
  -H "X-API-Key: astr_live_ornek_anahtariniz" \
  -d '{
    "birth": {
      "name": "Ahmet Yılmaz",
      "date": "1995-10-24",
      "time": "14:30",
      "latitude": 41.0082,
      "longitude": 28.9784,
      "timezone": "Europe/Istanbul"
    },
    "systems": ["vedic", "bazi", "egyptian", "mayan"]
  }'
```

#### Örnek Yanıt (Response):
```json
{
  "status": "success",
  "request_id": "req_8f1a2b3c4d5e",
  "credits_charged": 5,
  "credits_remaining": 9995,
  "data": {
    "chart": {
      "birth": {
        "name": "Ahmet Yılmaz",
        "date": "1995-10-24",
        "time": "14:30",
        "lat": 41.0082,
        "lon": 28.9784,
        "timezone": "Europe/Istanbul"
      },
      "planets": [
        {
          "body": "Sun",
          "sign": "Scorpio",
          "formatted": "00°Scorpio42'15\"",
          "house": 9,
          "retrograde": false,
          "speed_lon": 0.9984
        }
      ],
      "houses": [
        { "house": 1, "sign": "Capricorn", "formatted": "18°Capricorn12'04\"" }
      ],
      "aspects": [
        {
          "body_a": "Sun",
          "body_b": "Mars",
          "type": "Conjunction",
          "orb": 1.42,
          "motion": "Applying"
        }
      ]
    },
    "systems": {
      "vedic": {
        "name": "Vedic (Jyotish)",
        "headline": "Lagna: धनु (Dhanu / Yay) · Rashi: तुला (Tula / Terazi)",
        "sections": [...]
      },
      "bazi": {
        "name": "Chinese BaZi",
        "headline": "Day Master: 辛 Metal (Yin Metal)",
        "sections": [...]
      }
    }
  }
}
```

---

### 2. İlişki & Sinastri Uyumu (`POST /v1/synastry`)

İki doğum haritası arasındaki açı temaslarını, ev yerleşimlerini ve 4 boyutlu uyum skorunu hesaplar.

#### Örnek İstek (Request):
```bash
curl -X POST "https://natalkit.com/v1/synastry" \
  -H "Content-Type: application/json" \
  -H "X-API-Key: astr_live_ornek_anahtariniz" \
  -d '{
    "person_a": {
      "name": "Can",
      "date": "1992-06-15",
      "time": "08:15",
      "latitude": 41.0082,
      "longitude": 28.9784,
      "timezone": "Europe/Istanbul"
    },
    "person_b": {
      "name": "Elif",
      "date": "1994-11-20",
      "time": "19:45",
      "latitude": 39.9334,
      "longitude": 32.8597,
      "timezone": "Europe/Istanbul"
    }
  }'
```

#### Örnek Yanıt (Response):
```json
{
  "status": "success",
  "data": {
    "score": {
      "total_score": 88,
      "romantic": 92,
      "emotional": 85,
      "mental": 80,
      "longevity": 90,
      "harmony_level": "Çok Yüksek Uyum (Kadersel Çekim)"
    },
    "aspects": [
      {
        "planet_a": "Venus",
        "planet_b": "Mars",
        "type": "Trine",
        "orb": 0.85,
        "impact": "Güçlü romantik ve cinsel çekim bağı"
      }
    ]
  }
}
```

---

### 3. Gelecek Transitleri & Tetikleme Takvimi (`POST /v1/transits`)

Haritanın belirli bir zaman aralığındaki (6 ay – 5 yıl) tüm majör transit temaslarını, kesinleşme tarihlerini ve etki güçlerini puanlar.

```bash
curl -X POST "https://natalkit.com/v1/transits" \
  -H "Content-Type: application/json" \
  -H "X-API-Key: astr_live_ornek_anahtariniz" \
  -d '{
    "birth": {
      "date": "1990-03-21",
      "time": "12:00",
      "latitude": 41.0082,
      "longitude": 28.9784,
      "timezone": "Europe/Istanbul"
    },
    "range": "2y"
  }'
```

---

### 4. İlerletimler (Secondary Progressions & Solar Arc) (`POST /v1/progressions`)

```bash
curl -X POST "https://natalkit.com/v1/progressions" \
  -H "Content-Type: application/json" \
  -H "X-API-Key: astr_live_ornek_anahtariniz" \
  -d '{
    "birth": {
      "date": "1988-08-14",
      "time": "06:30",
      "latitude": 39.9334,
      "longitude": 32.8597,
      "timezone": "Europe/Istanbul"
    },
    "target_date": "2026-09-01"
  }'
```

---

### 5. Desteklenen Kadim Sistemlerin Listesi (`GET /v1/systems`)

```bash
curl -X GET "https://natalkit.com/v1/systems" \
  -H "X-API-Key: astr_live_ornek_anahtariniz"
```

---

## 🤖 LLM & Yapay Zeka Hazır Sentez Raporu

NatalKit, hesaplanan tüm ham Swiss Ephemeris verilerini ve 9 sistemi tek bir **Markdown Raporuna** dönüştürür. Raporun başında yer alan `AIAnalysisPrompt`, en yeni nesil amiral gemisi ve akıl yürütme modellerine (**Claude Opus 4.6 / 3.7 Sonnet (Thinking)**, **Gemini 3.7 Flash / 2.5 Pro**, **DeepSeek V4 Pro / R1**, **OpenAI o3 / GPT-5**, **xAI Grok 3 / Grok 4**) verildiğinde:

* **Sıfır Halüsinasyon:** Modelin belgede bulunmayan açı, derece ve konumları uydurmasını kesin olarak engeller.
* **Metodolojik Çıkarım Zinciri:** `Gösterge → Astrolojik Anlam → Kişisel Sentez → Pratik Sonuç` formatını zorunlu kılar.
* **Çoklu Sistem Gücü & Çelişki Ayrımı:** Batı, Vedik ve BaZi arasındaki ortak paydaları ve çelişkileri şeffafça sınıflandırır (*Çoklu Destek, Teknik Destek, Zayıf Destek, Belirsiz*).
* **Dinamik Gelecek Zaman Çizelgesi:** İlgili yıllara ait kariyer, finans, ilişki ve kritik fırsat/risk pencerelerini eksiksiz çıkarır.
* **Yüksek Bilgi Yoğunluğu & Token Optimizasyonu:** Edebi dolgu ve tekrarları keserek çıktı limitine takılmadan 8 bölümün tamamını eksiksiz bitirir.

---

## 🔑 API Key Edinme & Hızlı Başlangıç

NatalKit Enterprise API erişimi, özel kotalı planlar veya test API anahtarı talepleriniz için:

1. **İletişime Geçin:** Telegram üzerinden **[@e3x6v](https://t.me/e3x6v)** ile doğrudan iletişime geçerek API erişim anahtarınızı (`astr_live_...`) talep edin.
2. **Kredinizi & Planınızı Belirleyin:** Projenizin ihtiyaç duyduğu istek/kredi hacmine göre anahtarınız anında tanımlanır.
3. **Entegre Edin:** İsteklerinizde `X-API-Key: astr_live_...` başlığını kullanarak dakikalar içinde entegrasyonu tamamlayın.

Canlı interaktif API dokümantasyonu ve endpoint test arayüzü için: **[natalkit.com/v1/docs](https://natalkit.com/v1/docs)**

---

<p align="center">
  <sub>NatalKit Platform API — Yüksek Hassasiyetli Astroloji Hesaplama Motoru. 🌟</sub><br/>
  <sub>Geliştirici: <b>Muhammet ÇİMEN</b> · <a href="https://x.com/PrivyXe">X (@PrivyXe)</a> · <a href="https://instagram.com/mr_cimen_">Instagram (@mr_cimen_)</a></sub>
</p>
