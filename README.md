# Yandex Disk Downloader

Скачивает файлы с Яндекс Диска с использованием командной строки.


OAuth-токен для обращения к Яндекс API можно получить [здесь.](https://yandex.ru/dev/disk/poligon/#!//v1/disk/public/resources/GetPublicResourceDownloadLink)

## Как пользоваться

- **OAuth** - полученный OAuth-токен
- **OutputFile** - куда сохранить файл
- **PublicKey** - публичная ссылка на файл (полученная из UI Яндекс Диска)

```shell
git clone https://github.com/palshin/yandex-downloader
cd ./yandex-downloader
chmod +x ./download
./download --oauth=<OAuth> --output-file=<OutputFile> --public-key=<PublicKey>
```
