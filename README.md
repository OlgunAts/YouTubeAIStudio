# YouTube AI Studio

YouTube AI Studio, Windows 10/11 (64-bit) için taşınabilir bir video üretim uygulamasıdır.

## İndirme

Çalışır taşınabilir paket için bu deponun **Releases** bölümünü kullanın. Paketi tamamen bir klasöre çıkarın ve `YouTubeAIStudio.exe` dosyasını çalıştırın.

> Not: Uygulama dijital olarak imzalanmamıştır. Windows ilk çalıştırmada güvenlik uyarısı gösterebilir.

## Özellikler ve gereksinimler

- Standart mod: Gemini + Pexels + Edge TTS
- Premium mod: Gemini + NanoBananaAPI.ai + Edge TTS veya ElevenLabs
- Windows 10/11 64-bit
- İnternet bağlantısı
- Seçilen moda uygun API anahtarları

Python veya FFmpeg kurulumu gerekmez; gerekli çalışma zamanı dosyaları taşınabilir pakete dahildir.

## API anahtarları ve gizlilik

API anahtarları dağıtım paketine dahil değildir. Uygulamada girilen anahtarlar Windows Credential Manager içinde saklanır. Üretilen videolar varsayılan olarak kullanıcının `Videos\YouTubeAIStudio` klasörüne yazılır.

## Bütünlük doğrulaması

Yayımlanan `YouTubeAIStudio-portable.rar` dosyasının SHA-256 değeri:

```text
9A1A71059E090EEA1F9C86535FA6D047031AC4E7B27B0EFE88A170BB5473CD76
```

PowerShell ile doğrulamak için:

```powershell
Get-FileHash .\YouTubeAIStudio-portable.rar -Algorithm SHA256
```

## Depo kapsamı

Sağlanan arşiv kaynak kod değil, PyInstaller ile üretilmiş taşınabilir uygulama paketidir. Üretilmiş bağımlılıklar ve büyük ikili dosyalar Git geçmişine eklenmez; çalışır paket sürüm eki olarak dağıtılır.

Üçüncü taraf bileşen bilgileri için [THIRD_PARTY_NOTICES.txt](THIRD_PARTY_NOTICES.txt) dosyasına bakın.
