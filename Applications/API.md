### Telegram Bot
* t.me/ztonllyBot
token to access the HTTP API:
```bash
7642418865:AAE6t96oEeeJ9o4OqZDmTp0lMSwR-UOPzKE
```
[https://api.telegram.org/botxxxx:yyyyyy/getUpdates](https://api.telegram.org/botxxxx:yyyyyy/getUpdates)
xxxx:yyyyyy替换为自己的token key

```json
{
    "ok": true,
    "result": [
        {
            "update_id": 400595769,
            "message": {
                "message_id": 3,
                "from": {
                    "id": 5764984946,
                    "is_bot": false,
                    "first_name": "Z",
                    "last_name": "tonlly",
                    "username": "ztonlly",
                    "language_code": "zh-hans"
                },
                "chat": {
                    "id": 5764984946,
                    "first_name": "Z",
                    "last_name": "tonlly",
                    "username": "ztonlly",
                    "type": "private"
                },
                "date": 1730966624,
                "text": "/start",
                "entities": [
                    {
                        "offset": 0,
                        "length": 6,
                        "type": "bot_command"
                    }
                ]
            }
        }
    ]
}
```
