# ades2

## Kurulum

1. Node.js'i yükleyin (versiyon 16.9.0 veya üstü).
2. Projeyi klonlayın veya indirin.
3. Terminalde `npm install` komutunu çalıştırın.

## Yapılandırma

1. Discord Developer Portal'dan bir bot oluşturun ve token'ı alın.
2. `.env` dosyası oluşturun ve `DISCORD_TOKEN` değerini bot token'ınızla doldurun (`.env.example`'a bakın).

## Çalıştırma

`npm start` komutuyla botu başlatın.

## 7/24 Aktif Tutma

Botu yerel makinenizde çalıştırırsanız, bilgisayar kapandığında durur. 7/24 aktif tutmak için hosting servisleri kullanın:

- **Railway:** GitHub repo'sunu bağlayın, otomatik deploy.
- **Heroku:** `heroku create` ile app oluşturun, `git push heroku main` ile deploy.
- **Render:** Web service olarak deploy.

Environment variables olarak `DISCORD_TOKEN`'ı ayarlayın.

Botunuz artık 7/24 aktif kalacak!