1.Заходим в Botfather [https://t.me/BotFather]
1.1 Прописываем команду /newbot , регистрируем бота, копируем токен бота 

2. Заходим в файл config.php ищем 2 строку, меняем токен "6709715648:AAEirD3Par-zyhCVJw_Nf5i_485z_Az4Xa8"
3. Заходим в файл connect.php, меняем данные от базы данных
4. Закидываем данные на хостинг, импортим файл "bdproverka.sql" в phpmyadmin и последнее что требуется - создать вебхук
5. Создаем вебхук
https://api.telegram.org/botТокенБота/setwebhook?url=путь до файла bot.php 
example - ( https://api.telegram.org/6709715648:AAEirD3Par-zyhCVJw_Nf5i_485z_Az4Xa8/setwebhook?url=domain.com/proverka.php ) 
