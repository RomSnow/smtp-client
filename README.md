# smtp-client
SMTP клиент

### Внимание
Необходимо включить соответсвующие разрешения в вашем почтовом сервисе

## Параметры
```
usage: smtp-client.py [-h] [--server SERVER] [--port PORT]
                      [--username USERNAME] [--subject SUBJECT] [--text TEXT]
                      [--path PATH]
                      login password receiver

SMTP client

positional arguments:
  login                 Sender email address
  password              Password
  receiver              Receiver email address

optional arguments:
  -h, --help            show this help message and exit
  --server SERVER       SMTP server
  --port PORT           Port to use
  --username USERNAME   Username
  --subject SUBJECT, -s SUBJECT
                        Message subject
  --text TEXT, -t TEXT  Message text
  --path PATH, -p PATH  Path for attachment
```

## Пример использования
```
python3 smtp-client.py ivashkin.roma2001@yandex.ru **password** ivashkin.roma2001@gmail.com -t Hello
```