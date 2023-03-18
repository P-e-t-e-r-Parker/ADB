###### :heavy_check_mark: 1. Отобразить подключённый девайс в консоли. 
     ./adb devices
###### :heavy_check_mark:  2. Вывести адрес приложения todolist в системе Android
     ./adb shell 'pm list packages -f | grep todolist'
###### :heavy_check_mark: 3. Установить .apk файл приложениия todolist на телефон с компьютера через  ADB 
     ./adb install D:\26_QA\todolist.apk
 ###### :heavy_check_mark: 4. Сделать скриншот запущенного приложения todolist и сразу скопировать на компьютер в одной команде.
     ./adb shell  screencap/storage/emulated/0/DCIM/screen_26_QA.png | ./adb pull/storage/emulated/0/DCIM/screen_26_QA/png D:\adb\todolist\screen_26.png
 ###### :heavy_check_mark: 5. Вывести в консоль логи приложения todolist
     ./adb logcat -d | findstr -r todolist
 ###### :heavy_check_mark: 6. Скопировать логи приложения todolist на компьютер.
     ./adb logcat -d | findstr -r todolist > todolist_log.txt
 ###### :heavy_check_mark: 7. Удалить приложение todolist с телефона через ADB
     ./adb uninstall com.android.todolist






## 📫 Связаться со мной
[![Telegram](https://img.shields.io/static/v1?style=for-the-badge&logo=telegram&message=telegram&label=&color=4165a3&labelColor=000000)](https://t.me/petrshelkunov)
[![mail](https://img.shields.io/static/v1?style=for-the-badge&logo=gmail&message=mail&label=&color=e8203b&labelColor=000000)](mailto:petia.shelkunov@yandex.ru)
[![LinkedIn](https://img.shields.io/static/v1?style=for-the-badge&logo=linkedin&message=LinkedIn&label=&color=3947c4&labelColor=000000)](https://linkedin.com/in/petr-shhelkunov)
