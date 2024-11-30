# Turkish Podcastfy

Türkçe podcast oluşturma projesi. Podcastfy kullanarak web içeriklerini Türkçe podcast'e dönüştürür.

## Kurulum

1. Gereksinimleri yükleyin:
```bash
pip install -r requirements.txt
```

2. .env dosyasını oluşturun ve API anahtarlarınızı ekleyin:
```env
OPENAI_API_KEY=your-key
GOOGLE_API_KEY=your-key
ELEVENLABS_API_KEY=your-key
```

## Kullanım

```bash
python src/create_podcast.py
```

## Özellikler

- Web sayfalarından Türkçe podcast oluşturma
- Farklı ses modelleri desteği
- Özelleştirilebilir ses ayarları