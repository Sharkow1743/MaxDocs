# Объект вложения в сообщениях

## Примеры
### Фото
``` json
{
    "previewData": "data:image/webp;base64,Ukl...",                   
    "baseUrl": "https://i.oneme.ru/i?r=BTE...",
    "photoToken": "dpm...",
    "_type": "PHOTO",
    "width": 1920,
    "photoId": 111111111,
    "height": 1920
}
```

### Кнопка
``` json
{
    "_type": "INLINE_KEYBOARD",
    "keyboard": {
        "buttons": [
            [
                {
                    "type": "LINK",
                    "url": "https://max.ru/sferum_bot?startapp",
                    "text": "Выбрать организацию"
                }
            ]
        ]
    },
    "callbackId": "f9L..."
}
```