[2023-11-05] При попытке загрузить данные imdb из Keras выходила ошибка о невозможности
             использовать SSL из-за проблем с сертификатами
             решил проблему выполнив команду
             ln -s /etc/ssl/* /Library/Frameworks/Python.framework/Versions/3.9/etc/openssl
             ошибка и решение описаны на
             https://stackoverflow.com/questions/52805115/certificate-verify-failed-unable-to-get-local-issuer-certificate
             Возможно похожая проблема была и с moex iis, нужно там вернуть исходный код
             библиотеки aiohttp и попробовать снова.
