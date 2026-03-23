1.	Устанавливаем arduino 2.3.8. Установили, открыли и закрыли. Качать желательно с сайта https://www.arduino.cc/en/software/ 

2.	Качаем файл "arduino-littlefs-upload-1.6.3.vsix" для работы с littlefs по ссылке: https://github.com/earlephilhower/arduino-littlefs-upload/releases 

3.	Создаем папку C:\Users\ИМЯ_ПОЛЬЗОВАТЕЛЯ\.arduinoIDE\plugins\ и вставляем в нее этот файл.

4. Открываем arduino 2.3.8. File – Preferences - В меню настроек вставить ссылку:

<img width="492" height="430" alt="изображение" src="https://github.com/user-attachments/assets/4106fff9-ebe0-494c-ac34-a08d236f443e" />

https://espressif.github.io/arduino-esp32/package_esp32_dev_index.json,https://espressif.github.io/arduino-esp32/package_esp32_index.json

5. Перейти в BOARDS MANAGER и для esp32 скачать 3.3.6 

<img width="291" height="650" alt="изображение" src="https://github.com/user-attachments/assets/6d37d91b-ed15-47c7-b917-be8f1c8582d9" />

6. Открываем проект, выбираем плату ESP32S3 Dev Module. Далее установить другие настройки как на картинке и плюс дополнительно необходимо выбрать соответствующий Port:

<img width="344" height="667" alt="изображение" src="https://github.com/user-attachments/assets/17461190-b0bf-43f2-b8e5-01be2f35312d" />

7. Скачать библиотеки:
<img width="132" height="265" alt="изображение" src="https://github.com/user-attachments/assets/da7b0409-5669-44a2-8d66-b41bde3f7a7d" />

8.	Из папки «Audio+fix+core+3.3.5» копируем с заменой два файла для ESP32S3 в папку:
C:\Users\ ИМЯ_ПОЛЬЗОВАТЕЛЯ \AppData\Local\Arduino15\packages\esp32\tools\esp32s3-libs\3.3.6\lib 

9. Убедитесь, что в myoptions.h все как нужно выбрано, настроено и на данном этапе можно компилировать и прошивать.

<img width="580" height="114" alt="изображение" src="https://github.com/user-attachments/assets/88df4058-4cda-4951-8a5d-ab599f8d2c88" />


10. После чего прошиваем файловую систему. В arduino 2.3.8 нажмите Ctrl+Shift+P. Начните вводить Upload LittleFS — команда должна появиться.

<img width="557" height="120" alt="изображение" src="https://github.com/user-attachments/assets/83255a16-0c78-4f18-9731-66f7ce722931" />

11. Ready for Use!
