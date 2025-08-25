
***Оглавление***:

1. [[#Основы|Основы]]
	1. [[#Основы#Включение|Включение]]
	2. [[#Основы#Карта microSD|Карта microSD]]
		1. [[#Карта microSD#Flipper не видит карту|Flipper не видит карту]]
		2. [[#Карта microSD#Безопасное извлечение|Безопасное извлечение]]
	3. [[#Основы#Прошивка (Firmware)|Прошивка (Firmware)]]
		1. [[#Прошивка (Firmware)#Mobile App|Mobile App]]
			1. [[#Mobile App#Подключение телефона к Flipper Zero|Подключение телефона к Flipper Zero]]
				1. [[#Подключение телефона к Flipper Zero#Если флиппер не обнаруживается:|Если флиппер не обнаруживается:]]
			2. [[#Mobile App#Обновление прошивки в мобильном приложении|Обновление прошивки в мобильном приложении]]
		2. [[#Прошивка (Firmware)#Обновление через qFlipper|Обновление через qFlipper]]
		3. [[#Прошивка (Firmware)#Internal storage is full|Internal storage is full]]
			1. [[#Internal storage is full#через Settings|через Settings]]
			2. [[#Internal storage is full#через qFlipper|через qFlipper]]
			3. [[#Internal storage is full#Восстановление из backup|Восстановление из backup]]
		4. [[#Прошивка (Firmware)#Firmware Recovery|Firmware Recovery]]
			1. [[#Firmware Recovery#Переключаемся в Recovery|Переключаемся в Recovery]]
				1. [[#Переключаемся в Recovery#Если девайс работает но не обновляется|Если девайс работает но не обновляется]]
				2. [[#Переключаемся в Recovery#Если девайс окирпичен:|Если девайс окирпичен:]]
			2. [[#Firmware Recovery#Repair|Repair]]
	4. [[#Основы#Основной экран (Desktop)|Основной экран (Desktop)]]
		1. [[#Основной экран (Desktop)#Status bar|Status bar]]
		2. [[#Основной экран (Desktop)#Навигация|Навигация]]
		3. [[#Основной экран (Desktop)#Главное меню|Главное меню]]
		4. [[#Основной экран (Desktop)#Меню блокировки|Меню блокировки]]
			1. [[#Меню блокировки#Lock|Lock]]
			2. [[#Меню блокировки#Mute|Mute]]
			3. [[#Меню блокировки#Dummy Mode|Dummy Mode]]
		5. [[#Основной экран (Desktop)#Passport|Passport]]
		6. [[#Основной экран (Desktop)#Archive|Archive]]
		7. [[#Основной экран (Desktop)#Device Info|Device Info]]
		8. [[#Основной экран (Desktop)#Quick Access Apps|Quick Access Apps]]
	5. [[#Основы#Тамагочи|Тамагочи]]
	6. [[#Основы#Питание|Питание]]
		1. [[#Питание#Выключение питания:|Выключение питания:]]
		2. [[#Питание#Sleep mode|Sleep mode]]
	7. [[#Основы#Перезагрузка|Перезагрузка]]
	8. [[#Основы#Settings (Настройки)|Settings (Настройки)]]
		1. [[#Settings (Настройки)#Bluetooth|Bluetooth]]
		2. [[#Settings (Настройки)#LCD and Notifications|LCD and Notifications]]
		3. [[#Settings (Настройки)#Storage|Storage]]
		4. [[#Settings (Настройки)#MicroSD card benchmark|MicroSD card benchmark]]
		5. [[#Settings (Настройки)#Power|Power]]
		6. [[#Settings (Настройки)#Desktop settings|Desktop settings]]
		7. [[#Settings (Настройки)#System settings|System settings]]
			1. [[#System settings#Logs|Logs]]
			2. [[#System settings#Log Device|Log Device]]
			3. [[#System settings#Debug Mode|Debug Mode]]
			4. [[#System settings#Heap Trace|Heap Trace]]
		8. [[#Settings (Настройки)#Expansion Modules|Expansion Modules]]
		9. [[#Settings (Настройки)#Clock & Alarm|Clock & Alarm]]
		10. [[#Settings (Настройки)#About|About]]
2. [[#Sub-GHz|Sub-GHz]]
	1. [[#Sub-GHz#Read sub-ghz|Read sub-ghz]]
		1. [[#Read sub-ghz#Настройка частоты|Настройка частоты]]
			1. [[#Настройка частоты#Frequency Analyzer|Frequency Analyzer]]
		2. [[#Read sub-ghz#Hopping|Hopping]]
		3. [[#Read sub-ghz#Bin_RAW|Bin_RAW]]
		4. [[#Read sub-ghz#Прослушивание раций|Прослушивание раций]]
	2. [[#Sub-GHz#Read RAW sub-ghz|Read RAW sub-ghz]]
	3. [[#Sub-GHz#Ручное добавление|Ручное добавление]]
	4. [[#Sub-GHz#Поддерживаемые протоколы|Поддерживаемые протоколы]]
	5. [[#Sub-GHz#Tesla|Tesla]]
	6. [[#Sub-GHz#Антенны|Антенны]]
3. [[#Sub-GHZ Playlist|Sub-GHZ Playlist]]
4. [[#125 kHz Rfid|125 kHz Rfid]]
	1. [[#125 kHz Rfid#Какие бывают RFID-метки|Какие бывают RFID-метки]]
	2. [[#125 kHz Rfid#Отличия RFID 125 кГц и 13.56 МГц|Отличия RFID 125 кГц и 13.56 МГц]]
	3. [[#125 kHz Rfid#Низкочастотные протоколы 125 кГц|Низкочастотные протоколы 125 кГц]]
		1. [[#Низкочастотные протоколы 125 кГц#HID Prox|HID Prox]]
		2. [[#Низкочастотные протоколы 125 кГц#Indala|Indala]]
	4. [[#125 kHz Rfid#Ввод ID карты вручную|Ввод ID карты вручную]]
	5. [[#125 kHz Rfid#Запись болванки 125 кГц|Запись болванки 125 кГц]]
	6. [[#125 kHz Rfid#Чипы в котах и собаках|Чипы в котах и собаках]]
		1. [[#Чипы в котах и собаках#Animal RFID microchips supported|Animal RFID microchips supported]]
		2. [[#Чипы в котах и собаках#Метод 1.  Нащупать самому|Метод 1.  Нащупать самому]]
		3. [[#Чипы в котах и собаках#Метод 2. Поиск флипером|Метод 2. Поиск флипером]]
5. [[#NFC|NFC]]
	1. [[#NFC#Высокочастотные карты 13,56 МГц|Высокочастотные карты 13,56 МГц]]
	2. [[#NFC#Различие чтения UID и данных внутри карты|Различие чтения UID и данных внутри карты]]
	3. [[#NFC#NFC cards type A|NFC cards type A]]
		1. [[#NFC cards type A#MIFARE Classic|MIFARE Classic]]
		2. [[#NFC cards type A#Mifare Ultralight и NTAG|Mifare Ultralight и NTAG]]
		3. [[#NFC cards type A#MIFARE® DESFire|MIFARE® DESFire]]
		4. [[#NFC cards type A#Подорожник|Подорожник]]
			1. [[#Подорожник#Анализ памяти карты|Анализ памяти карты]]
			2. [[#Подорожник#Атака повторного воспроизведения|Атака повторного воспроизведения]]
			3. [[#Подорожник#Мобильное приложение Plantain|Мобильное приложение Plantain]]
	4. [[#NFC#NFC cards type V|NFC cards type V]]
		1. [[#NFC cards type V#ICODE® SLIX|ICODE® SLIX]]
	5. [[#NFC#NFC cards type F|NFC cards type F]]
		1. [[#NFC cards type F#FeliCa™ Lite-S|FeliCa™ Lite-S]]
	6. [[#NFC#NFC cards type B|NFC cards type B]]
		1. [[#NFC cards type B#ST25TB|ST25TB]]
	7. [[#NFC#Банковские карты EMV (PayPass, Apple Pay)|Банковские карты EMV (PayPass, Apple Pay)]]
		1. [[#Банковские карты EMV (PayPass, Apple Pay)#Виртуальная карта ApplePay VS Физическая банковская карта|Виртуальная карта ApplePay VS Физическая банковская карта]]
		2. [[#Банковские карты EMV (PayPass, Apple Pay)#Как украсть деньги с бесконтактной карты и Apple Pay|Как украсть деньги с бесконтактной карты и Apple Pay]]
	8. [[#NFC#MFKey32 attack|MFKey32 attack]]
		1. [[#MFKey32 attack#Troubleshooting|Troubleshooting]]
	9. [[#NFC#Unlocking cards with passwords|Unlocking cards with passwords]]
		1. [[#Unlocking cards with passwords#Генерация пароля|Генерация пароля]]
		2. [[#Unlocking cards with passwords#Ручной ввод пароля|Ручной ввод пароля]]
	10. [[#NFC#Запись NFC|Запись NFC]]
	11. [[#NFC#Создание NFC|Создание NFC]]
6. [[#Infrared|Infrared]]
	1. [[#Infrared#Как работает ИК-порт|Как работает ИК-порт]]
	2. [[#Infrared#Как устроен ИК-порт во Flipper Zero|Как устроен ИК-порт во Flipper Zero]]
	3. [[#Infrared#Что не так с кондиционерами|Что не так с кондиционерами]]
	4. [[#Infrared#Чтение ик|Чтение ик]]
	5. [[#Infrared#Универсальный пульт|Универсальный пульт]]
		1. [[#Универсальный пульт#TV remote|TV remote]]
		2. [[#Универсальный пульт#Audio system remote|Audio system remote]]
		3. [[#Универсальный пульт#Projector remote|Projector remote]]
		4. [[#Универсальный пульт#Air conditioner remote|Air conditioner remote]]
	6. [[#Infrared#Пульты из мобильного приложения|Пульты из мобильного приложения]]
	7. [[#Infrared#Ссылки|Ссылки]]
7. [[#Bluetooth|Bluetooth]]
	1. [[#Bluetooth#BLE Spam|BLE Spam]]
		1. [[#BLE Spam#SEX TOYS|SEX TOYS]]
8. [[#GPIO & modules|GPIO & modules]]
	1. [[#GPIO & modules#GPIO pinout|GPIO pinout]]
		1. [[#GPIO pinout#+3.3 V power (pin 9)|+3.3 V power (pin 9)]]
		2. [[#GPIO pinout#+5 V power (pin 1)|+5 V power (pin 1)]]
		3. [[#GPIO pinout#Input/output pins|Input/output pins]]
		4. [[#GPIO pinout#3.3 V and 5 V tolerance|3.3 V and 5 V tolerance]]
	2. [[#GPIO & modules#GPIO menu|GPIO menu]]
	3. [[#GPIO & modules#Взлом светофоров|Взлом светофоров]]
	4. [[#GPIO & modules#Модуль W5500|Модуль W5500]]
	5. [[#GPIO & modules#Радиомодуль 2.4 ГГц NRF24L01 Mouse Hunter|Радиомодуль 2.4 ГГц NRF24L01 Mouse Hunter]]
		1. [[#Радиомодуль 2.4 ГГц NRF24L01 Mouse Hunter#Купить|Купить]]
		2. [[#Радиомодуль 2.4 ГГц NRF24L01 Mouse Hunter#Сделай сам (pinout)|Сделай сам (pinout)]]
	6. [[#GPIO & modules#Official Wi-Fi Development Board.|Official Wi-Fi Development Board.]]
		1. [[#Official Wi-Fi Development Board.#Where to buy?|Where to buy?]]
		2. [[#Official Wi-Fi Development Board.#Official Purpose Of The Wi-Fi Development Board|Official Purpose Of The Wi-Fi Development Board]]
		3. [[#Official Wi-Fi Development Board.#Community Uses For The Board|Community Uses For The Board]]
		4. [[#Official Wi-Fi Development Board.#Useful Links|Useful Links]]
	7. [[#GPIO & modules#External Radio Module for 433 MHz aka CC1101|External Radio Module for 433 MHz aka CC1101]]
		1. [[#External Radio Module for 433 MHz aka CC1101#CC1101 с внешней антенной, а на самом деле E07-M1101D-SMA|CC1101 с внешней антенной, а на самом деле E07-M1101D-SMA]]
		2. [[#External Radio Module for 433 MHz aka CC1101#Купить готовый|Купить готовый]]
		3. [[#External Radio Module for 433 MHz aka CC1101#Сделать самому|Сделать самому]]
		4. [[#External Radio Module for 433 MHz aka CC1101#Еще вариант на базе СС1101 в исполнении с E07-400MM10S|Еще вариант на базе СС1101 в исполнении с E07-400MM10S]]
		5. [[#External Radio Module for 433 MHz aka CC1101#А можно еще дальше? Или сказ про усиление на базе E07-433M20S|А можно еще дальше? Или сказ про усиление на базе E07-433M20S]]
		6. [[#External Radio Module for 433 MHz aka CC1101#“Only a Sith deals in absolutes” или “Надо больше усиления”|“Only a Sith deals in absolutes” или “Надо больше усиления”]]
		7. [[#External Radio Module for 433 MHz aka CC1101#А что с приемом сигналов?|А что с приемом сигналов?]]
	8. [[#GPIO & modules#External Radio Module for 900 MHz|External Radio Module for 900 MHz]]
		1. [[#External Radio Module for 900 MHz#What is the purpose of this board?|What is the purpose of this board?]]
		2. [[#External Radio Module for 900 MHz#But... WHY?|But... WHY?]]
		3. [[#External Radio Module for 900 MHz#What makes it special?|What makes it special?]]
		4. [[#External Radio Module for 900 MHz#PINOUT|PINOUT]]
	9. [[#GPIO & modules#GPS Module|GPS Module]]
	10. [[#GPIO & modules#Flipper Zero Magspoof Module|Flipper Zero Magspoof Module]]
		1. [[#Flipper Zero Magspoof Module#... What? What the heck is a magspoof?|... What? What the heck is a magspoof?]]
		2. [[#Flipper Zero Magspoof Module#Cool... but why?|Cool... but why?]]
		3. [[#Flipper Zero Magspoof Module#Alright, what's on the board?|Alright, what's on the board?]]
		4. [[#Flipper Zero Magspoof Module#App for this?|App for this?]]
	11. [[#GPIO & modules#RS232|RS232]]
		1. [[#RS232#What is it?|What is it?]]
		2. [[#RS232#What does it do?|What does it do?]]
		3. [[#RS232#What makes it special?|What makes it special?]]
		4. [[#RS232#How to use it:|How to use it:]]
		5. [[#RS232#Why Serial? Isn't it Old?|Why Serial? Isn't it Old?]]
		6. [[#RS232#This seems pretty neat, What are the possibilities?|This seems pretty neat, What are the possibilities?]]
		7. [[#RS232#Why did I make it?|Why did I make it?]]
	12. [[#GPIO & modules#CANBus для Flipper Zero - Модуль подключения к CAN шине|CANBus для Flipper Zero - Модуль подключения к CAN шине]]
		1. [[#CANBus для Flipper Zero - Модуль подключения к CAN шине#Купить|Купить]]
	13. [[#GPIO & modules#ИК-модуль TV Buster 6.3 Вт|ИК-модуль TV Buster 6.3 Вт]]
	14. [[#GPIO & modules#ESP32 aka Marauder|ESP32 aka Marauder]]
		1. [[#ESP32 aka Marauder#Купить|Купить]]
9. [[#iButton|iButton]]
	1. [[#iButton#Что такое iButton|Что такое iButton]]
	2. [[#iButton#Режим эмуляции iButton|Режим эмуляции iButton]]
	3. [[#iButton#iButton через внешний GPIO|iButton через внешний GPIO]]
	4. [[#iButton#Формат данных в ключе Dallas|Формат данных в ключе Dallas]]
	5. [[#iButton#Ввод ID вручную|Ввод ID вручную]]
	6. [[#iButton#Запись ключей 1-Wire Dallas|Запись ключей 1-Wire Dallas]]
	7. [[#iButton#Что такое мастер ключ?|Что такое мастер ключ?]]
	8. [[#iButton#Играясь заблокировали домофон?|Играясь заблокировали домофон?]]
	9. [[#iButton#Вездеходы|Вездеходы]]
10. [[#Bad USB|Bad USB]]
	1. [[#Bad USB#Flipper Zero scripting language|Flipper Zero scripting language]]
	2. [[#Bad USB#Uploading new payloads to Flipper Zero|Uploading new payloads to Flipper Zero]]
	3. [[#Bad USB#Using your Flipper Zero as a BadUSB device|Using your Flipper Zero as a BadUSB device]]
		1. [[#Using your Flipper Zero as a BadUSB device#Via USB connection|Via USB connection]]
		2. [[#Using your Flipper Zero as a BadUSB device#Via BLE сonnection|Via BLE сonnection]]
11. [[#U2F|U2F]]
	1. [[#U2F#Setting up your Flipper Zero as a security key|Setting up your Flipper Zero as a security key]]
	2. [[#U2F#Signing in with your Flipper Zero|Signing in with your Flipper Zero]]
12. [[#Apps|Apps]]
	1. [[#Apps#Bluetooth|Bluetooth]]
		1. [[#Bluetooth#BLE Spam|BLE Spam]]
		2. [[#Bluetooth#BT trigger|BT trigger]]
		3. [[#Bluetooth#Anki Remote|Anki Remote]]
		4. [[#Bluetooth#BT Remote for kodi|BT Remote for kodi]]
		5. [[#Bluetooth#FindMy Flipper|FindMy Flipper]]
		6. [[#Bluetooth#Bluetooth Remote|Bluetooth Remote]]
		7. [[#Bluetooth#PC Monitor|PC Monitor]]
	2. [[#Apps#Games|Games]]
	3. [[#Apps#GPIO|GPIO]]
		1. [[#GPIO#BMI Air Mouse|BMI Air Mouse]]
		2. [[#GPIO#[PMSx003] Airmon|[PMSx003] Airmon]]
		3. [[#GPIO#AVR Flasher|AVR Flasher]]
			1. [[#AVR Flasher#Wiring|Wiring]]
			2. [[#AVR Flasher#Supported Microcontrollers|Supported Microcontrollers]]
		4. [[#GPIO#BarCode ScannerE|BarCode ScannerE]]
		5. [[#GPIO#\[ESP32\] Camera Suite|\[ESP32\] Camera Suite]]
		6. [[#GPIO#Coffee-EEPROM-FAP|Coffee-EEPROM-FAP]]
		7. [[#GPIO#RC2014 ColecoVision|RC2014 ColecoVision]]
		8. [[#GPIO#DAP Link|DAP Link]]
		9. [[#GPIO#\[ESP32\] WiFi Marauder|\[ESP32\] WiFi Marauder]]
		10. [[#GPIO#ESP8266 Deauther|ESP8266 Deauther]]
		11. [[#GPIO#esp8266_deauther v2|esp8266_deauther v2]]
		12. [[#GPIO#IFTTT Virtual Button|IFTTT Virtual Button]]
		13. [[#GPIO#ESP Flasher|ESP Flasher]]
		14. [[#GPIO#\[W5500\] Ethernet|\[W5500\] Ethernet]]
		15. [[#GPIO#Evil captive portal|Evil captive portal]]
		16. [[#GPIO#\[ESP32\] Evil portal|\[ESP32\] Evil portal]]
		17. [[#GPIO#Flashlight|Flashlight]]
		18. [[#GPIO#FlipTDI|FlipTDI]]
		19. [[#GPIO#Flipagotchi|Flipagotchi]]
		20. [[#GPIO#\[J305\]Atomic Dice Roller|\[J305\]Atomic Dice Roller]]
		21. [[#GPIO#\[J305\] geiger counter|\[J305\] geiger counter]]
		22. [[#GPIO#SPI-Terminal|SPI-Terminal]]
		23. [[#GPIO#Scope (flipperscope)|Scope (flipperscope)]]
		24. [[#GPIO#\[TEA5767\] FM Radio|\[TEA5767\] FM Radio]]
		25. [[#GPIO#\[ESP32\] Ghost ESP|\[ESP32\] Ghost ESP]]
		26. [[#GPIO#7-Segment Output|7-Segment Output]]
		27. [[#GPIO#GPIO Controller|GPIO Controller]]
		28. [[#GPIO#GPIO Reader 2|GPIO Reader 2]]
		29. [[#GPIO#Sentry Safe|Sentry Safe]]
		30. [[#GPIO#Timelapse|Timelapse]]
		31. [[#GPIO#\[NMEA\] GPS|\[NMEA\] GPS]]
		32. [[#GPIO#\[HC-SR\] Dist. sensor|\[HC-SR\] Dist. sensor]]
		33. [[#GPIO#i2c Tools|i2c Tools]]
		34. [[#GPIO#INA Meter|INA Meter]]
			1. [[#INA Meter#Supported Sensors:|Supported Sensors:]]
			2. [[#INA Meter#Wiring|Wiring]]
		35. [[#GPIO#Lightmeter|Lightmeter]]
			1. [[#Lightmeter#Lightmeter app for photography|Lightmeter app for photography]]
			2. [[#Lightmeter#Supported sensors|Supported sensors]]
			3. [[#Lightmeter#Wiring|Wiring]]
		36. [[#GPIO#Logic analyzer|Logic analyzer]]
		37. [[#GPIO#Longwave Clock|Longwave Clock]]
		38. [[#GPIO#LORA Terminal|LORA Terminal]]
		39. [[#GPIO#Magspoof|Magspoof]]
		40. [[#GPIO#\[Mx2125\] Accelerometer|\[Mx2125\] Accelerometer]]
		41. [[#GPIO#\[MH-Z19\] CO2 sensor|\[MH-Z19\] CO2 sensor]]
		42. [[#GPIO#NRF24|NRF24]]
		43. [[#GPIO#Pokemon Trade Tool|Pokemon Trade Tool]]
		44. [[#GPIO#RadSens (Radiation Sensor)|RadSens (Radiation Sensor)]]
		45. [[#GPIO#RCWL-516 Motion Sensor|RCWL-516 Motion Sensor]]
		46. [[#GPIO#SD SPI|SD SPI]]
			1. [[#SD SPI#Pinout|Pinout]]
			2. [[#SD SPI#Force Unlock|Force Unlock]]
		47. [[#GPIO#ServoTester и ServoTester 2|ServoTester и ServoTester 2]]
		48. [[#GPIO#Signal Generator|Signal Generator]]
			1. [[#Signal Generator#PWM Mode|PWM Mode]]
			2. [[#Signal Generator#Clock Mode|Clock Mode]]
		49. [[#GPIO#Simultaneous UHF RFID Reader|Simultaneous UHF RFID Reader]]
		50. [[#GPIO#SPI Mem Manager|SPI Mem Manager]]
		51. [[#GPIO#\[Mx2125\] Step Counter|\[Mx2125\] Step Counter]]
		52. [[#GPIO#SWD Probe|SWD Probe]]
		53. [[#GPIO#UART Terminal|UART Terminal]]
			1. [[#UART Terminal#Connecting|Connecting]]
		54. [[#GPIO#u-blox GPS|u-blox GPS]]
		55. [[#GPIO#Temp sensors reader|Temp sensors reader]]
			1. [[#Temp sensors reader#List of supported sensors|List of supported sensors]]
		56. [[#GPIO#\[USPING\] Distance Sensor|\[USPING\] Distance Sensor]]
	4. [[#Apps#Tools|Tools]]
		1. [[#Tools#Key Copier|Key Copier]]
13. [[#Flipper Mobile App|Flipper Mobile App]]
	1. [[#Flipper Mobile App#Connecting to Flipper Zero|Connecting to Flipper Zero]]
		1. [[#Connecting to Flipper Zero#If your Flipper Zero is not detected|If your Flipper Zero is not detected]]
		2. [[#Connecting to Flipper Zero#If Flipper Mobile App fails to synchronize with your Flipper Zero|If Flipper Mobile App fails to synchronize with your Flipper Zero]]
	2. [[#Flipper Mobile App#Flipper Mobile App: overview|Flipper Mobile App: overview]]
14. [[#qFlipper|qFlipper]]
	1. [[#qFlipper#Установка|Установка]]
		1. [[#Установка#Win|Win]]
		2. [[#Установка#Mac|Mac]]
		3. [[#Установка#Lin|Lin]]
			1. [[#Lin#Используя графический интерфейс пользователя|Используя графический интерфейс пользователя]]
			2. [[#Lin#Используя терминал|Используя терминал]]
	2. [[#qFlipper#Обновление флиппера|Обновление флиппера]]
	3. [[#qFlipper#Backup|Backup]]
15. [[#Разработка|Разработка]]
	1. [[#Разработка#"Hello world"|"Hello world"]]
		1. [[#"Hello world"#Шаг первый: учимся собирать прошивку|Шаг первый: учимся собирать прошивку]]
		2. [[#"Hello world"#Шаг второй: пишем приложение|Шаг второй: пишем приложение]]
16. [[#Video Game Module|Video Game Module]]
	1. [[#Video Game Module#Видеовыход|Видеовыход]]
	2. [[#Video Game Module#Гироскоп и акселерометр|Гироскоп и акселерометр]]
	3. [[#Video Game Module#Осциллограф Scoopy|Осциллограф Scoopy]]
	4. [[#Video Game Module#Прошивка и схемы|Прошивка и схемы]]
	5. [[#Video Game Module#Самостоятельная сборка|Самостоятельная сборка]]
	6. [[#Video Game Module#Video Game Module Tool|Video Game Module Tool]]




# Основы

![[controls.webp]]

## Включение
Нажимаем и держим 3 секунды кнопку `BACK`

![[flipper_power_on.mp4]]

Если не включается, то:
- Проверяем заряд батарей (ставим на зарядку)
- Зажимаем `LEFT` и `BACK` на 5 секунд
- Если это не помогло, переходим к разделу [[#Firmware Recovery]]


## Карта microSD
На карте microSD хранятся различные типы данных, такие как ключи, карточки, пульты дистанционного управления, базы данных и многое другое. Flipper Zero поддерживает карты microSD объемом до 256 ГБ, но для хранения всех необходимых данных достаточно обычной карты microSD объемом 16-32 ГБ.

Flipper Zero поддерживает FAT12, FAT16, FAT32, и exFAT.

Имейте в виду, что Flipper Zero может потребоваться больше времени для распознавания карты microSD с большим объемом памяти.


![[Flipper_Sd_Mount3_compressed.mp4]]

Важно использовать высококачественную карту SanDisk, Kingston или других брендов.
Важны именно качество и надежность, а не скорость. В отличие от современных смартфонов и компьютеров, использующих высокоскоростной SDIO-интерфейс, Flipper Zero использует более медленный и энергоэффективный SPI-интерфейс. 
Несмотря на то, что SPI-интерфейс Flipper Zero работает медленнее, чем SDIO, он может считывать данные со скоростью почти 600 кибибайт в секунду, что достаточно для выполнения задач устройства.


### Flipper не видит карту

![[no_card.webp]]

- Если карта сдохла - меняем
- Карта не поддерживает SPI - меняем
- Карта имеет неподдерживаемую файловую систему - форматируем

**Main Menu -> Settings -> Storage**.
Выбираем **Format SD Card** и жмем `RIGHT`.
![[flipper-zero-microsd-card-formatted.webp]]

- А может у вас просто пыль в слоте.

P.S. Флиппер хранит базу на карте и если карту отформатировали - всегда придется [[#Прошивка (Firmware)|обновиться. ]]

### Безопасное извлечение

**Main Menu -> Settings -> Storage**.
Выбираем **Unmount SD Card** и следуем инструкциям

![[unmounted-microsd-card.webp]]

Как только карта отмонтирована, ее можно доставать

![[sd_removal_compressed.mp4]]



## Прошивка (Firmware)

Перед прошивкой вставьте [[#Карта microSD|карту]]
Прошивку можно обновить с помощью мобильного приложения или qFlipper.

Что касается выбора прошивки:
По моему скромному мнению прошивка `Unleashed` - вне всякой конкуренции по стабильности и возможностям.

- Github: https://github.com/DarkFlippers/unleashed-firmware
- Telegram: https://t.me/flipperzero_unofficial_ru
- Releases: https://t.me/unleashed_fw

Так что переходим в ТГ с релизами и качаем *Build with extra apps*

### Mobile App
App Store: https://apps.apple.com/app/flipper-mobile-app/id1534655259
Google Play: https://play.google.com/store/apps/details?id=com.flipperdevices.app

#### Подключение телефона к Flipper Zero

1. Активируйте Bluetooth на своем телефоне.
2. Активируйте Bluetooth на своем Flipper Zero:
    - Перейдите в **Main Menu** **-> Settings** **->** **Bluetooth**.
    - Переключите **Bluetooth** в **ON**
3. В мобильном приложении нажмите **Connect**.
4. На следующем экране нажмите **Connect** напротив найденного флиппера

![[flipper-mobile-app-bluetooth-connection.webp]]

5. В мобильном приложении Flipper введите код сопряжения, который отображается на экране Flipper Zero.
6. Нажмите на **Pair**, чтобы завершить сопряжение.

##### Если флиппер не обнаруживается:
- Проверяем что bluetooth на флиппере включен
- Проверяем что bluetooth на телефоне включен
- Проверяем что мобильное приложение последней версии
- [[#Перезагрузка|Перезагружаем]] flipper
- Если не помогает, заставляем флиппер забыть все устройства (Unpair All Devices в Settings)
![[flipper-zero-bluetooth-settings.webp]]
- Если ничего не помогло, обновляем через [[#qFlipper]]


#### Обновление прошивки в мобильном приложении
1. На главном экране нажмите на строку "Update Channel"
2. Выберите "Custom"

![[Custom_update.jpg]]

3. Нажмите "`CHOOSE FILE`" и выберите tgz файл прошивки и update

Процесс обновления займет около 10 минут
![[update_proc.jpg]]

### Обновление через qFlipper

![[qflipper_update.webp]]

Обновление описано в соответствующем [[#qFlipper|разделе]]

### Internal storage is full

![[internal-storage.webp]]

1. Сделать бекап [[#Backup|через qFlipper]]
2. Сбросить до заводских
  
#### через Settings

![[factory_reset_settings.png]]

**Settings** **->** **Storage**.
Select **Factory Reset**.
Press **Erase** five times.

![[Factory_Reset_compressed.mp4]]


#### через qFlipper

Запускаем **qFlipper**.
Подключаем Flipper Zero USB кабелем.
Жмем **Advanced controls** и `ERASE`.

![[qflipper_erase.webp]]

#### Восстановление из backup
Запускаем **qFlipper**.
Подключаем Flipper Zero USB кабелем.
Жмем **Advanced controls** и `RESTORE`

![[qflipper_restore.webp]]



### Firmware Recovery

Испорченную прошивку можно исправить с помощью [[#qFlipper]] и встроенного USB Device Firmware Update (DFU) загрузчика.

![[firmware_repair.png]]

#### Переключаемся в Recovery
##### Если девайс работает но не обновляется

Переключаем Flipper Zero в Recovery mode:

1.  **Main Menu -> Settings -> Power**.
2. **Reboot -> Firmware Upgrade**.
3. `RIGHT` to reboot.

![[flipper-zero-dfu-mode-firmware-upgrade.webp]]


4. Подключаем проводом к компу
5. [[#Обновление флиппера|Обновляем через qFlipper]]

В качестве альтернативы можно перевести флиппер в нужный режим кнопками:
1. Зажимаем `LEFT` и `BACK` на 5 секунд
2. Отпускаем `BACK` удерживаем `LEFT` пока не мигнет синий светодиод

![[Flipper_Zero_DFU_mode_reboot.mp4]]
3. Подключаем проводом к компу
4. [[#Обновление флиппера|Обновляем через qFlipper]]


Чтобы выйти из режима Recovery зажимаем `LEFT` и `BACK` 

##### Если девайс окирпичен:

1. Отключите USB-кабель от устройства Flipper Zero, если оно подключено.
2. Нажмите и удерживайте кнопки `OK` и `BACK` в течение 30 секунд. Если на экране устройства Flipper Zero не отображается никаких указаний, это нормально.
3. Подключите устройство Flipper Zero к компьютеру с помощью USB-кабеля. Компьютер должен определить ваш Flipper Zero как устройство DFU.

![[flipper_recovery_dfu_mode_compressed.mp4]]

4. [[#Обновление флиппера|Обновляем через qFlipper]]

Если не помогает:
- пробуем другой кабель
- пробуем подключать без microsd карты
- пробуем подключить в другой usb порт

#### Repair
В qFlipper жмем `REPAIR`

![[qflipper_repair.webp]]



## Основной экран (Desktop)
Рабочий стол - это дом вашего цифрового питомца. Здесь вы можете узнать, что делает ваш питомец-дельфин и как он себя чувствует. Кроме того, здесь вы найдете строку состояния с различными индикаторами, такими как уровень заряда батареи, состояние зарядки, подключение по Bluetooth, состояние карты microSD и другие.

### Status bar

![[status1.png]]

![[status2.png]]



### Навигация

![[nav.webp]]

О настройке ярлыков см в  [[#Settings (Настройки)]]


### Главное меню
При нажатии `OK` мы попадаем в главное меню

![[main-menu-1.webp]]

На каждый пункт меню  - свой раздел этого руководства


### Меню блокировки

Меню доступно по кнопке `UP`

![[lock.webp]]


#### Lock

Блокирует флиппер. Для разблокировки нажать три раза `BACK`
В [[#Desktop settings|настройках]] можно задать pin

#### Mute

Убирает звук и вибро нотификации

#### Dummy Mode

Переводит девайс в тупой режим. Через настройки можно поставить быстрый доступ к определенным приложениям (например играм).

![[dummy.webp]]

Для выхода - `UP` и **Default Mode**


### Passport

Профиль вашего питомца с именем, прогрессом, уровнем, настроением

![[passport.webp]]

Так же на этот экран можно попасть через **Main Menu -> Settings -> Passport**.


### Archive
Быстрый доступ к сохраненным тэгам, ключам, пультам, полезной нагрузке и пр.

![[archive.webp]]



### Device Info

Об устройстве. Версия прошивки и железа

![[about.webp]]

### Quick Access Apps

Функция быстрого доступа к приложениям позволяет назначать приложения на кнопки и открывать их прямо с главного экрана. Таким образом, вам не нужно будет искать их в главном меню всякий раз, когда вы захотите их запустить.

![[quick-access-apps-desktop-1.webp]]

Переназначить можно через  **Main Menu -> Settings -> Desktop  -> Set Quick Access Apps**.


## Тамагочи

![[tamagochi.webp]]

![[tamagochi2.webp]]


Чем больше пользуешься, тем счастливее дельфинчик. 
Кроме как на *нескучные обои* это ни на что не влияет. Можно просто включить Happy Mode в настройках **Main Menu -> Settings -> Desktop -> Happy Mode**.

## Питание
Flipper питается от 2100 mAh "lithium-ion polymer rechargeable battery"

Чтобы посмотреть информацию о батареи идем на страницу **Main Menu -> Settings -> Power -> Battery Info**.

![[battery_info.webp]]

### Выключение питания:
**Main Menu -> Settings -> Power -> Power OFF** 

или зажать `OK` и `BACK`

### Sleep mode
Когда на вашем устройстве Flipper Zero не запущены приложения или не установлены соединения, устройство переходит в спящий режим, потребляемая мощность которого составляет около 1,5 мА.

Если устройство не переходит в спящий режим, проверьте настройки:
![[sleep.png]]

Доступны два режима ожидания: Default и Legacy. Энергопотребление в Default режиме составляет около 1,5 мА, что увеличивает время автономной работы. Однако при использовании этого режима могут возникать сбои в работе устройства. В Legacy режиме энергопотребление составляет 9 мА, что сокращает время автономной работы, но также повышает стабильность работы вашего устройства.


Вы можете переключиться в Legacy спящий режим в настройках:
**Main Menu -> Settings -> System** and setting **Sleep Method** to **Legacy**.

## Перезагрузка
Зажимаем `LEFT` и `BACK` на 5 секунд

![[Flipper_Zero_simple_reboot_5sec_compressed.mp4]]

```ad-tip

Так же перезагрузка доступна через **Settings -> Power -> Reboot**.

Из мобильного приложения **Options** -> **Reboot Flipper**.

Hard reboot - зажать `BACK` на 30 секунд

Перезагрузка в recovery описана в [[#Переключаемся в Recovery|соответствующем разделе]]
```


## Settings (Настройки)

**Main Menu ->** **Settings**

![[settings.webp]]

### Bluetooth

![[bluetooth-settings.webp]]

### LCD and Notifications

![[flipper-zero-lcd-settings.webp]]

### Storage

![[flipper-zero-storage-settings.webp]]

### MicroSD card benchmark

Не знаю зачем нужен бенчмарк в SPI режиме, но он есть

![[flipper-zero-microsd-card-benchmark.webp]]

### Power

![[flipper-zero-power-settings.webp]]

### Desktop settings

Тот самый раздел меню, где можно задать pin устройства, happy mode и изменить имя флиппера

![[flipper-zero-desktop-settings.webp]]

P.S. Pin можно сбросить возвратом к заводским настройкам


### System settings

![[flipper-zero-system-settings.webp]]

- Переключение для правшей/левшей
- предпочитаемые единицы измерения.
- форматы времени и даты.
- насколько подробно будут отображаться записи в журналах.
- режим отладки и анализ утечек памяти.
- Отключение режима энергосбережения
- настройки присвоения имен новым файлам

#### Logs

Сообщения журнала выводятся на консоль через UART, а также могут быть выведены в интерфейс командной строки (CLI) с помощью команды log.

The following log level options are available:

- **Default:** equivalent to the Info log level.    
- **None:** no events are logged.    
- **Error:** only errors are logged.    
- **Warning:** errors and warnings are logged.    
- **Info:** errors, warnings, and info messages are logged.    
- **Debug:** errors, warnings, info, and debug messages are logged.    
- **Trace:** errors, warnings, info, and debug messages are logged, as well as tracing information from various subsystems.

```ad-important
Чем более подробный лог ставим - тем медленнее работает флиппер
```


#### Log Device

- **USART:** uses pins 13 and 14. This option is set by default.    
- **LPUART:** uses pins 15 and 16.    
- **None:** disables logging via UART.

#### Debug Mode
Включение режима обеспечивает дополнительные возможности отладки в приложениях Sub-GHz, 125 kHz RFID, NFC, и Infrared, а также новые команды в CLI. 
Например, вы можете считывать raw данные низкочастотной RFID-карты, перейдя в Main Menu -> 125 kHz RFID -> Extra Actions -> Read RAW RFID data.


Режим отладки также предоставляет доступ к интерфейсу отладки по SWD. Если вы отключите режим отладки на вашем Flipper Zero, SWD-интерфейс станет недоступен.


#### Heap Trace
журнал выделений и освобождений памяти, которые происходят в вашем Flipper Zero. Трассировка записывает информацию о каждом выделении, включая размер выделенного блока памяти, адрес блока памяти и время, в течение которого он был выделен. Трассировка кучи полезна для устранения проблем таких как утечки памяти. Сообщения журнала трассировки кучи выводятся на консоль через UART.

### Expansion Modules
Вы можете выбрать, какое оборудование UART будет использоваться для взаимодействия с внешними модулями

- **USART:** uses pins 13 and 14. This option is set by default.
- **LPUART:** pins 15 and 16.    
- **None:** disables expansion module support.

### Clock & Alarm
Часы и будильник

![[clock.webp]]

### About
Информация об устройстве



# Sub-GHz

```ad-warning
Не пытайтесь экспериментировать со своим автомобилем. В большинстве современных решений используются rolling коды и блокировка при рассинхроне.
Вы можете просто заблокировать штатные ключи
```

Прием и передача радио-сигналов на частоте от 300 до 928 MHz

![[subghzhw.webp]]

## Read sub-ghz

![[Sub-GHz_read_8-10-22_compressed.mp4]]

### Настройка частоты

Чтобы правильно прочитать сигнал, надо выставить частоту и модуляцию


![[subghz_read_conf.webp]]

#### Frequency Analyzer
**Main Menu** **-> Sub-GHz -> Frequency Analyzer**.

![[subghz_freq_an.webp]]

### Hopping
![[Sub-GHz_Hopping-2022-10-08_compressed.mp4]]

### Bin_RAW
Эта опция позволяет обрабатывать сигналы, которые не были декодированы в процессе считывания. Обработка включает в себя устранение фонового шума, удаление повторяющихся сегментов сигнала и исправление ошибок синхронизации.

Чтобы использовать эту функцию, вам необходимо вручную включить опцию Bin_RAW. Кроме того, важно убедиться, что частота и параметры модуляции согласуются с вашим пультом дистанционного управления.

### Прослушивание раций

**Main Menu -> Sub-GHz**.
- **Read** — to listen only.
  _or_
-  **Read RAW** — to listen and record.
  
Go to **Config**.
Set **Frequency** to the frequency of the walkie-talkie you want to listen to.
Set **Modulation** to **FM238**.
Set **Sound** to **ON**.
(Optional) If you’ve selected **Read RAW**, you can also configure **RSSI Threshold** to only record signals that exceed the set signal strength level.
Press **BACK**.
If you’ve selected **Read RAW**, press **OK** to start listening.

## Read RAW sub-ghz
Запись сигнала без декодирования

**Main Menu -> Sub-GHz  -> Read RAW

![[Sub-GHz_Read_RAW_2022-10-08_compressed.mp4]]

## Ручное добавление

**Main Menu** **-> Sub-GHz** **-> Add Manually**.

![[Add_manually_compressed_1.mp4]]

## Поддерживаемые протоколы
Encryption protocol legend:

- **Static** - not encrypted protocol. Flipper Zero can decode, save, and playback signals from these radio remotes.
    
- **Dynamic** - encrypted protocol. Flipper Zero can decode signals from these radio remotes. For security reasons, the save function is disabled.
    

|**Vendors and devices**|**Encryption protocol**|**Frequency & modulation** (proven compatibility)|
|---|---|---|
|**Airforce**|Static|433.92 AM|
|**A.P.S** 2300, 2500, 2000, 1500, 1000, 500, 3000, 2550, 2450|Dynamic|433.92 AM|
|**Alligator** D-810, D-930, L330, M-550, M-500, NS-105, NS-205, NS-305, NS-405, NS-505, NS-605, S-275, S-750RS|Dynamic|433.92 AM|
|**Allmatic**|Dynamic|433.92 AM|
|**Alutech** AT-4N|Dynamic|433.92 AM|
|**AN-Motors**|Dynamic|433.92 AM|
|**Ansonic**|Static|433.92 AM|
|**Beninca**|Dynamic|433.92 AM|
|**BERNER**|Static|433.92 AM|
|**Bytec** (Princeton)|Static|433.92 AM|
|**CAME** 12bit, 24bit|Static|433.92 AM|
|**CAME** ATOMO, TOP44r, TWIN, Space|Dynamic|433.92 AM|
|**Cenmax** A-900, ST-5A, Vigilant V-5A, ST-7A, Vigilant V-7A|Dynamic|433.92 AM|
|**Chamberlain** (before 2004)|Dynamic|310.00, 315.00, 390.00 AM|
|**Chamberlain** (after 2004)|Dynamic|310.00, 315.00, 390.00 AM|
|**Chamberlain** 7-Code|Static|390.00 AM|
|**Chamberlain** 8-Code|Static|390.00 AM|
|**Chamberlain** 9-Code|Static|390.00 AM|
|**Clemsa**|Static|433.92 AM|
|**Clemsa Mutancode**|Dynamic|433.92 AM|
|**Comunelo**|Dynamic|433.92 AM|
|**DEA**|Dynamic|433.92 AM|
|**Doitrand**|Static|433.92 AM|
|**Dooya**|Static|433.92 AM|
|**DoorHan**|Dynamic|433.92 AM|
|**DTM**|Dynamic|433.92 AM|
|**EcoStar**|Dynamic|433.92 AM|
|**Elimes**|Dynamic|433.92 AM|
|**ELKA**|Static|433.92 AM|
|**FAAC** RC|Dynamic|433.92 AM|
|**FAAC** XT|Dynamic|433.92 AM|
|**FAAC** SLH|Dynamic|433.92 AM|
|**Faraon**|Dynamic|433.92 AM|
|**Firefly**|Static|300.00 AM|
|**Gate-TX**|Static|433.92 AM|
|**Genius**|Dynamic|433.92 AM|
|**GIBIDI**|Dynamic|433.92 AM|
|**GSN**|Dynamic|433.92 AM|
|**GSN** (Princeton)|Static|433.92 AM|
|**Guard** RF-311A|Dynamic|433.92 AM|
|**Harpoon** BS-2000|Dynamic|433.92 AM|
|**Holtek**|Static|418.00 AM|
|**Holtek** HT12x|Static|433.92 AM|
|**Honeywell** WBD|Static|433.92 AM|
|**HORMANN** HSM|Static|433.92 AM|
|**iDo 117/111** (PT4301-X)|Dynamic|433.92 AM|
|**Intertechno** V3|Static|433.92 AM|
|**IronLogic**|Dynamic|433.92 AM|
|**Jaguar** EZ-Beta, JX-1000, XS-2700|Dynamic|433.92 AM|
|**JCM Tech**|Dynamic|433.92 AM|
|**KEY**|Dynamic|433.92 AM|
|**KGB** FX-1, FX-5|Dynamic|433.92 AM|
|**KingGates** Stylo 4K|Dynamic|433.92, 868.35 AM|
|**Leopard** LS50/10|Dynamic|433.92 AM|
|**Linear**|Static|300.00 AM|
|**Linear** Delta 3|Static|318.00 AM|
|**Linear** MegaCode|Static|318.00 AM|
|**LiftMaster**|Static|310.00, 318.00, 390.00 AM|
|**Magellen**|Static|433.92 AM|
|**Marantec**|Static|433.92 AM|
|**Mongoose** 7000 RF, AMG-850C, 800C, IQ-215|Dynamic|433.92 AM|
|**Nero** Radio|Static|434.42 AM|
|**Nero** Sketch|Static|433.92 AM|
|**Nice** FLO 12bit/24bit,|Static|433.92 AM|
|**Nice** FLOR-S|Dynamic|433.92 AM|
|**Nice** Mhouse|Dynamic|433.92 AM|
|**Nice** One|Dynamic|433.92 AM|
|**Nice** Smilo|Dynamic|433.92 AM|
|**Normstahl**|Dynamic|433.92 AM|
|**Novoferm** MCHS43-2, MTR43-2, MNHS433-02, MNHS433-04, Novotron 502 MAX43-2, Novotron 504 MAX43-4, Novotron 512 MIX 43-2, Mini-Novotron 522, Mini-Novotron 524, Mini-Novotron 522 Design, Mini-Novotron 524 Design|Dynamic|433.92 AM|
|**Pantera** CL-500, CL400, CL600, CLK-355, SLK-2i, SLK-2i/3i/4i/5i/7i, SLK-25SC, SLR-5100, XS-1500, XS-2000, XS-1000, XS-1700, XS-100, XS-2600, XS-2700|Dynamic|433.92 AM|
|**Partisan** RX-1|Dynamic|433.92 AM|
|**Phoenix** V2|Static|433.92 AM|
|**Phox**|Static|433.92 AM|
|**Prastel**|Static|433.92 AM|
|**Princeton**|Static|315.00, 433.92, 868.35 AM|
|**Reef**|Dynamic|433.92 AM|
|**Scher-Khan** III, IV, V (Magic Dynamic Code 51bit)|Dynamic|433.92 AM|
|**Sheriff** APS-2400, APS-25 PRO, APS-35 PRO, ZX-925, ZX-900, ZX-910, APS-75, ZX-600|Dynamic|433.92 AM|
|**SMC** 5326|Static|315.00, 318.00, 433.42 AM|
|**Somfy** Keytis RTS|Dynamic|433.42 AM|
|**Somfy** Telis RTS|Dynamic|433.42 AM|
|**Sommer**|Dynamic|433.92 AM|
|**StarLine** A1, A2, A4, A6, A7, A8, A9, Moto V7, B6, B9 (for additional control)|Dynamic|433.92 AM|
|**Stilmatic** HCS101|Dynamic|433.92 AM|
|**Tantos-Proteus** (Princeton)|Static|433.92 AM|
|**TEDSEN**|Static|433.92 AM|
|**TELETASTER**|Static|433.92 AM|
|**Tomahawk** 9010, TW-9000, TW-9010, TW-7000, LR-950, TZ-9010, SL-950, D-700, D-900, S-700, 9030, TW-9030, TW-7010, TW-9020, TZ-7010, TZ-9020, TZ-9030, H1, H2, Z5, Z3, X3, X5|Dynamic|433.92 AM|
|**Unilarm**|Static|315.00, 318.00, 433.42 AM|
|**Wisniowski** MIDO|Dynamic|433.92 AM|

## Tesla
TODO

## Антенны
TODO
https://habr.com/ru/articles/795253/
https://habr.com/ru/articles/801801/
https://habr.com/ru/articles/795253/

# Sub-GHZ Playlist

# 125 kHz Rfid

RFID – это технология для бесконтактных радио-меток, используемых повсюду: в домофонах, платежных картах, проездных, пропусках в офисы, для учета домашних животных, автомобилей и т.д. Есть два основных типа RFID меток, которые мы используем в обычной жизни: низкочастотные и высокочастотные.  
  

- **Низкочастотные** (Low Frequency: 125 кГц) — имеют большую дальность чтения. Небезопасные и тупые. Используются в примитивных системах контроля доступа: домофонах, офисных пропусках, абонементах в спортзал.
- **Высокочастотные** (High Frequency: 13,56 МГц) — имеют меньшую дальность работы по сравнению с низкочастотными, и могут иметь сложные протоколы, средства шифрования, аутентификации, криптографии. Используются в бесконтактных банковских картах, проездных билетах, безопасных пропусках.

![[rfid_antenna.webp]]



## Какие бывают RFID-метки
  
Внешний вид RFID-меток может быть совершенно разный: толстые/тонкие карты, брелоки для домофонов, браслеты, кольца, монеты и даже наклейки. При этом только по внешнему виду нельзя однозначно сказать, на какой частоте и по какому протоколу работает метка.

![[rfid.jpeg]]


## Отличия RFID 125 кГц и 13.56 МГц

  
Проще всего понять в каком диапазоне работает RFID-метка по виду антенны. У низкочастотных меток (125 кГц) антенна сделана из очень тонкой проволоки, буквально тоньше волоса, и огромного числа витков. Поэтому такая антенна выглядит как цельный кусок металла. У высокочастотных карт (13.56 МГц) антенна имеет намного меньше витков и более толстую проволоку или дорожки. Так что между витками видны зазоры.

![[rfid2.jpeg]]

## Низкочастотные протоколы 125 кГц

В низкочастотных метках хранятся короткие ID карты, длиной в несколько байт. Эти ID прописываются в базу данных контроллера или домофона. При этом карта просто передает свой ID любому желающему, как только на нее подано электричество. Часто ID карты написан на ней самой и его можно сфотографировать и ввести вручную во Флиппер.  
  
**Популярные типы 125 kHz протоколов:**  

- **EM-Marin** — EM4100, EM4102. Самый популярный протокол в СНГ. Очень простой и стабильный в работе, может считываться с расстояния метра.
- **HID Prox II** — низкочастотный протокол от компании HID Global. Более распространен на западе, но встречается и в СНГ. Более сложный в работе, считыватели и карты относительно дорогие.
- **Indala** — очень старый низкочастотный протокол, придуманный компанией Motorola, но потом выкупленный HID. Встречается реже двух предыдущих, выходит из использования, но по-прежнему иногда встречается.

**Другие поддерживаемые протоколы:

- IDTECK Idteck    
- Kantech IoProx XSF    
- AWID
-  FECAVA FDX-A    
- ISO FDX-B    
- Generic HID Prox    
- Generic HID Ext    
- Farpointe Pyramid    
- Viking    
- Jablotron    
- Paradox    
- PAC Stanley    
- Keri    
- Gallagher    
- Honeywell Nexwatch    
- Electra    
- Securakey    
- Guardall G-Prox II    
- Noralsy

В СНГ наиболее распространен RFID-формат EM-Marin. Он прост и не защищен от копирования. EM-Marin обычно выполнен на базе чипа EM4100. Существуют и другие чипы, работающие по тому же принципу, например EM4305 – в отличие от EM4100 его можно перезаписывать.  
  
Для считывания низкочастотной карты нужно зайти в меню Флиппера `125 kHz RFID —> Read` и приложить метку к задней крышке. Флиппер определит протокол метки самостоятельно и отобразит его название вместе с ID карты. Так как за один проход, Флиппер пытается по очереди пробовать все типы протоколов, это занимает время. Например, для считывания карт Indala требуется несколько секунд.

![[rfid3.jpeg]]

Уникальный код EM4100 состоит из 5 байт. Иногда он написан на RFID-карте. Уникальный код может быть записан сразу в нескольких форматах: десятичном и текстовом. Флиппер использует шестнадцатеричный формат при отображении уникального кода. Но на картах EM-Marin обычно написаны не все 5 байт, а только младшие 3 байта. Остальные 2 байта придется перебирать, если нет возможности считать карту.

### HID Prox
Компания HID Global — самый крупный производитель RFID оборудования в мире. У них есть несколько фирменных низкочастотных и высокочастотных RFID-протоколов. Наиболее популярный низкочастотный HID-протокол это 26-битный H10301 (HID26, он же HID PROX II). Уникальный код в нем состоит из 3 байт (24 бита), еще 2 бита используются для контроля четности (проверки целостности).  
  
На некоторых HID26 картах написаны цифры – они обозначают номер партии и ID карты. Полностью узнать 3 байта уникального кода по этим цифрам нельзя, на карте написаны лишь 2 байта в десятичной форме: Card ID.

![[hid_rfid.jpeg]]

### Indala

  
RFID-протокол Indala был разработан компанией Motorola, и потом куплен HID. Это очень старый протокол, и современные производители СКУД его не используют. Но в реальной жизни Indala все еще изредка встречается. Флиппер умеет работать с протоколом Indala I40134.

Так же, как HID26, уникальный код карт Indala I40134 состоит из 3 байт. К сожалению, структура данных в картах Indala это не публичная информация, и все, кто вынужден поддерживать этот протокол, сами придумывают, какой порядок байт выбрать, и как интерпретировать сигнал на низком уровне.  
  
Все эти протоколы настолько простые, что ID карты можно просто ввести вручную, не имея оригинальной карты под рукой. Можно тупо прислать текстовый ID карты, и владелец Флиппера сможет ввести его вручную.

## Ввод ID карты вручную

Чтобы добавить ID карты вручную, нужно зайти в меню `125 kHz RFID —> Add manually`, выбрать протокол и ввести ID карты. Добавленная карта сохранится на SD-карту, и ее можно будет использовать для эмуляции или записи на болванку.

## Запись болванки 125 кГц
Существуют специальные типы карт болванок, на которые можно записать любой из трех протоколов описанных выше (EM-Marin, HID Prox, Indala). Самый популярный тип болванок — это T5577. Для записи болванки нужно перейти в меню `125 kHz RFID —> Saved`, выбрать нужный ключ и нажать `Write`.


## Чипы в котах и собаках

Flipper Zero позволяет считывать микрочипы животных. Антенна Flipper Zero была разработана для работы на частоте 125 кГц, в то время как большинство микрочипов животных работают на частоте 134,2 кГц. В качестве дополнительной функции была реализована поддержка считывания микрочипов с частотой 134,2 кГц. Чтобы считывать микрочип, подержите Flipper Zero над микрочипом животного в течение 3 секунд. В противном случае Flipper Zero не распознает его.

![[animal0.webp]]

"Пробить" ID чипа можно на следующих сайтах:
https://animal-id.net/en/pets/lookup
https://www.aaha.org/for-veterinary-professionals/microchip-search/
https://www.europetnet.org/
https://www.petmaxx.com/


![[animal.webp]]

### Animal RFID microchips supported

- **Compatible microchips:** [FDX-B](https://www.priority1design.com.au/fdx-b_animal_identification_protocol.html "FDX-B") (15-digit, ISO-compliant, including thermo microchips), FDX-A (10-digit, not ISO-compliant), and other chips supported by Flipper Zero in the form factor of an animal microchip.
- **Reading frequency:** 125 kHz. Flipper Zero can also read microchips in the 110-140 kHz range but with a shorter reading distance.
- **Reading distance:** 10 mm (0.39 inch).

![[animal2.webp]]

### Метод 1.  Нащупать самому
как только нащупали **Main Menu -> 125 kHz RFID -> Extra Actions**.
Select **Read ASK** and press **OK**.

### Метод 2. Поиск флипером

**Main Menu -> 125 kHz RFID -> Extra Actions**.
Select **Read ASK** and press **OK**.

Далее ведем вдоль, задерживаясь на 3 секунды

![[animal3.webp]]

![[animal4.webp]]

LED сигнал будет ориентиром

![[animal5.webp]]

Если не получилось, поворачиваем флиппер на 90 градусов

![[animal6.webp]]


Некоторые чипы могут быть NFC. Смотрите соответствующий раздел

# NFC

```ad-tip
Банковские и транспортные карты это тоже nfc. Будете спрашивать в чате прошивки - схлопочете бан
```

## Высокочастотные карты 13,56 МГц

Высокочастотные метки 13,56 МГц состоят из целого стека стандартов и протоколов — весь этот стек принято называть технологией [NFC](https://nfc-forum.org/what-is-nfc/about-the-technology/), что не всегда правильно. Основная часть протоколов основана на стандарте ISO 14443 — это базовый набор протоколов физического и логического уровня, на котором стоят высокоуровневые протоколы, и по мотивам которых созданы альтернативные низкоуровневые стандарты, например ISO 18092.  
  
Наиболее часто встречаемой является реализация **ISO 14443-A**, ее используют почти все исследуемые мною проездные, пропуска и банковские карты.

![[nfc.jpeg]]

Упрощенно архитектура NFC выглядит так: на низкоуровневой базе ISO 14443 реализован транспортный протокол, он выбирается производителем. Например, компания NXP придумала свой высокоуровневый транспортный протокол карт Mifare, хотя на канальном уровне, карты Mifare основаны на стандарте ISO 14443-A.  
  
Флиппер умеет взаимодействовать как с низким уровнем протоколов ISO 14443, так и с протоколами передачи данных Mifare Ultralight и EMV банковских карт. 

Все высокочастотные карты, работающие на базе ISO 14443-A, имеют уникальный идентификатор чипа — UID. Это серийный номер карточки, подобно MAC-адресу сетевой карты. UID бывает длиной 4, 7 и очень редко 10 байт. UID не защищен от чтения и не является секретным, иногда он даже написан на карточке.

В реальности существуют много СКУД-ов, использующих UID для авторизации доступа. Такое встречается, даже когда RFID-метки имеют криптографическую защиту. По уровню безопасности это мало чем отличается от тупых низкочастотных карт 125 кГц. Виртуальные карты (например, Apple Pay) намеренно используют динамический UID, чтобы владельцы телефонов не использовали платежное приложение как ключ для дверей.

Так как UID это низкоуровневый атрибут, то возможна ситуация, когда UID прочитан, а высокоуровневый протокол передачи данных еще неизвестен. Во Флиппере реализованы чтение, эмуляция и ручное добавление UID, как раз для примитивных считывателей, которые используют UID для авторизации.

## Различие чтения UID и данных внутри карты

![[nfc2.jpeg]]

Чтение меток 13,56 МГц во Флиппере можно разделить на 2 части:  
  

- **Низкоуровневое** — первичное чтение только UID, SAK и ATQA. На основе этих данных Флиппер пытается предположить, на каком высокоуровневом протоколе работает карта. Это угадывание не может быть на 100% точным, это только предположение.
- **Высокоуровневое** — чтение данных в памяти карты используя конкретный высокоуровневый протокол, например, чтение данных в картах Mifare Ultralight, чтение содержимого секторов Mifare Classic, чтение реквизитов банковской карты PayPass/Apple Pay

Для чтения карты с помощью конкретного высокоуровневого протокола нужно перейти в `NFC —> Extra Actions -> Read Specific Card Type` и выбрать необходимый тип метки.  
  
Для определения типа метки и чтения UID нужно перейти в `NFC -> Read card`. 

## NFC cards type A

### MIFARE Classic
Flipper Zero может читать MIFARE Classic 1K, MIFARE Classic 4K, and MIFARE Classic Mini. 

Для того чтобы прочитать данные в секторах, Flipper Zero должен найти все 32 ключа для 16 секторов (MIFARE Classic 1K), 80 ключей для 40 секторов (MIFARE Classic 4K), и 10 ключей для 5 секторов (MIFARE Classic Mini). Для этого Flipper Zero использует ключи из встроенного словаря (**System dictionary**.)

В словарь можно добавлять свои ключи через **Main Menu** **->** **NFC ->** **Extra Actions -> MIFARE Classic Keys**.

### Mifare Ultralight и NTAG

Mifare — семейство бесконтактных смарт-карт, имеющих собственные разные высокоуровневые протоколы. Mifare Ultralight — самый простой тип карт из семейства. В базовой версии он не использует криптографическую защиты и имеет только 64 байта встроенной памяти. Флиппер поддерживает чтение и эмуляцию Mifare Ultralight. Такие метки иногда используют как домофонные брелки, пропуска и проездные. Например, московские транспортные билеты «единый» и «90 минут» выполнены как раз на основе карт Mifare Ultralight.

Как работать с запароленными ntag\ultralight см [[#Unlocking cards with passwords|тут]]

### MIFARE® DESFire

Для DESFire флиппер может эмулировать только UID

### Подорожник
Подорожник базируется на смарт-картах типа [MIFARE](https://ru.wikipedia.org/wiki/Mifare).
В качестве стандарта носителя Подорожника выбран **MIFARE Plus 4K**, работающий в режиме совместимости с MIFARE Classic.

Данный стандарт является усовершенствованной версией MIFARE Classic: алгоритм шифрования был изменён на AES, что позволило закрыть известные на момент выхода уязвимости. Первые MIFARE Plus появились в 2009 году и до конца 2015 года в публичном доступе не было информации о каких-либо уязвимостях в данных носителях.  
  
В октябре 2015 года вышла в свет работа "[Ciphertext-only Cryptanalysis on Hardened Mifare Classic Cards](http://www.cs.ru.nl/~rverdult/Ciphertext-only_Cryptanalysis_on_Hardened_Mifare_Classic_Cards-CCS_2015.pdf)", описывающая атаку на карты MIFARE, работающие в режиме совместимости с Mifare Classic. Именно работа Подорожника в режиме совместимости позволила получить дальнейший доступ к карте. 
  
Память MIFARE Plus 4K разбита на 40 секторов: первые 32 сектора содержат 64 байта информации, последние 8 — 256 байт, что в сумме и даёт 4096 байт, которые указаны в названии.  
  
Для доступа к каждому сектору используется два ключа, KeyA и KeyB — они никак не зависят друг от друга и применяются для чтения/записи соответственно.  
  
В апреле 2016 года на Github появился репозиторий [aczid/crypto1_bs](https://github.com/aczid/crypto1_bs), содержащий реализацию атаки описанную в научной статье. Я не буду подробно останавливаться на процессе компиляции и запуска скрипта, лишь скажу, что для атаки достаточно использовать любой libnfc-ридер, например, известный в узких кругах [ACR122U](https://vk.cc/6nmXi0).

Таким образом были получены ключи A и B от всех 40 секторов карты Подорожник.  

#### Анализ памяти карты
  
После получения ключей доступа к секторам, стало возможно чтение и запись любых данных на карту. После снятия первых дампов сразу бросилось в глаза, что большинство секторов (1-3, 6, 7, 13-39) забиты нулями и никак не используются: для чего в таком случае используется карта на 4 Кб (а не на 2, например) осталось загадкой. Более того, после нескольких поездок было обнаружено, что данные меняются только в секторах 4, 5 и 9. Так же сразу стало очевидно, что сектор 9 содержит в себе только данные о числе поездок за текущий месяц: значения в некоторых блоках памяти только инкрементируются и соответствуют этому показателю.  
  
Самое же интересное происходит в секторах 4 и 5 — вот их значения до и после одной из поездок:

![[podoroznik.png]]

Легко заметить, что первый и второй блоки в секторе 4 всегда совпадают, точно так же ведут себя блоки 2 и 3 в пятом секторе. Экспериментируя с различными балансами, валидаторами в метро и наземном транспорте и интервалами между поездками удалось выяснить следующее:  
  

- Первые 2 байта первого (или второго) блока четвёртого сектора хранят в себе информацию о балансе электронного кошелька карты в виде целочисленного числа, последние 2 разряда которого содержат информацию о копейках.
- Первые 4 байта первого блока пятого сектора хранят количество минут, прошедших с 1 января 2010 года. Таким образом, информация о последней поездке хранится на карте с точностью до минуты.
- Следом за минутами, два байта выделено для идентификатора валидатора: эти идентификаторы отличаются даже в пределах одной станции метро и получить одинаковое значение можно лишь пройдя через тот же турникет.
- Первый байт второго (или третьего) блока пятого сектора хранит в себе информацию о кол-ве поездок в текущем месяце, аналогично той, что записана в девятом секторе.

  
Кроме этого, в 5-м секторе находится [имитовставка](https://ru.wikipedia.org/wiki/%D0%98%D0%BC%D0%B8%D1%82%D0%BE%D0%B2%D1%81%D1%82%D0%B0%D0%B2%D0%BA%D0%B0): результат хеш-функции от каких-то хранящихся на данных карте. Возможное её расположение — последние 2 байта первого блока и, возможно, середина второго (третьего) блока. Имитовставка используется в качестве дополнительной защиты и не позволяет менять баланс (и любые другие критичные для оплаты данные) на произвольные значение, тем самым сильно уменьшая возможности для атаки. Тем не менее, имитовставка не является преградой, если речь идёт об атаке повторного воспроизведения.

#### Атака повторного воспроизведения

**Атака повторного воспроизведения (replay)** — атака на систему аутентификации путём записи и последующего воспроизведения ранее посланных корректных сообщений или их частей.  
Данный тип атаки можно применить как раз в этом случае: так как возможность генерировать имитовставку под нужные данные отсутствует (по причине неизвестного алгоритма её формирования), остаётся лишь вариант полного сохранения состояния карты после пополнения баланса и возврат к нему при необходимости.  
  
Тестирование атаки производилось по следующим схемам:  
  
1. Пополнение баланса, сохранение дампа, трата доступных средств, восстановление дампа и попытка пополнить баланс через автомат, результат — ==мгновенная блокировка карты.==
2. Пополнение баланса, сохранение дампа, трата доступных средств, восстановление дампа и последующий проход в метро, результат — ==успешный проход в метро, блокировка карты спустя 2 часа после прохода.==
3. Пополнение баланса, сохранение дампа, трата доступных средств, восстановление дампа и последующие поездки только в наземном транспорте, результат — ==никаких блокировок, удалось повторить несколько раз.== (*прим. потом наземный подключили онлайн и стали блокировать*)
4. Пополнение баланса, сохранение дампа, трата доступных средств, восстановление дампа, поездка в наземном транспорте, поездка в метро, результат — ==успешный проход в метро, блокировка карты спустя 2 часа после прохода.==

  
После блокировки карты в метро, её все ещё можно использовать в наземных видах транспорта довольно продолжительное время: внесённый в стоп-лист Подорожник работал ещё минимум 2 недели, после чего тестирование было прекращено.  
  
Таким образом, данная атака позволя~~ет~~ла бесплатно и без каких-либо ограничений пользоваться любыми наземными видами транспорта: карта Подорожник принимается к оплате в автобусах, троллейбусах, трамваях и маршрутных такси.  
  
С метрополитеном ситуация не такая: турникеты синхронизируются очень оперативно и любые попытки обойти защиту заканчиваются блокировкой карты в кратчайшие сроки. 

#### Мобильное приложение Plantain

![[plantainreader.png]]

Для ускорения процесса тестирования, было написано простое приложение, способное считывать информацию с Подорожника, а так же сохранять и восстанавливать его состояние.

В публичном поле доступно урезанное приложение Plantain Reader только для считывания.

Как бы то ни было, Flipper Zero тоже  позволяет проверить баланс карты. Остальные действия приведут к блокировке и в целом бессмысленны.

## NFC cards type V

### ICODE® SLIX

Flipper Zero может считывать и сохранять данные, хранящиеся на ICODE SLIX, SLIX-2, SLIX-L, and SLIX-S tags. В этих тегах память организована в виде блоков.

## NFC cards type F

### FeliCa™ Lite-S

Flipper Zero может считывать, сохранять и эмулировать карты FeliCa Lite-S.
В частности, он может считывать Manufacture ID (IDm), Manufacture parameter (PMm), and data in blocks.

*Прим.: если флиппер считал 26 из 28 блоков, считается что карта прочитана полностью. Особенности чтения*

## NFC cards type B
### ST25TB
- ST25TB512
- ST25TB512-AC    
- SRIX512    
- ST25TB02K    
- ST25TB04K    
- SRIX4K


## Банковские карты EMV (PayPass, Apple Pay)

EMV (Europay, Mastercard, and Visa) — международный набор стандартов банковских карт.

Банковские карты — это полноценные смарт-карты со сложными протоколами обмена данными, поддержкой ассиметричного шифрования. Помимо чтения UID, с банковской картой можно обменяться сложными данными, в том числе вытащить полный номер карты (16 цифр на лицевой стороне карты), срок действия карты, иногда имя владельца и даже историю последних покупок.  
  
Стандарт EMV имеет разные высокоуровневые реализации, поэтому данные, которые можно достать из карт могут отличаться. CVV (3 цифры на обороте карты) считать нельзя никогда.  
  
Банковские карты защищены от replay-атак, поэтому скопировать ее Флиппером, а затем эмулировать и оплатить покупку в магазине у вас не получится.

### Виртуальная карта ApplePay VS Физическая банковская карта

В сравнении с пластиковой банковской картой, виртуальная карта в телефоне выдает меньше информации и более безопасна для платежей оффлайн.  
  
Преимущества виртуальной карты Apple Pay, Google Pay:  
  

- **Не позволяет использовать перехваченные данные для оплаты в интернете** – обычная карта может быть использована для операций типа Card not present (CNP), то есть для оплаты в интернете, по телефону и т.д. Данные из виртуальной карты Apple Pay нельзя использовать подобным образом. Это связано с тем, что электронная карта при регистрации выпускает новую карту, операции по которой обязаны иметь криптографическую подпись. Считывание Apple Pay выдает PAN и expiration date новой выпущенной электронной карты, а не физической, регистрируемой. Поэтому, если указать перехваченные данные виртуальной карты для оплаты в интернете, платеж будет отклонен, так как эти транзакции требуют специальной подписи.
- **Не раскрывает данные владельца** — некоторые физические бесконтактные карты могут передавать имя владельца (Cardholder name) и историю последних покупок. Виртуальная карта так не делает.

  
  
> Поддержка банковских карт во Флиппере сделана исключительно для демонстрации работы высокоуровневых протоколов.

Всё что можно получить - номер карты и срок годности

### Как украсть деньги с бесконтактной карты и Apple Pay

никак, читаем статью:
https://habr.com/ru/articles/422551/

## MFKey32 attack

![[mfkey32.webp]]

Если вам не удалось прочитать все сектора карты MIFARE Classic®  или тех секторов, которые вы прочитали, недостаточно для получения доступа, попробуйте воспользоваться уязвимостями в картах MIFARE Classic NFC, чтобы получить доступ.

На этой странице вы узнаете, как проводить атаку MFKey32 как с физическим доступом к карте, так и без него, а также атаки только с использованием карты, для которых вам не нужен доступ к считывающему устройству для вычисления ключей.

Атака MFKey32 [использует слабые места](https://www.cs.bham.ac.uk/~garciaf/publications/Dismantling.Mifare.pdf) в алгоритме шифрования [Crypto-1](https://en.wikipedia.org/wiki/Crypto-1). MFKey32 - это название инструмента/алгоритма, используемого для восстановления ключей MIFARE Classic из [nonce](https://en.wikipedia.org/wiki/Cryptographic_nonce) Crypto-1 считывателя. Он работает путем восстановления исходного состояния [сдвигового регистра линейной обратной связи](https://en.wikipedia.org/wiki/Linear-feedback_shift_register) (Linear Feedback Shift Register) Crypto-1, который содержит ключ.


Лучший способ провести атаку MFKey32 - это получить доступ к карте, даже если были прочитаны не все сектора. Получив ключ считывателя, вы сможете считывать данные с большего количества секторов карты, чего может быть достаточно для получения доступа.


Чтобы получить ключи считывателя и прочитать данные с карты MIFARE Classic, выполните следующие действия:


1. Прочитайте и сохраните карту с помощью устройства Flipper Zero.
2. Перейдите в **Main Menu -> NFC -> Extract MF Keys**. Flipper Zero будет имитировать  карту для атаки MFKey32.

![[m.webp]]

3. Коснитесь считывателя Flipper Zero, как показано ниже. Находясь рядом со считывателем, ваш Flipper Zero будет собирать одноразовые данные считывателя. В зависимости от устройства, вам может потребоваться несколько раз приложить к считывателю Flipper Zero, пока не будут собраны все 10 из 10 одноразовых значений.

   На экране вашего устройства Flipper Zero количество собранных пар одноразовых значений должно увеличиваться с каждым новым считыванием. Если количество одноразовых пар не увеличивается, считывающее устройство не пытается аутентифицировать карту, эмулируемую вашим Flipper Zero.

![[mfkey32_3.webp]]


4. Нажмите `OK`, чтобы сохранить собранные пары nonce на карту памяти microSD. Как только необходимое количество пар nonce будет собрано, на экране отобразится сообщение о завершении. 

![[mfkey32noncepairscollected.webp]]

**Recover keys** from the collected nonces. You can do it via: **Flipper Mobile App**

1. On your phone, run [Flipper Mobile App](https://docs.flipperzero.one/mobile-app "Flipper Mobile App") and synchronize it with your Flipper Zero.
2. Go to **Tools -> Mfkey32 (Extract MF Keys)**.
   

**Flipper Lab**

1. Connect your Flipper Zero to your computer via a USB-C cable.
2. On your computer, go to [lab.flipper.net](https://lab.flipper.net/ "lab.flipper.net").
3. Go to **NFC tools**, then click the **GIVE ME THE KEYS** button.
   

**MFKey app**

https://lab.flipper.net/apps/mfkey

если у вас нет доступа к смартфону или компьютеру, вы можете восстановить ключи из собранных одноразовых данных, используя только свой Flipper Zero. Имейте в виду, что восстановление ключей занимает несколько минут из-за ограниченной вычислительной мощности устройства.


На своем Flipper Zero перейдите в Main Menu -> Apps -> NFC
Запустите приложение MFKey и нажмите кнопку OK.

Восстановленные ключи отобразятся на экране. После этого их можно будет добавить в словарь пользователя. В некоторых случаях ключи не могут быть восстановлены из одноразовых файлов из-за того, что считывающее устройство неправильно распознает эмуляцию Flipper Zero.


6. Как только в пользовательский словарь будут добавлены новые ключи, прочитайте карточку еще раз. Количество найденных ключей и прочитанных секторов может увеличиться, что указывает на сбор необходимых данных.


### Troubleshooting

Q: **I have zero keys, how do I find more?**

A: You can find more keys from the card reader (the same one you would normally tap your card against) using the Mfkey32 attack. Navigate to NFC -> Extract MF Keys and hold the Flipper Zero up to the reader. If the reader unlocks during this process, it is using the UID of the card and is highly insecure. Otherwise, it'll collect "nonces" from the reader. You can crack the nonces to find the reader keys by running MFKey following Extract MF Keys (navigate to Main Menu -> Applications -> NFC -> MFKey, press OK to run).

When the cracking process is complete, the number of new user keys (or candidate keys) that are found will be shown. If more than zero keys are found, return to step 1 of [**Reading the Card**](https://flipper.wiki/mifareclassic/#reading-the-card) and repeat the process.

Q: **When I read the card in the NFC app, it says "(Hard)" at the top, and when I use MFKey it errors with "No nonces found". How do I find new keys?**

A: You need to perform a Hardnested attack using the nonces your Flipper Zero saved when reading the card. You have two options:

- Follow the guide to run HardnestedRecovery [**here**](https://github.com/noproto/HardnestedRecovery#usage).
- Upload the .nested.log from your device (nfc/.nested.log on your SD card) to [**this website**](https://flipperzero.club/hardnested/) and copy any found keys back to your user dictionary (nfc/assets/mf_classic_dict_user.nfc on your SD card). You can also manually add new keys on the Flipper by navigating to Main Menu -> NFC -> Extra Actions -> MIFARE Classic Keys -> Add.

## Unlocking cards with passwords

![[nfc_pass.webp]]

Существуют карты NFC, данные на которых упорядочены по страницам, например карты MIFARE Ultralight® и NTAG®. Если вы не можете прочитать все страницы карты NFC с помощью функции чтения, возможно, карта защищена паролем. Чтобы разблокировать защищенную карту, вы можете ввести пароль вручную, сгенерировать пароль для разблокировки или извлечь пароль из считывателя.

```ad-warning
Этот метод может привести к блокировке карты
```

если у вас есть доступ к считывающему устройству и карте, попробуйте извлечь пароль из считывающего устройства, скопировав данные с записанной карты. Считывающее устройство может аутентифицировать карту с помощью пароля, который может быть записан и сохранен вашим устройством Flipper Zero. После этого вы сможете прочитать данные на оставшихся страницах карты. 


Чтобы узнать пароль и разблокировать карту, выполните следующие действия:

1. Считайте карту
2. Go to **Main Menu** **-> NFC -> Saved -> Card*****s name -> Unlock**.
3. Select **Unlock with Reader**, then tap the reader with your Flipper Zero.

![[ntag_pass.webp]]

4. When the password is captured, press **Continue**.

![[flipperzerounlocknfccardswithreader.webp]]

5. Read the card by holding the card near your Flipper Zero’s back.

![[ntag_pass3.webp]]

6. Once pages are unlocked, press **Save**.

![[successfulunlockofallpagesofnfccard.webp]]


7. Name the card, then press **Save**.

### Генерация пароля


Используя свой Flipper Zero, вы можете сгенерировать пароль для toys-to-life NFC technology and Xiaomi Air Purifier. Когда карта окажется рядом, Flipper Zero сгенерирует пароль на основе UID карты.


Чтобы сгенерировать пароль и разблокировать карту, выполните следующие действия:

1. **Main Menu** **-> NFC -> Extra Actions -> Unlock NTAG/Ultralight**
2. Select the card type, then hold the card near your Flipper Zero’s back.
3. Once pages are unlocked, press **Save**.
4. Name the card, then press **Save**.

### Ручной ввод пароля

1. Считайте карту.
2. Go to **Main Menu** **-> NFC -> Saved**.
3. Select the saved card.
4. Then go to **Unlock with Password** **-> Enter Password Manually**.
5. Enter the password in hexadecimal, then press **Save**.
6. To unlock the card with the entered password, hold the card near your Flipper Zero’s back.
7. Once pages are unlocked, press **Save**.
8. Name the card, then press **Save**.


## Запись NFC

Стандартные NFC-карты имеют уникальные идентификационные номера (UID), присвоенные производителем. Эти номера нельзя изменить.

Запись возможна только на специальные **NFC magic** or **UID rewritable**

Flipper Zero can write data to **Gen1**, **Gen2**, and **Gen4** magic cards, as well as **regular** **MIFARE Classic®** cards (without rewriting the UID).

**Gen1 magic cards** can be configured as the following card type:

- MIFARE Classic® 1K
    

**Gen2 magic cards** can be configured as the following card type:

- MIFARE Classic® 1K (Compatible Gen 2 card is required)
- MIFARE Classic® 4K (Compatible Gen 2 card is required)
  
**Gen4 (Ultimate) magic cards** can be configured as the following card types:

- Any MIFARE Classic®    
- MIFARE Ultralight® EV1    
- MIFARE Ultralight® EV2    
- NTAG® 203    
- NTAG® 213    
- NTAG® 215    
- NTAG® 216

Для записи воспользуйтесь **Main Menu** **-> Apps -> NFC -> NFC Magic**.

Check if you have a compatible Gen1, Gen2, or Gen4 magic card by using the **Check Magic Tag** option and holding the magic card near the back of your Flipper Zero. _or_ If you have a password-protected Gen4 card, go to **Gen4 Actions -> Auth with password** to enter the password manually. Then use the **Check Magic Tag** option.

## Создание NFC

С помощью Flipper Zero вы можете создавать различные NFC-карты, которые можно запрограммировать в качестве ключей в системах контроля доступа или записывать на них различные данные с помощью смартфона, такие как ссылки на ваш личный веб-сайт, резюме или визитную карточку. 
![[flipper_zero_emulate_nfc_business_card.mp4]]

Кроме отдельного приложения на Android можно воспользоваться сайтом https://nfc.flippertools.net/

---

# Infrared
Пульты от телевизоров, кондиционеров, музыкальных проигрывателей передают команды через ИК-порт. Инфракрасный порт во Flipper Zero позволяет рулить всеми ИК-устройствами: перехватывать сигналы пультов и сохранять их на SD-карту, брутфорсить неизвестные коды от бытовой техники и загружать свои коды пультов и новые протоколы.

## Как работает ИК-порт

  
Инфракрасное излучение — это невидимое для человека электромагнитное излучение с длиной волны от 0,7 до 1000 мкм. Бытовые пульты дистанционного управления используют ИК-сигнал для передачи данных и работают в диапазоне излучения 0,75..1,4 мкм. Микроконтроллер в пульте мигает инфракрасным светодиодом с определенной частотой — так цифровой сигнал становится ИК-сигналом.

![[ir.gif]]

Для приема сигнала используют фотоприемник, который преобразует ИК-излучение в импульсы напряжения — с ними уже можно работать как с цифровым сигналом. Обычно в приемниках установлен темный фотофильтр, пропускающий излучение с нужной длиной волны, чтобы фильтровать помехи.  
  

## Как устроен ИК-порт во Flipper Zero

  
У ИК-порта Flipper Zero стоит специальное темное окошко — оно блокирует помехи от видимого света и пропускает ИК-излучение от пультов. Это помогает выделять полезный ИК-сигнал и убирать засветы видимого света. Именно этот фильтр мы привыкли видеть во всех ИК-портах. За ним уже расположены элементы приемника и передатчика. Flipper Zero может быть как приемником, так и передатчиком ИК-сигнала.

![[flipper_IR_explosion_animation_unc.mp4]]

Сразу за окошком ИК-порта расположена печатная плата. На ней с двух сторон расположено 3 ИК-светодиода — это передатчики сигнала. Их специально 3, чтобы увеличить мощность передачи. На нижней стороне печатной платы расположен фотоприемник TSOP, с помощью которого принимается ИК-сигнал. На выход TSOP выдает цифровой сигнал, который обрабатывается микроконтроллером STM32.

Так как декодинг инфракрасного сигнала происходит программно, потенциально Флиппер поддерживает прием и передачу любых кодов ИК-пультов. В том числе, неизвестных ему протоколов, которые не удалось распознать — в этом случае используется запись и воспроизведение сырого сигнала, без расшифровки.

Для чтения ИК-сигнала нужно перейти в меню `Infrared -> Learn new remote`, откуда его можно сохранить как новый пульт. К одному пульту можно добавить несколько сигналов, выбрав нужный пульт в меню `Infrared -> Saved remotes`. В одном пульте может быть неограниченное число сигналов (кнопок).

![[tv_switched_off_dictionary_attack_padding_compressed.mp4]]

Flipper Zero можно использовать как универсальный пульт для управления любым телевизором, кондиционером или медиацентром. В этом режиме Флиппер перебирает сигналы всех известных ему кодов всех производителей по словарю, лежащему на SD-карте. Когда пользователь решает выключить телевизор, висящий в ресторане, ему не нужно искать пульт именно от этой модели телевизора. Достаточно нажать кнопку выключения в режиме универсального пульта, и Флиппер будет последовательно посылать команды выключения от всех телевизоров, которые он знает: Sony, Samsung, Panasonic… и так далее. Когда телевизор услышит свой сигнал, он отреагирует и выключится.  
  
Такой перебор занимает время. Чем больше словарь, тем больше потребуется ждать, пока закончится перебор всех сигналов. Узнать, какой именно сигнал распознал телевизор, нельзя, так как у телевизора нет обратной связи.

![[tv-signals-bruteforce-dictionary.gif]]

Чтобы воспользоваться режимом универсального пульта, нужно перейти в меню `Infrared -> Universal library` и выбрать тип устройства, которым нужно управлять.

## Что не так с кондиционерами
Пульты от кондиционеров представляют собой полноценные устройства с экранчиком, и, при управлении кондиционером, мы смотрим не на кондиционер, а на экран пульта. Там устанавливается температура, мощность вентилятора и т.д. При этом, сам пульт не знает, услышал ли его сигнал кондиционер, он просто посылает сигнал каждый раз при изменении настроек на пульте.  
  
Но что произойдет, если мы уйдет в другую комнату с пультом от кондиционера, изменим настройки температуры на пульте, но кондиционер не услышит сигнал в момент нажатия на пульт? Допустим на кондиционере сохранилось значение 19°C, мы ушли в другую комнату и полностью поменяли все настройки на пульте, поставили 30°C. Потом подошли к кондиционеру снова и нажали кнопку на пульте, поднимающую температуру на 1°C вверх. Если бы пульт просто посылал нажатие каждой кнопки, как это делают другие пульты, на кондиционере бы установилась температура 20°C, а на экране пульта мы бы увидели 31°C. Получилась бы рассинхронизация данных на пульте и в памяти кондиционера.

Поэтому пульты от кондиционеров, в отличие от остальной техники, передают не команду нажатой кнопки, а сразу целиком все параметры кондиционера, которые видны на экранчике пульта. То есть всегда шлют ВСЕ данные отображаемые на экране пульта в одном большом пакете.  
  
Такие протоколы намного более сложные, так как требуют описания всего пакета данных целиком, а не только одной команды, как в случае с телевизорами.

Для разных кондиционеров данные с пульта могут быть совершенно различными. Помимо отличий в хранении данных, существуют модели с разными уровнями мощностей, контролем влажности, зональностью и прочим. Из-за этого посылаемые данные иногда имеют большой размер и могут передаваться за несколько посылок.

## Чтение ик
**Main Menu** **-> Infrared -> Learn New Remote**.

## Универсальный пульт
Flipper Zero позволяет управлять различными устройствами, не копируя их оригинальные инфракрасные (ИК) пульты дистанционного управления. С помощью функции универсальных пультов дистанционного управления вы можете использовать свой Flipper Zero в качестве универсального ИК-пульта дистанционного управления для отправки команд на телевизоры, звуковые системы, проекторы и кондиционеры. Эта функция отправляет команды из встроенного словаря протоколов дистанционного управления. 

**Main Menu -> Infrared -> Universal Remotes**.

### TV remote
Универсальный пульт дистанционного управления телевизором позволяет управлять питанием, устанавливать громкость звука, переключать каналы и отключать звук телевизора.

![[tvremote.webp]]

### Audio system remote

![[audioremote.webp]]

### Projector remote

![[projector_remote.webp]]

### Air conditioner remote

Универсальный пульт дистанционного управления кондиционером позволяет управлять питанием, активировать режим осушения воздуха и устанавливать температуру в режимах охлаждения или обогрева. Кнопка выключения только выключает  кондиционер. Чтобы включить кондиционер, нажмите любую другую кнопку на универсальном пульте дистанционного управления.

![[condei_remote.webp]]


## Пульты из мобильного приложения
**Main Menu -> Tools -> Remotes Library**.

Функция библиотеки пультов дистанционного управления в мобильном приложении Flipper поможет вам найти нужные ИК-сигналы для вашего устройства из базы данных. После выбора сигнал загружается на ваш Flipper Zero и может воспроизводиться через мобильное приложение или непосредственно с Flipper Zero.

![[remotes_lib.webp]]


## Ссылки
- [Flipper-IRDB](https://github.com/Lucaslhm/Flipper-IRDB): Community driven database of Flipper Zero formatted infrared files that anyone can contribute to.
- Внешний [[#ИК-модуль TV Buster 6.3 Вт]]

# Bluetooth
## BLE Spam

При использовании BLE Spam с выбором определённой опции Flipper Zero начинает транслировать соответствующие пакеты Bluetooth для всплывающих подсказок о подключении и уведомлений на различные устройства на iOS, Android, Windows в радиусе своего действия.

Устройства на ОС Android 14 и Windows 11 по умолчанию отображают уведомления о запросах на подключение по Bluetooth, поэтому постоянные отправки пакетов через Flipper Zero могут вызвать проблемы у пользователей.

![[ble_spam.jpeg]]

Apple в обновлении iOS 17.2 [закрыла](https://9to5mac.com/2023/12/15/the-jig-is-up-flipper-zero-devices-can-no-longer-crash-iphones-running-ios-17-2/) уязвимость, которая позволяла блокировать работу iPhone по Bluetooth с помощью Flipper Zero.

После установки iOS 17.2 при попытке проведения DoS-атаки («отказ в обслуживании») на iPhone с бесконечным числом оповещений по Bluetooth на смартфоне будет отображаться только несколько попыток подключения внешних устройств, которые можно игнорировать. Также в этом случае доступны другие функции мобильного устройства, а не происходит его блокировка сторонними уведомлениями.


### SEX TOYS

Разработчики Маттео Мандолини и Лука Бонджиорни [рассказали](https://www.whid.ninja/blog/denial-of-pleasure-attacking-unusual-ble-targets-with-a-flipper-zero) о том, как им удалось взломать и перехватить управление Bluetooth-гаджетами. Внимание исследователей привлекли игрушки для взрослых, работающие через приложение [Love Spouse](https://apps.apple.com/us/app/love-spouse/id1565293484).

На первом этапе реализации проекта разработчикам надо было получить команды, которые передаются по Bluetooth со смартфона на устройство. Для этого использовали приложение nRF Connect, доступное на Android и iOS. С его помощью получилось перехватить сигнал и изучить его содержимое. Для активации различных режимов на игрушке для взрослых со смартфона передаются разные команды, которые могут отличаться в зависимости от моделей. Поэтому авторы решили реализовать функцию отключения всех устройств в радиусе действия Flipper Zero.

Сперва им пришлось модифицировать прошивку Flipper Zero, изменив Bluetooth API. Это потребовалось для более удобной работы с протоколом беспроводной передачи данных. В итоге у разработчиков получилось полноценное приложение для взаимодействия с целым классом игрушек для взрослых.

![[Attacking BLE Adult Toys.mp4]]



# GPIO & modules

![[gpio.webp]]


Вы можете использовать Flipper Zero для исследования оборудования, перепрошивки встроенного ПО, отладки и фаззинга. Flipper Zero можно подключить к оборудованию с помощью встроенных контактов GPIO, управлять оборудованием с помощью кнопок, запускать код и отображать сообщения об отладке на экране. Flipper Zero также можно использовать в качестве преобразователя USB в UART / SPI / I2C.

## GPIO pinout

Flipper Zero имеет 18 контактов на верхней стороне, состоящих из контактов источника питания и контактов ввода-вывода. Контакты источника питания можно использовать для питания внешних модулей. Контакты ввода-вывода (I/O) допускают напряжение на входе и выходе +3,3 В. 

Контакты ввода-вывода подключают внешние модули к контактам ввода-вывода микроконтроллера STM32WB55 с помощью резисторов сопротивлением 51 Ом. Все контакты защищены от электростатического разряда (ESD). 

![[pinout.webp]]

![[flipperzeropinout.webp]]

**В режиме DFU пины меняют свое состояние:**

![[dfu_pinout.webp]]
![[dfu_pinout2.webp]]
![[dfu_pinout3.webp]]
![[dfu_pinout4.webp]]

### +3.3 V power (pin 9)
- По умолчанию включен.
- Максимальная нагрузка составляет 1,2 А.
- На карту microSD Flipper Zero подается напряжение +3,3 В. Во время обновления встроенного ПО и установки карты microSD подача питания на контакт 9 временно отключается.

### +5 V power (pin 1)
Pin 1 запитан от встроенного аккумулятора или напрямую от usb если подключен кабель
- По умолчанию отключен. Чтобы включить:  **Main Menu**,  **GPIO**. -> **5V on GPIO** -> **ON**.
- The maximum load is 1.2 A.

### Input/output pins

Общее энергопотребление контактов ввода-вывода не должно превышать 5 Вт. В противном случае аккумулятор может перейти в режим защиты, и устройство Flipper Zero может отключиться. Каждый контакт может подавать до 20 мА.

### 3.3 V and 5 V tolerance
Интерфейс ввода-вывода современных CMOS-микросхем рассчитан на работу в определенном диапазоне напряжений. В случае микроконтроллера Flipper Zero STM32WB55 интерфейс ввода-вывода рассчитан на работу с напряжением 3,3 В.

![[5v_tolerance.png]]

## GPIO menu
![[gpio_menu.webp]]

- **USB-UART Bridge:** Flipper Zero acts as a USB to Serial UART converter.
    
- **GPIO Manual Control:** test output of individual or all GPIO pins by pressing **OK**. Available configuring options: PA7 (pin 2), PA6 (pin 3), PA4 (pin 4), PB3 (pin 5), PB2 (pin 6), PC3 (pin 7), PC1 (pin 15), PC0 (pin 16), and ALL.
    
- **5V on GPIO:** enable/disable +5 V power supply to pin 1. See [this section](https://docs.flipperzero.one/gpio-and-modules#brgPY "this section") for more information.





## Взлом светофоров

 Канадский инженер Питер Фэрли с помощью светодиодной ИК-матрицы и штатной опции «генератор сигналов» в Flipper Zero создал дешёвый MIRT-передатчик для включения зелёного сигнала на светофорах.

![[svetofor.jpeg]]

Исследователь подключил б/у светодиодную ИК-матрицу от старой видеокамеры к элементу питания через оптопару 4N33 и транзистор Дарлингтона и завел на вход этой схемы внешний кабель от интерфейса GPIO генератора сигналов от Flipper Zero, настроенного на частоту 14 Гц. В итоге получился мобильный инфракрасный передатчик с возможностью включения зелёного сигнала светофоров, как это делают спецслужбы во многих странах мира (там обычно используется сигнал на 10 Гц, 12 Гц или 14 Гц).

Инженер проверил, что устройство действительно работает со светофорами в его городе. Управляющая электроника транспортной службы правильно принимает ИК-сигнал и переключает на зелёный нужные светофоры на перекрёстках при правильном направлении ИК-матрицы на приёмники на столбах.

![[svetofor2.jpeg]]

![[svetofor3.jpeg]]

![[Opticom Infrared System for Emergency Vehicle Preemption.mp4]]

![[Flipper Zero Controlling Traffic Lights.mp4]]

## Модуль W5500

С помощью специального модуля, можно проверить интернет кабель на наличие подключения к локальной компьютерной сети или к интернету, а так же получить IP адрес по DHCP и измерить ping.

**понадобится**:

- Макетная плата (можно купить на официальном сайте - [ссылка](https://shop.flipperzero.one/products/proto-boards).    
- Китайский дешевый модуль W5500. Подойдёт версия lite с питанием 3.3v или обычная 5v [ozon](https://www.ozon.ru/category/elektronika-15500/?category_was_predicted=true&deny_category_prediction=true&from_global=true&text=W5500).    
- Паяльник, припой, соединительные провода.

**сборка**

1. Впаиваем гребенки разъёма из комплекта макетных плат в макетную плату.    
2. Устанавливаем модуль W5500 в плату и припаиваем его контакты. Важно учитывать, что бы контакты модуля не замыкались между собой. В данном случае модуль версии lite может отлично расположиться по центру платы. После припайки укорачиваем кусачками ножки модуля.    
3. Разводим и припаиваем проводки от гребёнок к контактам модуля следуя схеме.

![[w5500_0.jpg]]

![[w5500_1.jpg]]

Нам необходимо установить приложение на флиппер [[#[W5500] Ethernet]]

очень важно собранный нами модуль подключать ДО запуска приложения.

Итак. Подключаем модуль к флипперу, должен загореться светодиод питания.

![[w5500_2.jpg]]

Переходим в меню Apps выбираем папку GPIO.

Запускаем приложение [[#[W5500] Ethernet]] и жмем `[init]`.

Мы должны увидеть успешный запуск и инициализацию.

![[w5500_3.jpg]]

Если инициализация модуля не прошла, а появилась та или иная ошибка, вам нужно:

1. Проверить корректность соединения по схеме и их пайку.    
2. Проверить модуль, он может быть поврежден при транспортировке или иметь брак с завода.
    

Если инициализация модуля прошла успешно, продолжаем тестирование. Аккуратно подключаем ethernet кабель с коннектором RJ45 в разъем модуля, замигает зеленый и оранжевый светодиоды расположенные непосредственно на разъеме, дожидаемся постоянного свечения зелёного светодиода.

Нажимаем `[dhcp]` или `[static]` - (предварительно настроив статический IP адрес в приложении нажав вправо в меню static) и тем самым получаем IP адрес в сети.

![[w5500_4.jpg]]

Если адрес получен, жмём `ping` и наблюдаем результат. Кабель цел, доступ к сети имеется.

![[w5500_5.jpg]]



##  Радиомодуль 2.4 ГГц NRF24L01 Mouse Hunter

NRF24L01 используется для исследования беспроводных устройств, таких как беспроводные мыши и клавиатуры. Совместим с приложениями "NRF24 Sniffer", "NRF24 Mouse Jacker", "NRF24 Channel scaner" и другими приложениями Flipper Zero, использующие чип NRF24L01 


### Купить

Данное исполнение содержит усилитель принимаемого и отправляемого сигнала. Максимальная мощность - 500 мВт - самая большая на рынке РФ. На плате уже распаяны стабилизатор и фильтр питания. Это обеспечивает стабильную работу капризного чипа в любых условиях
https://flipper.market/product-gkkzlxf

### Сделай сам (pinout)

![[nrf24l01.png]]

![[nrf24l012.png]]


## Official Wi-Fi Development Board.

The developer board with Wi-Fi connectivity made specially for Flipper Zero. Based on the [ESP32-S2 module](https://www.espressif.com/en/products/socs/esp32-s2), this devboard allows:

- Wireless Flipper Zero firmware update
- Advanced in-circuit debugging via USB or Wi-Fi using the [Black Magic Probe](https://github.com/blacksphere/blackmagic) open source project

As a bonus, ESP32-S2 allows Wi-Fi penetration testing (PMKID capturing, deauth, and more) and connects Flipper Zero to the Internet. These functions are not supplied with the module and must be implemented additionally.

### Where to buy?

- [https://shop.flipperzero.one/products/wifi-devboard](https://shop.flipperzero.one/products/wifi-devboard)

### Official Purpose Of The Wi-Fi Development Board

The official Wi-Fi development board sold by Flipper Devices is geared primarily for debugging firmware and application for the Flipper Zero. Due to this, it arrives pre-flashed with the [BlackMagic](https://github.com/flipperdevices/blackmagic-esp32-s2) firmware to enable both wired and wireless debugging.

Documentation for how to begin debugging with the board can be found in the [official flipper zero documentation](https://developer.flipper.net/flipperzero/doxygen/dev_board_get_started.html).

### Community Uses For The Board

If one does not desire to do development with the board or wants to try a different use for the board, it is possible to flash the Wi-Fi board with alternate firmware to try new functions.

The following is a partial list of a few popular community firmware that one may use for the board that also have companion apps for the Flipper Zero:

- [Marauder](https://github.com/justcallmekoko/ESP32Marauder/wiki/flipper-zero), an offensive security testing platform for ESP32 based devices, featuring both Wi-Fi tools and Bluetooth tools for hardware supporting bluetooth.
- [FlipperHTTP](https://github.com/jblanked/FlipperHTTP), a multi-purpose firmware that uses HTTP requests to retrieve information from websites, download applications from the catalog, connect with users on social media platforms, and extract data from APIs.
- [GhostESP](https://github.com/Spooks4576/Ghost_ESP), a firmware that provides tools to perform comprehensive Wi-Fi and Bluetooth Low Energy (BLE) analysis, execute targeted wireless tests, and explore dynamic wireless environments.

### Useful Links

- [FZEE flasher](https://fzeeflasher.com/), an easy web based ESP flasher for installing popular firmware with only a few clicks.
- [EspWebTool](https://esp.huhn.me/), a more manual and general purpose web flasher tool for all ESP32 devices, requires having pre-built firmware binaries.
- [Ghost ESP Flasher](https://flasher.spookytools.com/), Online flasher for flashing GhostESP to supported ESP32 devices.


## External Radio Module for 433 MHz aka CC1101

У Flipper Zero есть встроенный модуль для работы в диапазоне до 1 ГГц (поэтому и Sub-GHz) на основе приемопередатчика CC1101 и встроенной антенны. Встроенный CC1101 и антенна рассчитаны на работу в диапазонах частот 300-348 МГц, 387-464 МГц и 779-928 МГц. Но, как мы знаем, чем более универсален инструмент, тем меньше он подходит под решение конкретной задачи. Так получилось и тут – команда Flipper Devices Inc. провела огромную работу, чтобы покрыть весь УКВ диапазон частот с помощью одной антенны. Но, если вы хотите работать именно на ±433MHz, то вам нужна другая антенна, настроенная на эту конкретную частоту. На наш взгляд, это будет значительно эффективнее, ведь на ±433MHz у встроенной антенны самые компромиссные показатели.

![[subghz_antenna.png]]
*Визуальное сравнение внутренней антенны и от внешнего модуля

Замеры внутренней антенны флиппера показывают что средняя дистанция приёма-передачи составляет около 6-15 метров при указанной мощности.

### CC1101 с внешней антенной, а на самом деле E07-M1101D-SMA

> Важно отметить, что внешний модуль почему‑то все называют CC1101 ака «ЦЦшка», хотя это только название микросхемы (IC, Integrated circuit), которая стоит внутри флиппера и на которой основаны оба модуля (если хотите — сборки) E07-M1101D‑SMA и E07–433M20S. И сейчас вам начинает казаться, «а зачем мне про это душнят», да? А затем, что дальше будет инфа про другой внешний модуль с усилителем, который все называют E07, но он носит официальную маркировку E07–433M20S. И важно не запутаться, что такое E07, а что CC1101. Но вроде все договорились называть простой модуль без усилителя — CC1101, а с усилителем сигнала — E07:) А пока писали статью, появился ещё модуль E07–400MM10S, который до нас уже назвали E07–400 ¯_(ツ)_/¯_

Если внимательно посмотреть на модуль и плату-переходник, которая идёт в составе, (ведь реверс-инжиниринг никто нам не запрещал), то по рассыпухе можно увидеть, что важная часть модуля – это понижайка до напряжения 3,3В. В мануале к микросхеме E07-M1101D-SMA указано, что работает она именно от этого напряжения, а также, что преобразователь – линейный, что благотворно сказывается на уровне шумов при приёме.

При сравнении показателей мощности встроенного и внешнего радиомодуля видим хороший прирост:

|   |   |   |   |   |
|---|---|---|---|---|
|**AMP**|**TR(dBV)**|**POW(mW)**|**Dist aprox (m)**|**Dist cub_root aprox (m)**|
|Flipper Zero internal module & antenna|-49|0,05188358724|4,58397784|9,815200545|
|**E07-M1101D-SMA**|**-29,5**|**4,62412958**|**43,27554136**|**43,84289037**|

При условии, что микруха тут тот же, что и внутри флиппера, то влияет на такое увеличение правильно отстроенная антенна и согласованный тракт именно под ±433 MHz.



### Купить готовый

Это проще, чем собрать самому, но стоит шекелей. Если их есть у вас, то чекайте ссылки:

- Модули на базе CC1101 на маркетплейсе [Flipper Addons](https://flipperaddons.com/product-tag/cc1101/) от разных вендоров в коротком длинном и даже прозрачном форм-факторе, а также в виде плат-переходников для самостоятельной сборки
    
- Модуль CC1101 на [Flipper.Market](https://flipper.market/product-vidogmr)

### Сделать самому

Вы можете сами собрать этот модуль, как и любой другой, если у вас есть паяльник, рассыпуха, и, собственно, сам CC1101 модуль. Итак, вам понадобится:

- Внешний CC1101 с внешней SMA антенной. Все в основном пользуются таким вот модулем, на базе [Ebyte 10dBm 530m CC1101 Rf 433MHz Fsk](https://www.ru-ebyte.com/products/E07-M1101D-SMA)
    
- Рассыпуха в виде AMS1117-3.3
    
- Макетная плата и некоторое количество соединительного  провода, например можно использовать МГТФ.
    

Чтобы собрать модуль на базе Ebyte-CC1101, руководствуйтесь распиновкой с  изображения

![[Ebyte-CC1101-impr.png]]


Или обойтись без AMS1117-3.3, подключившись на 3.3в

### Еще вариант на базе СС1101 в исполнении с E07-400MM10S 

Еще под руку попался интересный модуль на базе E07-400MM10S, которая тоже работает на базе СС1101, как вы уже поняли.

![[E07-400MM10S.png]]

Провели его замеры и получили, что он чуть лучше работает, чем предыдущий модуль.

|   |   |   |   |   |
|---|---|---|---|---|
|**AMP**|**TR(dBV)**|**POW(mW)**|**Dist aprox (m)**|**Dist cub_root aprox (m)**|
|Flipper Zero internal module & antenna|-49|0,05188358724|4,58397784|9,815200545|
|E07-M1101D-SMA|-29,5|4,62412958|43,27554136|43,84289037|
|**E07-400MM10S**|**-25,17**|**12,53227729**|**71,24305092**|**61,12691962**|

Все модули, о которых мы говорили, работают на той же CC1101, что и во флиппере, без всякого усиления. Но благодаря настроенному на 433 MHz тракту, и, возможно, экранированию, более эффективны и "дальнобойны" (на 315 и 866 будет хуже, чем встроенный)

### А можно еще дальше? Или сказ про усиление на базе E07-433M20S

Люди так устроены, что им хочется больше силы, власти, и, конечно же, им мало просто настроенного на 433 MHz тракта и отстроенной антенны.

![[07-433M20S.png]]


Вот так и появился модуль для Flipper Zero на базе [модуля E07-433M20S](https://ebyteiot.com/products/ebyte-e07-433m20s-cc1101-433mhz-20dbm-wireless-transceiver-module-smart-home-spi-interface-power-amplifier-rf-receiver-module). В нём также используется CC1101, но есть еще и встроенный усилитель сигнала, который позволяет передавать сигнал с флипаря еще дальше.

|   |   |   |   |   |
|---|---|---|---|---|
|**AMP**|**TR(dBV)**|**POW(mW)**|**Dist aprox (m)**|**Dist cub_root aprox (m)**|
|Flipper Zero internal module & antenna|-49|0,05188358724|15,27992613|15,18604175|
|E07-M1101D-SMA|-29,5|4,62412958|43,27554136|43,84289037|
|E07-400MM10S|-25,17|12,53227729|71,24305092|61,12691962|
|**E07-433M20S Amp OFF**|**-29,17**|**4,989189454**|**44,95132622**|**44,96754496**|
|**E07-433M20S Amp ON**|**-18,64**|**56,36765863**|**151,0923616**|**100,9018613**|

Вы можете задаться вопросом, почему в этой таблице есть две строчки относительно e07, одна из которых очень сильно повторяет показатели обычного внешнего модуля. На самом деле, все просто – усилитель может работать, а может и не работать. А если он не работает, то по факту у вас в руках просто модуль CC1101 с внешней антенной.

И да, на данный момент официальная прошивка не поддерживает работу усилителя “из коробки” и нужно использовать альтернативную прошивку, где эта поддержка реализована. Если вы будете использовать этот модуль на официальной прошивке, то он просто будет работать как модуль из блока выше.

Приобрести же этот готовый модуль можно [тут](https://flipperaddons.com/product-tag/e07-433/). А вот схем по самостоятельной сборке с пинаутом и рассыпухой мы не нашли в свободном доступе.

### “Only a Sith deals in absolutes” или “Надо больше усиления”

Естественно, на E07-433M20S все не закончилось, ведь есть и другие усилители сигнала, которые попались нам под руку, а именно:

- 50M-6GHz Low Noise Amplifier LNA RF Power Amplifier Gain 20dB Powered By USB OpenSourceSDR Lab
    
- 20dB 50MHz to 6000MHz UHF 2.4G Broadband Low Noise Amplifier RF LNA Amp Module VHF HF
    

Что важно тут отметить – так это то, что эти усилители уже требуют внешнего питания, а не тянут 5v с флиппера, как это делает E07-433M20S.

Первый подопытный у нас LNA усилитель от компании Open Source SDR Lab.

![[LNA_RF_PowerAmplifier.png]]

Мы запитали его от банки, ибо на борту имеется порт micro-usb, что кажется оч удобным (и банка не шумит, проверили тоже). Небольшой минус в том, что придется носить с собой не только флиппер, но и банку)) Значит, понадобится рюкзак или сумка.

Измерив его работу в аналогичных условиях, что и для предыдущих подопытных, получили уже данные немного интереснее. Как видите – расчётная дальность увеличилась почти ни на сколько, по сравнению с E07. Да и наврали китайцы про 20 dB усиления.

|   |   |   |   |   |
|---|---|---|---|---|
|**AMP**|**TR(dBV)**|**POW(mW)**|**Dist aprox (m)**|**Dist cub_root aprox (m)**|
|Flipper Zero internal module & antenna|-49|0,05188358724|4,58397784|9,815200545|
|E07-M1101D-SMA|-29,5|4,62412958|43,27554136|43,84289037|
|E07-400MM10S|-25,17|12,53227729|71,24305092|61,12691962|
|E07-433M20S Amp OFF|-29,17|4,989189454|44,95132622|44,96754496|
|E07-433M20S Amp ON|-18,64|56,36765863|151,0923616|100,9018613|
|**OSDRL Amp**|**-19**|**51,88358724**|**144,9581072**|**98,15200545**|

А что если взять еще более “мощный” на вид LNA усилитель, у которого тоже 20dB, как и у предыдущего, но запитать его не от банки, а от 12v? Именно так мы и сделали, взяв в руки еще один усилитель сигнала.

![[LNA_RF_PowerAmplifier2.png]]


|   |   |   |   |   |
|---|---|---|---|---|
|**AMP**|**TR(dBV)**|**POW(mW)**|**Dist aprox (m)**|**Dist cub_root aprox (m)**|
|Flipper Zero internal module & antenna|-49|0,05188358724|4,58397784|9,815200545|
|E07-M1101D-SMA|-29,5|4,62412958|43,27554136|43,84289037|
|E07-400MM10S|-25,17|12,53227729|71,24305092|61,12691962|
|E07-433M20S Amp OFF|-29,17|4,989189454|44,95132622|44,96754496|
|E07-433M20S Amp ON|-18,64|56,36765863|151,0923616|100,9018613|
|OSDRL Amp|-19|51,88358724|144,9581072|98,15200545|
|**Chi Amp**|**-19**|**51,88358724**|**144,9581072**|**98,15200545**|

И получили такие же показатели, как у прошлого ¯_(ツ)/¯.

На этом мы остановились и цеплять большие  промышленные усилители не стали. И так с усилителями мощность получилась больше разрешенных 10 милливатт (это если у вас нет радиолюбительской категории и позывного, а у нас есть, так что усилки нам можно :)

### А что с приемом сигналов?

Хорошо, а как быть с приемом сигнала? А то только про передачу говорим, которая от нескольких метров выросла в разы.

Усилитель может работать и для принимаемого сигнала, но есть нюанс. Усиливает не только входной сигнал, но и помехи, ещё и добавляя свои шумы. Поэтому для уверенного приёма  без хорошей направленной антенны и приёмника с большим динамическим диапазоном, коим СС1101 не является, не обойтись. 

И тут сказать можно тезисно тоже кратко

- Модуль с настроенной внешней антенной принимает лучше встроенной антенны Flipper Zero 
    
- Усилители, в случае с флиппером, не сильно помогут вам (но немного помогут) ибо не дают хорошего прироста в дальности приема, о котором все мечтают Кроме того, сильно усложняют модульную конструкцию до монструозной.
    
- Хорошая приёмная антенна даст намного больше пользы, чем усилитель на приёме*
    
- А хорошая направленная антенна ещё лучше, и при передаче, и при приёме*

## External Radio Module for 900 MHz

- [Rabbit-Labs™ CC1101 900Mhz Module](https://www.tindie.com/products/tehrabbitt/rabbit-labs-cc1101-900mhz-module/)
- [CC1101 shielded module for 900Mhz by ruckus // section80 in Australia](https://www.tindie.com/products/ruckus/cc1101-shielded-module/)

### What is the purpose of this board?

This is a custom-made 900 Mhz module designed around a similar form factor to the existing CC1101 modules available on amazon and aliexpress.

### But... WHY?

The only CC1101 readily available is the 433Mhz CC1101 module. While this module is able to operate on higher frequencies > 600Mhz, it does not perform as well at these frequencies in comparison to the 433Mhz it was designed for. Because of this, I built this module to be used at higher frequencies such as 868-900Mhz as it uses a radio tuned to handle this upper-frequency range while also being compatible with 315/433Mhz (just not as strong as 900Mhz)

### What makes it special?

This is the only high-frequency module fully pin-compatible with the MAYHEM Board and other CC1101 MiniBoards, Multiboards, and full-height boards on the market. The module is plug-and-play with your existing boards and follows the same pinout as the EByte 433Mhz CC1101 module that has become the go-to in the community. This board also has decoupling capacitors as close to the radio itself and RF Shielding around the actual RF circuitry to limit noise.

### PINOUT

- `GND` - Flipper Pin 11
- `3v3` - Flipper Pin 9
- `GD0` - Flipper Pin 6
- `CS` - Flipper Pin 4
- `SCK` - Flipper Pin 5
- `MOSI` - Flipper Pin 2
- `MISO` - Flipper Pin 3
- `UNUSED` - N/A

## GPS Module

- [TinyGPS](https://www.tindie.com/products/sce/flipper-zero-tinygps/)

Equipped with a high-precision Telit GPS module, the Tiny GPS board offers accurate location data for your applications. Its compact design makes it ideal for embedded systems and projects where space is limited.

If you already own a Flux Capacitor from Rabbit Labs USA, then this board is the perfect choice for you! It conveniently fits alongside the Flipper Zero, creating a fantastic combo for your Flipper Zero.

To unlock the full potential of this board, make sure to use the [Xtreme firmware](https://awesome-flipper.com/firmware/xtreme/), which has been specifically optimized to leverage its unique capabilities. With this firmware, you can harness the complete capabilities of the Tiny GPS board, enabling precise GPS positioning and Subdriving.

**Subdriving** is a novel feature within the [Xtreme Firmware](https://awesome-flipper.com/firmware/xtreme/), which functions similarly to wardriving, but it's tailored for Sub-GHz signals. This innovative feature allows you to explore and interact with Sub-GHz wireless signals, opening up a world of possibilities!

Once you've successfully installed the firmware, navigate to the Xtreme app. Open the Protocols section, scroll down to GPIO pins, and set the UART NMEA Channel to 15,16. This configuration is important otherwise it will not work!

The default baudrate is 9600! Time To First Fix (TTFF) takes about 30 seconds, keep your Flipper next to an open window or outside.

To use the Tiny GPS board on other firmware, please use [this GPS NMEA app](https://github.com/Sil333033/flipperzero-gps-lpuart)

## Flipper Zero Magspoof Module

- [Flipper Zero Magspoof Module by Astrowave Electronics in United States of America](https://www.tindie.com/products/astrowave/flipper-zero-magspoof-module/)
- [Flipper Zero Add-On: MagSpoof](https://electroniccats.com/store/flipper-add-on-magspoof/)

PLEASE NOTE: THIS DEVICE DOES NOT READ MAGSTRIPES, IT ONLY EMULATES THEM

![[magspoof.jpg]]


### ... What? What the heck is a magspoof?

Well... you know when you swipe your card at the store? That's a magnetic stripe card, aka magstripe. The black stripe (usually.. sometimes it's another color) on the back of the card has some magnetically encoded information- when you swipe your card, the reader picks up this information. There's probably some more detailed information on what my board here is doing[1](https://awesome-flipper.com/extra/module/magspoof/#fn:samy-magspoof), but it basically transmits that data to the reader.

### Cool... but why?

I dunno, just think it's pretty neat. I originally made a standalone board which you can also get here, but figured I'd design a Flipper module too as practice.

### Alright, what's on the board?

Probably the most noticeable part of the board is the giant PCB coil, used to transmit the magnetic card information. It's driven by a L293D dual H-bridge motor driver- though I'm only using one H-bridge... and it's not even driving a motor. There's a couple of LEDs too- one to show when Flipper's 5V is available, and another to show when the board is transmitting. Lastly, there's a switch in the center to allow for the module to be switched between 3.3 and 5 volts. It draws about 35 mA when on 3.3V, and about 90 mA on 5V.

Again, keep in mind that this board has no reading functionality - this board only emulates magstripe cards. 

### App for this?

[[#Magspoof]]

## RS232

![[rs232.png]]

- [Flipper Zero - Flip'n Cereal RS232 by Rabbit-Labs™](https://www.tindie.com/products/tehrabbitt/flipper-zero-flipn-cereal-rs232-by-rabbit-labs/)

### What is it?

The first ever Plug-and-Play RS232 Adapter Designed for use with the Flipper Zero. No special Configuration Needed, No having to turn on 5v, or special firmware... Yes, this will work with Official Firmware out of the box :)

### What does it do?

It handles the conversion of the TTL Communication that your flipper knows what to do with, to a standard RS232 compatible serial interface.

### What makes it special?

First off, it's smol, compact, and sits flush on top of the flipper's 10-pin GPIO header. This is important because it truly is, plug-and-play. All you need to do is make sure your baud rate to the device you're connecting to is correct, and you can interface your flipper with any RS232 interface. (I tested mine on my Ubiquiti EdgeRouter 4 using a Cat5 Cable to the console port).

### How to use it:

1. Place board onto flipper, connect Cat5 cable (RJ45) to either a console port using the proper pinout (Cisco requires a special "roll-over" cable) or to an RS232 to RJ45 adapter (commonly found on Ebay, or Amazon).
2. Open the serial APP of your choice :) In my testing, I used the UART to USB Pass-thru and was able to turn my flipper into a simple USB to RS232 adapter, for changing parameters on my router.

### Why Serial? Isn't it Old?

What's old is new, and is still in use by hundreds of thousands of devices worldwide due to it's reliability and simple standard. Everything from modems, to receipt printers, to barcode scanners, there are RS232 version of all of these things. Even my new Vinyl Cutter (Used to make the Rabbit-Labs Decals and other swag) and Laser use RS232 to interface with my PC!

### This seems pretty neat, What are the possibilities?

Write a FAP to offer Flipper-Dial-Up service, or maybe a wardialing FAP? Maybe Bad-USB, but for Serial interfaces? What about using the Flipper as a standalone controller for a laser, or a Plotter / Cutter without the need for a full-fledged PC? Maybe someone can make a FAP to use a Thermal printer to print photos taken on your Mayhem Camera! There is quite a bit of possibility :)

### Why did I make it?

Because Serial is cool. My first job out of college, I was working with old RS232/485 Time clocks, and had to deal with a LOT of serial stuff. I wish I had this back then, it would have made things a lot more interesting (like being able to maybe write a FAP or something to back up the contents of a timeclock to an SD card, rather than having to lug a laptop around).

Anyway, I've always loved serial interfaces, Maybe it's because I'm part of the generation that has the modem sounds living rent-free in the back of my brain... or maybe it's because of Cereal-Killer from the movie Hackers in 1995... or maybe it's because I'm a Rabbit and Bits are for Skids. Whatever the reason... Serial is COOL

## CANBus для Flipper Zero - Модуль подключения к CAN шине

![[canbus.jpg]]

Модуль для взаимодействия с шиной CAN. Возможность чтения данных через OBD2. Вы также можете напрямую читать, перехватывать пакеты, редактировать, передавать обратно в сеть. Модуль будет отличным инструментом для анализа, обнаружения ошибок и управления периферийными устройствами в сети CAN Bus.

Для включения модуля необходимо подать питание 5V через меню “GPIO / 5V on GPIO =ON”  
Ссылка на проект и сборку приложения под свою прошивку [https://github.com/ElectronicCats/flipper-MCP2515-CANBUS](https://github.com/ElectronicCats/flipper-MCP2515-CANBUS)

### Купить 
https://flipperaddons.com/product/canbus-flipper-zero/


## ИК-модуль TV Buster 6.3 Вт

![[ir_buster.jpeg]]


Увеличивает дальность отправки ИК-сигнала до 90 метров. Больше не нужно целиться точно в приёмник — излучатели направлены в 4 стороны для уверенного управления бытовой техникой и другими устройствами с ИК-приёмником. Суммарная мощность свечения — 6.3 Вт (против 0.3 Вт у встроенного модуля Flipper Zero). Имеется индикация передачи сигнала. Автоматически определяется Flipper Zero (для работы включите автоопределение в меню: Infrared → GPIO Settings → Signal Output → Detect).


## ESP32 aka Marauder

Предназначен для исследование сетей WiFi 2.4 ГГц с помощью Flipper Zero. Он может использоваться для сканирования ближайших Wi-Fi сетей, анализа их параметров, мониторинга сетевой активности, поиска уязвимостей в беспроводных сетях и многих других задач.

### Купить

Модуль от https://flipper.market/product-asdbwur

Описание:
Поддерживается всеми прошивками Flipper Zero Внешняя антенна на 2.4 ГГц 3dBi значительно увеличивает радиус работы устройства. Также вы можете подключить другие антенны с разъёмом RP-SMA Вы можете сохранять хейндшейки и другие пакеты на внешнюю флешку или карту памяти внутри Flipper Zero. На плате имеется светодиодный индикатор, который показывает работу устройства Всё готово для быстрого старта - в комплекте имеется MicroSD-карта, USB-картридер, а само устройство уже прошито. Просто установите приложение [[#[ESP32 ] WiFi Marauder]] из магазина приложений Flipper Zero, подключите плату к флипперу и начните пользоваться Если вам потребуется обновить прошивку, в больше не нужно хитрым образом нажимать кнопки. Вы можете прошиться через MicroSD-карту или прямо флиппером с помощью приложения [[#ESP Flasher]] (должен быть установлен вместе с прошивкой Unleashed или Momentum) Quick Flash- > ESP32 WROOM -> Marauder


---

# iButton

![[ibutton.png]]

iButton — это общее название для формата электронного ключа в форм-факторе металлической “таблетки”. Еще его называют Dallas Touch Memory. Часто его ошибочно называют “магнитным” ключом, но это неправильно, ничего магнитного в нем нет. Внутри iButton полноценный микрочип, работающий по цифровому протоколу.

## Что такое iButton
  
Название iButton — это продукт фирмы Dallas Semiconductor, в 1991 году выпустившей на рынок ключ под торговой маркой Touch Memory, потом замененной на iButton.

При поднесении ключа к считывателю, контакты соприкасаются, и на ключ подается питание. Далее осуществляется передача ID ключа. Иногда ключ не считывается сразу, потому что внешние контуры ключа и считывателя не соприкоснулись. В этом случае нужно упереть ключ в одну из стенок считывателя.

![[ibutton2.png]]

Для считывания ключа необходимо зайти в меню iButton —> Read и приложить читаемый ключ к контактной площадке. Считанный ключ можно сразу эмулировать, записать на болванку, либо сохранить на SD-карту. Хоть контактная площадка находится на задней стороне от экрана, можно быстро наловчиться читать ключи не разворачивая флиппер, просто на ощупь.

![[flipper_cut_scheme_read_ibutton.mp4]]

## Режим эмуляции iButton

  
В режиме эмуляции ключа, Флиппер сам выступает ключом и программно эмулирует iButton из памяти. ID ключа для эмуляции во Flipper Zero можно добавить двумя способами:  
  

- **Считать существующий ключ** — сохранить ID ключа на SD-карту и выбирать нужный ключ в любой момент
- **Вручную ввести ID ключа** — даже если в руках нет нужного ключа, но его ID известен, его можно ввести вручную. Так, например, можно сфотографировать ID ключа и отправить его другу с флиппером, без необходимости передавать физический ключ

## iButton через внешний GPIO

  
Контакт iButton на нижней крышке также выведен на гребенку GPIO. Это можно использовать для подключения к нестандартным считывателям, ключам, любым устройствам работающим по протоколу 1-Wire вроде датчиков. Мы используем эти контакты для анализа сигналов через осциллограф. При этом, этот контакт не совсем честный GPIO, потому что имеет подтяжку к 5V.

![[ibutton3.jpeg]]

## Формат данных в ключе Dallas

  
  
Домофон считывает из iButton 8 байт (64 бита) информации, чтобы решить, открывать дверь или нет.  
  
Структура данных этих 8 байт следующая:  
  

- 1 байт — код семейства (Family Code), для iButton он всегда равен 0x01
- 6 байт — серийный номер ключа
- 1 байт — контрольная сумма СRC

Код семейства у ключей Dallas всегда **0x01**. Если у вас этот код отличается, то скорее всего, это не ключ от домофона.  
  
Серийный номер в некоторых случаях выгравирован на ключе, но может:  
  

- Не содержать все 8 байт
- Иметь последовательность символов задом-наперед
- Иметь начало в непонятном месте

![[ibutton4.jpeg]]

На картинке выше показан неочевидный пример гравировки ID на оригинальном ключе iButton. В нем читать байты нужно справа налево, контрольная сумма написана слева, а family code справа.

## Ввод ID вручную

  
Если ID ключа известен, его можно ввести во Флиппер вручную. Это удобно когда самого физического ключа нет, например можно передать нужные байты просто в чате или скинув другу фото. На видео показан пример создания нового ключа Cyfral из 2 байт. Новый сгенерированный ключ сохраняется на SD-карту.

![[add_manually_cyfral_compressed.mp4]]

При создании ключа нужно выбрать его тип: Dallas, Cyfral или Metakom. От этого будет зависеть длина ID и протокол, используемый при эмуляции. После ввода ID Флиппер предложит ввести имя нового ключа, либо использовать сгенерированное.

## Запись ключей 1-Wire Dallas

  
Существуют ключи Dallas, которые можно записать и которые нельзя. Популярные перезаписываемые iButton болванки: RW1990, TM2004, TM01C. Процесс записи имеет свои нюансы, разберем их.  
  
**Запись болванки может требовать повышенного напряжения** — например, для записи менее популярной RW2000 требуется напряжение 8 В (правда это Cyfral, но смысл понятен).  
  
**Некоторые болванки требуют финализиации** — после финализации ключ больше не может быть перезаписан. Этим пользуются некоторые домофоны, пробуя перезаписать ключ перед считыванием, чтобы избежать поддельных ключей. Обычно для финализации используют импульс напряжения и специальную команду, которая может отличаться для разных ключей.  
  
Существуют болванки, которые могут подходить ко всем типам ключей: Dallas/Cyfral/Metakom. Флиппер умеет записывать основные популярные болванки.

Чтобы записать ключ на болванку, нужно выбрать желаемый ключ из меню `iButton —> Saved —> Имя_ключа` и выбрать пункт Write. Далее прислонить перезаписываемый ключ к контактной площадке. После записи на болванку, флиппер проверяет корректность записи и показывает сообщение об успешной записи ID.

Протоколы Metakom и Cyfral — отечественные разработки, распространенные только в СНГ. В отличие от ключей Dallas, они работают не по напряжению, а по току. Это менее распространенные и более дорогие ключи. Они очень чувствительны к параметрам ключа (частота, сила тока, амплитуда сигнала и пр.), из-за чего изготовление дубликатов бывает капризным процессом.  
  
Cyfral и Metakom не принимают никакие команды. При подаче питания на ключ, он сразу начинает бесконечно посылать ID за счет изменения сопротивления. Таким образом, логические уровни определяются сопротивлением ключа. По документации ключей условно принимается, что информационные слова кода выдаются начиная с младшего бита.

## Что такое мастер ключ?

  
Обычно это ключ, который сам не открывает дверь, а позволяет добавлять в память новые ключи. Он записан в отдельную область памяти домофона. Такой ключ может одновременно для одних домофонов быть мастер-ключом, а для других обычным. Это всего лишь циферки, которые записаны в одну или другую область памяти домофона.  
  

## Играясь заблокировали домофон?

  
Такой вариант возможен, когда в домофоне есть “блокирующий ключ”. Он блокирует домофон для всех остальных ключей, пока не снимут блокировку с помощью мастер-ключа.

## Вездеходы
Некоторые старинные домофоны с ключами Dallas имеют в памяти базу ID ключей, заполненную не полностью. Незаполненные поля имеют некоторое значение, иногда соответствующее всем нулям (0x00) или всем единицам (0xFF). Для проверки домофона на дремучесть создаются два ключа: один со всеми нулями, другой со всеми единицами.  
Эти ключи содержат неправильный код семейства (не 0x01) и неправильный CRC (вообще не контрольная сумма)!!! — Да, бывают и такие исключения.  
  
Часто используют универсальные ключи, они же “вездеходы”, подходящие на группу домофонов, например для всего района. Этот ключ может быть один на город, один на группу домов, может быть дефолтным для какой-то модели, а может и вовсе отсутствовать.

Словари для [iButton Fuzzer](https://lab.flipper.net/apps/fuzzer_ibtn) и [RFID Fuzzer](https://lab.flipper.net/apps/fuzzer_rfid) можно найти по ссылкам:

https://t.me/flipperzero_unofficial_ru/37058
https://t.me/flipperzero_unofficial_ru/37072

или в папке [dictionary ](https://github.com/RadiatedMonday/flipper_zero_docs/tree/main/dictionary)

Словарики вездеходов можно закинуть на карту и выбирать в программе iButton Fuzzer:
Кнопка `DOWN` -> **Load UIDs from file**

Или просто использовать iButton Fuzzer с дефолтными кодами


---


# Bad USB
TODO
https://habr.com/ru/articles/767996/
https://github.com/UNC0V3R3D/Flipper_Zero-BadUsb
https://github.com/aleff-github/my-flipper-shits/
https://github.com/I-Am-Jakoby/Flipper-Zero-BadUSB
https://github.com/FalsePhilosopher/badusb
https://github.com/FalsePhilosopher/BadUSB-Playground/
https://github.com/ooovenenoso/BadUSB-GPT
https://github.com/UberGuidoZ/Flipper/tree/main/BadUSB/BadUSB-MarkCyber
https://github.com/UberGuidoZ/Flipper/tree/main/BadUSB/Bombs
https://github.com/nocomp/Flipper_Zero_Badusb_hack5_payloads
https://github.com/grugnoymeme/flipperzero-badUSB
https://github.com/UberGuidoZ/Flipper/tree/main/BadUSB/MacOS-narstybits
https://github.com/UberGuidoZ/Flipper/tree/main/BadUSB/Zero-Lazagne
https://github.com/atomiczsec/My-Payloads
https://github.com/emptythevoid/flipperzero/tree/main/badusb
https://github.com/UberGuidoZ/Flipper/tree/main/BadUSB/s4dic%20-%20BadUSB/passwordgrabber
https://github.com/MarkCyber/BadUSB



Flipper Zero может выступать в качестве устройства BadUSB, распознаваемого компьютерами как устройство интерфейса пользователя (HID), такое как клавиатура или даже мышь. Устройство BadUSB может изменять системные настройки, открывать бэкдоры, извлекать данные, запускать обратные оболочки или делать практически все, что может быть достигнуто с помощью физического доступа. Это делается путем выполнения набора команд, написанных на скриптовом языке Rubber Ducky, также известном как DuckyScript. Этот набор команд также называется полезной нагрузкой.

## Flipper Zero scripting language
Прежде чем использовать Flipper Zero в качестве устройства BadUSB, вам необходимо написать payload в формате .txt в любом ASCII текстовом редакторе.
 Flipper Zero может выполнять расширенный синтаксис скрипта Rubber Ducky. Синтаксис совместим с классическим Rubber Ducky Scripting Language 1.0, но предоставляет дополнительные команды и функции, такие как метод ввода ALT + Numpad, команда SysRq и многое другое.
 
## Uploading new payloads to Flipper Zero
После создания полезной нагрузки вы можете загрузить ее на свой Flipper Zero через qFlipper или мобильное приложение Flipper в папку SD-карта/badusb/. Новые полезные нагрузки будут доступны в приложении Bad USB.

![[qflipper_file_manager.mp4]]

## Using your Flipper Zero as a BadUSB device

### Via USB connection

To turn your Flipper Zero into a BadUSB device using USB, do the following:

1. If qFlipper is running on your computer, close it.
2. On your Flipper Zero, go to **Main Menu -> Bad USB.**
3. Select the payload.
4. Make sure the Bad USB app is in **USB mode** — you should see a USB logo (as shown below).
   To switch to USB mode, press **USB**.
![[usb_mode_badusb.webp]]

5. If needed, you can modify the keyboard layout (US English is default) by pressing **Layout** and selecting from the list of layouts.
6. Connect your Flipper Zero to the computer via a USB cable.
7. Press **Run** to execute the payload on the computer.

![[bad_usb_compressed.mp4]]

### Via BLE сonnection

To turn your Flipper Zero into a BadUSB device using Bluetooth Low Energy, do the following:

1. Activate Bluetooth on your Flipper Zero by going to **Main Menu -> Settings -> Bluetooth**.
2. If qFlipper is running on your computer, close it.
3. On your Flipper Zero, go to **Main Menu -> Bad USB.**
4. Select the payload.
5. Make sure the Bad USB app is in **BLE mode** — you should see a Bluetooth logo (as shown below).
   To switch to BLE mode, press **BLE**.

![[ble_mode_badusb.webp]]

6. If needed, you can modify the keyboard layout (US English is default) by pressing **Config** and selecting from the list of layouts.
7. On your computer, go to Bluetooth settings and connect to the detected wireless BadUSB device.
8. Confirm connection both on your computer and Flipper Zero (by selecting **OK** on both devices).
9. On your Flipper Zero, press **Run** to execute the payload on the computer.
10. To unpair your Flipper Zero, go to **Config** and select **Remove Pairing**.


# U2F

Flipper Zero может выступать в качестве универсального USB-токена аутентификации с использованием 2-го фактора (U2F) или ключа безопасности, который можно использовать в качестве второго фактора аутентификации при входе в веб-аккаунты. 

Ключ безопасности - это небольшое устройство, которое помогает компьютерам подтвердить, что это вы, при входе в учетную запись. Использование этой функции повышает безопасность ваших учетных записей.

## Setting up your Flipper Zero as a security key

Before using the U2F feature, you need to register your Flipper Zero as a security key for two-factor authentication of a user on your web accounts.

To add the device as a security key to your account, do the following:

1. If the qFlipper application is running on your computer, close the application.
2. Connect your Flipper Zero to the computer via a USB cable.
3. On your Flipper Zero, go to **Main Menu** **-> U2F** and make sure that **Connected** is displayed on the screen.
4. In your web account, activate the two-factor authentication of a user by following the website’s instructions. Websites such as [Google](https://support.google.com/accounts/answer/185839?hl=en&co=GENIE.Platform%3DDesktop&oco=0#zippy=%2Cuse-security-keys-to-increase-phishing-protection "Google"), [X](https://help.twitter.com/en/managing-your-account/two-factor-authentication "https://help.twitter.com/en/managing-your-account/two-factor-authentication"), [Facebook](https://www.facebook.com/help/148233965247823 "Facebook"), [GitHub](https://docs.github.com/en/authentication/securing-your-account-with-two-factor-authentication-2fa/configuring-two-factor-authentication "GitHub"), and others have different procedures for adding security keys.
5. Choose a security key as the 2nd verification step.
6. On your Flipper Zero, press **OK** to confirm the registration of Flipper Zero as a security key.
![[u2f.webp]]

![[u2f_2.png]]


## Signing in with your Flipper Zero

Once you’ve added your Flipper Zero to your account as a security key, you can use the device as the 2nd factor.

To sign in to your account with Flipper Zero, do the following:

1. If the qFlipper application is running on your computer, close the application.
2. Connect your Flipper Zero to your computer via a USB cable.
3. On your Flipper Zero, go to **Main Menu** **-> U2F** and make sure that **Connected** is displayed on the screen.
4. While signing in to your web account, complete the 1st verification step in your account by entering the password.
5. Once you get the request for the security key, press **OK** on your Flipper Zero to confirm that it is you.

![[omked.webp]]




# Apps

![[store.webp]]

Приложения - это каталог, в котором собраны инструменты и игры, разработанные сообществом Flipper Zero. Вы можете получить доступ к приложениям из [Flipper Mobile App](https://docs.flipper.net/mobile-app "Flipper Mobile App") and [Flipper Lab](https://lab.flipper.net "Flipper Lab")

Также существуют альтернативные магазины приложений https://flipp-app.onrender.com/ и https://flipc.org/. Большую часть времени не работают.

![[flipper-zero-apps-mobile-and-desktop-1.webp]]

## Bluetooth
### BLE Spam
см. раздел [[#BLE Spam]]

### BT trigger
Подключаем флиппер к телефону, запускаем камеру. Приложение делает фотку посылая код Volume Up. Работает и на iOS и на Android

### Anki Remote
Пульт для [Anki](https://apps.ankiweb.net/) 

### BT Remote for kodi
Пульт для [kodi](https://kodi.tv/)

### FindMy Flipper
Подключение флиппера в Эпловый Локатор. 
Для нормальной работы нужно клонировать существующий AirTag
Инструкции: https://github.com/MatthewKuKanich/FindMyFlipper

### Bluetooth Remote

Use Flipper as a HID remote control over Bluetooth

- Keynote - Remote for presentations
- Keynote Vertical - Alternate remote for presentations
- Keyboard - A functional keyboard, including modifier keys
- Numpad - Number pad
- Media - Media controls
- Apple Music macOS - Alternate music controls
- Movie - Media controls for watching a movie
- Mouse - Move the cursor and send clicks
- TikTok / YT Shorts - Specialized controls for short-form videos
- Mouse Clicker - Repeatedly click the mouse after a delay
- Mouse Jiggler - Moves the mouse every few seconds
- Mouse Jiggler Stealth - Moves the mouse a random direction and distance after a random time period
- PushToTalk - Controls to unmute your microphone with various services

### PC Monitor

Flipper Application for monitoring PC resources

**[A backend running on your PC is required](https://github.com/TheSainEyereg/flipper-pc-monitor-backend/releases)**

## Games
На флиппере идут десятки игр, включая порт doom, тетрис, судоку, астеройды, шахматы, крестики-нолики и, конечно, Ну Погоди!

## GPIO

### BMI Air Mouse

The app allows you to turn your Flipper into a USB or Bluetooth air mouse

Hardware:
The custom module is using Bosch BMI160 accelerometer/gyroscope chip connected via I2C.

###  [PMSx003] Airmon
*получить значения с аппаратных се*
Plantower PMSx003 sensor reader

###  AVR Flasher

Application for flashing AVR microcontrollers

#### Wiring

The AVR ISP Programmer includes a wiring pinout diagram in the app. You can also find it here:

| FLIPPER PIN | AVR PIN          |
| ----------- | ---------------- |
| 1           | 5V (optional)    |
| 2           | MOSI             |
| 3           | MISO             |
| 4           | CLOCK (optional) |
| 5           | SCK              |
| 6           | RESET            |
| 7           | -                |
| 8           | GND              |
| 9           | 3.3V             |
| 10          | -                |
| 11          | GND              |
| 12-18       | -                |

#### Supported Microcontrollers

- ATtinyXXXX
- ATmegaXXXX
- AT43Uxxx
- AT76C711
- AT86RF401
- AT90xxxxx
- AT94K
- ATAxxxxx
- ATA664251
- M3000
- LGT8F88P
- LGT8F168P
- LGT8F328P

###  BarCode ScannerE
*Если занимаетесь настройкой POS, то может пригодится*

Emulates a barcode scanner for testing cash registers. Why buy a scanner when you have a flipper?

###   \[ESP32\] Camera Suite
A camera suite application for the Flipper Zero ESP32-CAM module.

Software to run an ESP32-CAM module on your Flipper Zero device.

Full setup, wiring guide, etc. in the main project README here: [https://github.com/CodyTolene/Flipper-Zero-Camera-Suite](https://github.com/CodyTolene/Flipper-Zero-Camera-Suite)

Firmware is needed for the ESP32-CAM module, see here for more information: [https://github.com/CodyTolene/Flipper-Zero-Camera-Suite#firmware-installation](https://github.com/CodyTolene/Flipper-Zero-Camera-Suite#firmware-installation)


Button mappings:

**Up** = Contrast Up.

**Down** = Contrast Down.

**Left** = Toggle invert.

**Right** = Toggle dithering on/off.

**Center** = Take a picture and save to the "DCIM" folder at the root of your SD card. Image will be saved as a bitmap file with a timestamp as the filename ("YYYYMMDD-HHMMSS.bmp"). If flash is on in the settings (enabled by default) the ESP32-CAM onboard LED will light up when the camera is opened.

**Back** = Go back.

Settings:

**Orientation** = Rotate the camera image 90 degrees counter-clockwise starting at zero by default (0, 90, 180, 270). This is useful if you have your camera module mounted in a different orientation than the default.

**Flash** Toggle the ESP32-CAM onboard LED on/off while using the camera.

**Dithering Type** Change between the Cycle Floyd–Steinberg, Jarvis-Judice-Ninke, and Stucki dithering types.

**Haptic Effects** = Toggle haptic feedback on/off.

**Sound Effects** = Toggle sound effects on/off.

**LED Effects** = Toggle LED effects on/off.

### Coffee-EEPROM-FAP
*взлом древних кофе-автоматов, принимающих аппаратный "pen"*
https://medium.com/@wh00hw/vendors-still-allow-you-to-hack-the-vending-machine-34ddad81dbad

###  RC2014 ColecoVision
 application and [RC2014](https://rc2014.co.uk/) module allowing the Flipper to be used as a controller for ColecoVision games on the [RC2014](https://rc2014.co.uk/).

https://github.com/ezod/flipperzero-rc2014-coleco

###  DAP Link

Enables use of Flipper as a debug probe for ARM devices, implements the CMSIS-DAP protocol

This application allows you to use your Flipper Zero as a [Free-DAP](https://github.com/ataradov/free-dap) based SWD/JTAG debugger. Free-DAP is a free and open source firmware implementation of the [CMSIS-DAP](https://www.keil.com/pack/doc/CMSIS_Dev/DAP/html/index.html) debugger.

SWD, JTAG , CMSIS-DAP v1 (18 KiB/s), CMSIS-DAP v2 (46 KiB/s), VCP (USB-UART).

WinUSB for driverless installation for Windows 8 and above.

### \[ESP32\] WiFi Marauder
*Практически все работы с Wifi лучше проводить на полноценном ноутбуке или на телефоне с KaliNethunter*

Приложуха для работы с [[#ESP32 aka Marauder]]

### ESP8266 Deauther
*Практически все работы с Wifi лучше проводить на полноценном ноутбуке или на телефоне с KaliNethunter*
https://github.com/SequoiaSan/FlipperZero-Wifi-ESP8266-Deauther-Module

### esp8266_deauther v2
*Практически все работы с Wifi лучше проводить на полноценном ноутбуке или на телефоне с KaliNethunter*

https://github.com/Timmotools/flipperzero_esp8266_deautherv2

### IFTTT Virtual Button

*Для фанатов IFTTT. Для остальных бесполезно*

application that allows you to send IFTTT requests from FlipperZero through an esp8266 module to automate some actions. If This Than That, which could translate to "if this happens, then make that happen". As the phrase says, it allows you to automate activities by connecting to different online services.

### ESP Flasher
Flipper Zero app to flash ESP chips from the device (no computer connection needed!)

Flipper Zero app to flash ESP chips from the device (no computer connection needed!). Requires an ESP chip connected to the flipper's UART pins (e.g. Wi-Fi devboard). For information on how to connect, see the ESP pinout/wiring details on UberGuidoZ's GPIO section: [https://github.com/UberGuidoZ/Flipper/tree/main/GPIO](https://github.com/UberGuidoZ/Flipper/tree/main/GPIO)

Supported targets: ESP32  
ESP8266  
ESP32-S2  
ESP32-S3  
ESP32-C3  
ESP32-C2  
ESP32-H2

### \[W5500\] Ethernet

Проверка сети. Получает ip и пингует внешний адрес. Всё. С вас 1000р за модуль+devboard

https://lab.flipper.net/apps/eth_troubleshooter

Подробности в разделе модули: [[#Модуль W5500]]


### Evil captive portal

*Практически все работы с Wifi лучше проводить на полноценном ноутбуке или на телефоне с KaliNethunter*

https://github.com/bigbrodude6119/flipper-zero-evil-portal

### \[ESP32\] Evil portal

This project will turn your Wi-Fi dev board into an open access point. When users try to connect to this access point they will be served a fake login screen. User credentials are sent to the Flipper and logged on the SD card.

https://github.com/bigbrodude6119/flipper-zero-evil-portal

### Flashlight

Подключаем светодиод, получаем фонарик

### FlipTDI

https://lab.flipper.net/apps/flip_tdi

This is a FT232H device emulation application

Сonnect Flipper to your computer and open the application, a new FT232H compatible device will appear in the system

![[flipper-zero-as-a-usb-to-gpio-spi-uart-adapter-for-your-pc-v0-be0l5n7lejtd1.webp]]

Modern PCs and laptops don't have GPIO connectors and don't support interfaces popular in embedded systems. Luckily, USB adapters offer a solution. For example, those based on the FTDI FT232H chip enable connection to GPIO, SPI, I2C, UART, and JTAG. There is a lot of software available for USB adapters, including bus scanners, memory chip programmers, and plugins for Smart Home. You can also find python libs (e.g. pyftdi, pylibftdi) and hundreds of code examples on github.

Thanks to the FlipTDI app, Flipper Zero can emulate USB adapters based on the FTDI chip. This means you can use software and tools designed for these adapters. Currently, FlipTDI supports UART, SPI, and GPIO.

To use your Flipper as a USB-to-GPIO/SPI/UART adapter:

1. Install the Flip TDI app from the Flipper Apps Catalog and launch it    
2. Connect your Flipper to your PC via USB. The FlipTDI device will be detected    
3. Follow the instructions for the PC software you want to use with the adapter

### Flipagotchi

> Displays the screen of the Pwnagotchi on the Flipper's screen. Interfaces over UART with a Raspberry Pi Zero W running the Pwnagotchi program.

Что такое pwnagotchi:

[проект Pwnagotchi](https://pwnagotchi.ai/) предназначен для исследования беспроводных сетей Wi-Fi. 
Он [внешне напоминает](https://telegra.ph/Ponagochi-Pwnagotchi-Drug-kompanon-i-instrument-dlya-audita-bezopasnosti-Wi-Fi-setej-08-01) Flipper Zero и построен на базе Raspberry Pi.

Pwnagotchi использует Raspberry Pi Zero W и специально настроенное программное обеспечение, которое позволяет устройству автоматически сканировать и анализировать ближайшие беспроводные сети Wi-Fi.

В своей традиционной модификации понагочи не имеет кнопок и иных физических элементов управления. После загрузки переходит в режим мониторинга, сканирует эфир и в момент подключения клиента к точке доступа, перехватывает и сохраняет на microSD карту файл с пакетами аутентификации (так называемый 4-way handshake). Если зверёк видит пару клиент-точка, то применяет атаку деаутентификации, с последующим перехватом хендшейка в момент обратного подключения клиента.

### \[J305\]Atomic Dice Roller

🎲☢ An atomic dice roller for the Flipper Zero ☢🎲

https://github.com/nmrr/flipperzero-atomicdiceroller

Это приложение генерирует истинные случайные числа путем хэширования временных меток, полученных при измерении тика счетчиком Гейгера (т.е. при обнаружении бета- или гамма-излучения). Временные метки имеют 32-битное разрешение и генерируются на основе сигнала частотой 64 МГц.

Для работы нужна вот такая плата:

![[geiger.png]]

### \[J305\] geiger counter

https://github.com/nmrr/flipperzero-geigercounter

Приложение для Счетчика Гейгера с алиэкспресса.

Подключение железной части:

![[geigercounter.jpg]]

###  SPI-Terminal

SPI TERMINAL - это приложение SPI, которое позволяет вам управлять внешними устройствами с помощью SPI. Ваш Flipper может выступать в качестве ведущего или ведомого устройства SPI. Режим Slave позволяет отслеживать связь между различными периферийными устройствами SPI.

SPI _(Serial Peripheral Interface)_ - интерфейс связи между цифровыми устройствами, по нему МК может общаться с датчиками и модулями или с другими МК. Среди основных интерфейсов связи (UART, I2C, SPI) SPI - самый простой, самый быстрый и неприхотливый, но требует больше пинов для подключения.

- Синхронный (есть тактовая линия)
- Последовательный (данные передаются бит за битом по одному проводу)
- Количество пинов: от 2 до 4
- Скорость: зависит от устройства и качества линии, от 0 Гц до 150 МГц
- Топология: одно ведущее устройство
- Количество ведомых на шине: не ограничено

SPI является шиной, т.е. к одним и тем же выводам может быть подключено несколько устройств. На шине есть только одно ведущее устройство - **Master**, остальные - ведомые, **Slave**. Ведущее выбирает, с каким из ведомых взаимодействовать, может отправлять и читать с него данные. Ведущим обычно является основной МК в схеме, а остальные - различные цифровые микросхемы, датчики или вспомогательные МК.


Приложение использует низкоуровневый SPI-интерфейс микропроцессора STM32WB55RG. Все данные передаются с помощью субмодуля DMA и могут достигать скорости до 32 Мбит/с в режиме Master и до 24 Мбит/с в режиме Slave.

https://github.com/janwiesemann/flipper-spi-terminal

Про SPI в ардуино хорошо написано у AlexGyver:
https://alexgyver.ru/lessons/spi/

### Scope (flipperscope)

https://lab.flipper.net/apps/flipperscope
https://github.com/anfractuosity/flipperscope

Осцилограф из флиппера. 

```ad-danger
До 2.5В
```

![[freq.jpg]]


### \[TEA5767\] FM Radio

TEA5767 - супер компактный радио приёмник частотно модулированного сигнала. Позволяет принимать радиостанции в FM диапазоне

### \[ESP32\] Ghost ESP

https://lab.flipper.net/apps/ghost_esp

Companion app for [Ghost ESP Firmware.](https://ghostesp.net/)

WiFi: Scan networks, beacon spam, deauth attacks, packet capture, evil portal, network connection, and printer control. Bluetooth: Flipper discovery, Pineapple Detection, AirTag scanning, and packet capture. GPS: Wardriving capabilities.

### 7-Segment Output

https://lab.flipper.net/apps/gpio_7segment_output
Control a 7-segment display with GPIO pins


### GPIO Controller

A visual tool to control the general purpose pins of the Flipper Zero

https://github.com/Lokno/gpio_controller


### GPIO Reader 2

This is a fork of the `gpio` app built into the flipper, with added functionality to read GPIO inputs

https://github.com/biotinker/flipperzero-gpioreader



### Sentry Safe

Открытие электронного сейфа фирмы Sentry с помощью Flipper Zero с использованием уязвимости в протоколе управления контроллера (UART)

Подробности в видео:
https://www.youtube.com/watch?v=trpOoM6ugnk


### Timelapse
Simple intervalometer app, works via GPIO pins

  
### \[NMEA\] GPS
A simple Flipper Zero application for NMEA 0183 serial GPS modules, such as the

- Adafruit Ultimate GPS Breakout.

Heavy lifting (NMEA parsing) provided by minmea.
Works with GPS modules via UART, using NMEA protocol.

https://lab.flipper.net/apps/gps_nmea

###  \[HC-SR\] Dist. sensor

- Author is Ported and modified by [@xMasterX](https://github.com/xMasterX "GitHub User: xMasterX")
- Comment: (original by Sanqui [https://github.com/Sanqui/flipperzero-firmware/tree/hc_sr04](https://github.com/Sanqui/flipperzero-firmware/tree/hc_sr04) - How to connect -> (5V -> VCC / (GND -> GND / (13TX -> Trig / (14RX -> Echo

### i2c Tools

Set of i2c tools

https://lab.flipper.net/apps/i2ctools

### INA Meter

Application for reading TI INAxxx sensors.

Когда вы создаете проект промышленной установки, робота, дистанционно управляемой модели ровера или аналогичный проект с микрокомпьютером, встает задача контроля состояния систем электропитания. Вам нужно проверять напряжение на аккумуляторах, потребляемый ток и мощность. Не исключено, что в проекте есть не одна, а несколько цепей, где нужно обеспечить подобный контроль.

Результаты контроля можно передавать, например, на пульт управления или использовать как‑то еще. Когда заряд аккумуляторов подходит к концу, можно отключить какие‑нибудь устройства с целью экономии энергии или инициировать зарядку аккумуляторов вашего устройства. Если в устройстве есть сервоприводы, можно контролировать потребляемую ими мощность, а при перегрузке отключать все сервоприводы или некоторые из них.

Этим и занимаются модули с чипами INA

INA Meter is an application for Flipper Zero that allows you to read I2C-connected current/power monitors from Texas Instruments.

#### Supported Sensors:

- **INA219** – 0–26V, 16-bit resolution (±0.5% accuracy)
- **INA226** – 0–36V, 16-bit resolution (±0.1% accuracy)
- **INA228** – 0–85V, 20-bit resolution (±0.05% accuracy)

#### Wiring

| Flipper pin | INAxxx |
| ----------- | ------ |
| C0 (16)     | SCL    |
| C1 (15)     | SDA    |
|             |        |

https://lab.flipper.net/apps/ina_meter

### Lightmeter

#### Lightmeter app for photography

An application that suggests settings for your manual camera based on the reading of the ambient light sensor. Can also be used in a pure lux meter mode.

#### Supported sensors

- BH1750
- MAX44009

#### Wiring

| Sensor | Flipper Zero |
| ------ | ------------ |
| VCC    | 3.3V         |
| GND    | GND          |
| SCL    | C0           |
| SDA    | C1           |

https://lab.flipper.net/apps/lightmeter

### Logic analyzer

https://github.com/g3gg0/flipper-logic_analyzer

### Longwave Clock

Decode or demonstrate long wave time signals

Receive long wave time signals through inexpensive GPIO modules, or simulate receipt if you don't own any.
Supports DCF77 as well as MSF, with more protocols to be implemented in the future.

https://lab.flipper.net/apps/longwave_clock

### LORA Terminal

app to control Lora Breakout board.

В качестве готового LoRa модуля можно воспользоваться продукцией от RAK Wireless, например, модулем [RAK11720 Breakout Board](https://store.rakwireless.com/products/rak11720-breakout-board-rak11721?m=3&h=wisduo-breakout), который продается по 18$ за штуку. Можно взять вариант подешевле (без BLE) [RAK3172 Breakout Board](https://store.rakwireless.com/products/wisduo-breakout-board-rak3272s?m=3&h=wisduo-breakout) за 15$. Оба базируются на трансивере **Semtech SX1262.** Заказать можно через [Ali](https://aliexpress.ru/item/1005005328447503.html).

Оба варианта позволяют использовать любую совместимую внешнюю антенну с разъемом RP-SMA Female. Фирменная антенна конечно же идет в комплекте c модулем за такую цену.

На плате также присутствуют все необходимые контакты для подключения модуля по UART и взаимодействия через AT-команды.

Сам модуль функционирует на фирменной прошивке от RAK Wireless – [RUI3](https://www.rakwireless.com/en-us/products/rui3), которая предоставляет разработчикам возможность создавать собственное программное обеспечение с использованием RUI3 API, которое легко интегрируется с популярными средами разработки, такими как Arduino и Visual Studio. Подробнее можно ознакомиться в [документации](https://docs.rakwireless.com/RUI3/#overview).

https://github.com/aafksab/lora_terminal

### Magspoof

Enables wireless transmission of magstripe data

Модуль: [[#Flipper Zero Magspoof Module]]

https://github.com/zacharyweiss/magspoof_flipper


### \[Mx2125\] Accelerometer

- Author is [@jamisonderek](https://github.com/jamisonderek "GitHub User: jamisonderek"). [https://github.com/jamisonderek/flipper-zero-tutorials/tree/main/gpio](https://github.com/jamisonderek/flipper-zero-tutorials/tree/main/gpio)

### \[MH-Z19\] CO2 sensor

Measuring carbon dioxide (CO2) with mh-z19
https://lab.flipper.net/apps/mh_z19

### NRF24
Приложения для модуля [[#Радиомодуль 2.4 ГГц NRF24L01 Mouse Hunter]] :
- \[NRF24\] Batch
- \[NRF24\] Mouse Jacker
- \[NRF24\] Mouse Jacker MS
- \[NRF24\] Scanner
- \[NRF24\] Sniffer
- \[NRF24\] Sniffer MS
- \[NRF24\] Channel Scanner
- \[NRF24\] Tool

### Pokemon Trade Tool

![[pockemon.png]]

Pokemon exchange from Flipper Zero to Game Boy, supports Generation I & II non-Japanese games

### RadSens (Radiation Sensor)

App for RadSense radiation measurement module by ClimateGuard

RadSens – модульный arduino дозиметр на счетчике Гегера-Мюллера и интерфейсом I2C. Трубка СМБ20 включена в комплект поставки. Трубка установлена в держатели и может быть быстро демонтирована. В качестве исходящего пакета по I2C, датчик формирует 3 значения:

- Интенсивность излучения (мкР/ч) c алгоритмом сильного усреднения, для точного измерения излучения за большой промежуток времени (500с)
- Интенсивность излучения (мкР/ч) c алгоритмом регистрации локальных источников и загрязнений с динамическим диапазоном времени расчета
- Количество зарегистрированных импульсов с момента последнего запроса по шине I2C

![[radsens.mp4]]


https://climateguard.ru/radsens_mini/

### RCWL-516 Motion Sensor
app for RCWL-0516 radar.
RCWL-0516 is a doppler radar microwave motion sensor module

https://github.com/ahmedafe1/rcwl_0516-Flipperzero

### SD SPI
Lock and Unlock SD card / Micro SD card through SPI protocol.

Все карты **SD**/**SDHC**, удовлетворяющие стандартам организации SD Group, поддерживают защиту данных паролем на уровне карты. Это означает, что Вы можете назначить пароль (длиной до 16 байт) для любой карты SD. Если установлен пароль, то операции чтения/записи данных карты заблокированы. Если Вы захотите получить доступ к данным карты, то сначала должны ввести пароль.

Пароль хранится на самой карте, не на компьютере, куда подключается карта. Предоставленный по паролю доступ сохраняется только до тех пор, пока карта получает непрерывное питание; если у карты пропадет питание, и пароль в момент пропадания питания не был снят, то при восстановлении питания карты блокировка по паролю снова придет в действие.

#### Pinout

| Flipper Zero | SD Card |
| ------------ | ------- |
| 9/3.3V       | +3.3V   |
| 8/GND        | GND     |
| 2/A7         | Mosi    |
| 3/A6         | Miso    |
| 4/A4         | CS      |
| 5/B3         | SCK     |

![[scheme_sd_lock.png]]

#### Force Unlock
force unlock стирает пароль, вместе с данными

https://github.com/Gl1tchub/Flipperzero-SD-SPI


### ServoTester и ServoTester 2

![[servo_test.png]]

PWM generator for testing RC servos. Available modes: Manual, Center, Auto.

![[servo_test.mp4]]

Смысл приложения - заменить отдельный тестер

![[original-servo-tester.jpeg]]


https://lab.flipper.net/apps/servotester
https://github.com/mhasbini/ServoTesterApp

### Signal Generator

![[sig_gen.png]]

This is a simple signal generator that can be used to generate a signal with a given frequency. There are two modes: PWM and Clock.

#### PWM Mode

In PWM mode, the signal is generated by toggling the GPIO pin at the given frequency with a given pulse width. You can also select the GPIO pin on which the signal will be generated.

#### Clock Mode

In Clock mode, the signal is generated from the clock signal of the microcontroller. The frequency of the clock signal can be divided by a given value to get the desired frequency. The maximum frequency that can be generated is 64MHz, and the minimum is 32.768kHz. You can also manually select the frequency divider from 1 to 16. The GPIO pin is fixed at 13 (TX).

### Simultaneous UHF RFID Reader

Simultaneous UHF RFID Reader that supports the M6E Nano, M7E Hecto, and YRM1000 series Readers. Read up to 150 UHF tags per second \[Using ThingMagic Readers\]!

для YRM100 есть отдельное приложение *\[YRM100\] UHF RFID

### SPI Mem Manager

Application for reading and writing 25-series SPI memory chips

![[spi_mem_manager.png]]

https://lab.flipper.net/apps/spi_mem_manager


### \[Mx2125\] Step Counter

Шагомер на модуле [Memsic2125](https://www.chipdip.ru/product/ie-memsic2125-otsenochnaya-plata-akselerometra-na-innoexp-9000052858) 

https://lab.flipper.net/apps/stepcounter

### SWD Probe

Современные микроконтроллеры поддерживают двухпроводной интерфейс отладки SWD, что значительно упрощает подключение. При обратном проектировании найти эти два контакта намного проще, чем при использовании JTAG, когда вам приходилось подключать два или более контакта. Однако поиск двух контактов по-прежнему требует небольшой работы, которая еще больше упрощается с помощью этого приложения.

Это приложение пытается определить правильный ответ SWD на выбранных вами проводах и подает звуковой сигнал, когда вы находите правильные контакты, показывая обнаруженный идентификационный регистр и, что более важно, распиновку SWD. Не имеет значения, какие два вывода вы выберете, просто выберите любые два из GPIO.

Приложение отправляет пакеты и сканирует ответ по всем выводам, а затем уточняет их в течение нескольких попыток.

Для пользователя это просто - подключите две тестовые иглы, подключите очевидный вывод GND и протестируйте все тестовые площадки. 

https://lab.flipper.net/apps/swd_probe

  
### UART Terminal

- Reading from UART in text or hex mode
- Sending commands
- Sending AT commands
- Sending fast commands
- Sending binary packets (in hex)
- Baudrate selection
- UART pins selection (2 options)

#### Connecting

| Device UART interface | Flipper Zero pin (default) | Flipper Zero pin (option) |
| :-------------------: | :------------------------: | :-----------------------: |
|          RX           |           13 TX            |           15 TX           |
|          TX           |           14 RX            |           16 TX           |
|          GND          |         8, 18 GND          |         8, 18 GND         |

Info: If possible, do not power your devices from 3V3 (pin 9) Flipper Zero. It does not support hot plugging.

![[uart_term.jpg]]

https://lab.flipper.net/apps/uart_terminal


### u-blox GPS

App to display and log data from a u-blox GPS module connected over  I2C to the Flipper. This app can also synchronize the Flipper's internal clock to GPS time.

https://lab.flipper.net/apps/ublox

### Temp sensors reader

Application for reading temperature, humidity and pressure sensors like a DHT11/22, DS18B20, BMP280, HTU21 and more.

#### List of supported sensors

- DHT11
- DHT12
- DHT21/AM2301
- DHT22/AM2302
- DHT20/AM2108
- AM2320
- AHT10
- AHT20
- SHT30/GXHT30
- SHT31/GXHT31
- SHT35/GXHT35
- LM75
- BMP180
- BMP280
- BME280
- BME680
- HTU21D(F)
- HDC1080
- DS18B20
- DS18S20 (DS1820)
- DS1822
- MAX31855
- MAX6675

https://lab.flipper.net/apps/unitemp

### \[USPING\] Distance Sensor

Ultrasound measurments with PING))) Parallax sensor SKU 28015 (3 wires)

Modified by privet971 using PING))) sensor from Parallax 3/23/2023

Use only gpio 13 for TX & RX wired to SIG pin

https://github.com/privet971/FlipperZeroApps/tree/main/usping

### WHC SWIO Flasher

![[whc.png]]

A WHC CH32V003 debugger/flasher tool

https://lab.flipper.net/apps/wch_swio_flasher


### Wiegand Reader

![[wiegant.png]]

This application can be used to test Wiegand readers and keypads. It can save the data to a file, and can load and replay the data. Timings are measured and displayed; which can be used to help debug Wiegand readers.

https://lab.flipper.net/apps/wiegand_reader

## Media

### Music

`FlipperMusicRTTTL` - Collection of musics for FlipperZero Music Player. 
https://github.com/neverfa11ing/FlipperMusicRTTTL



## Tools

### Key Copier

![[key_cop.jpg]]

Утилита работает с ключами Kwikset KW1, Schalge SC4 и их аналогами. Для копирования бородки надо выбрать модель ключа, приложить сам ключ к экрану Flipper Zero и отрегулировать положение выемок. Цифровой слепок можно использовать для изготовления дубликата в мастерской. Пользователь, показавший работу утилиты, отмечает, что последнее время часто использует её для создания копий ключей. Разработчики отмечают, что для более точной подгонки лучше закрыть один глаз.

Сайт для генерации STL модели:
https://keygen.co/

Github, если сайт недоступен:
https://github.com/ervanalb/keygen

![[key_copy.mp4]]




---

# Flipper Mobile App

![[mobile.webp]]

With **Flipper Mobile App**, you can remotely control and update your Flipper Zero, share saved keys, manage and edit data, and more. Flipper Mobile App enhances the functionality of your Flipper Zero, making it even more convenient to use.

The application is available on iOS and Android:
https://apps.apple.com/app/flipper-mobile-app/id1534655259
https://play.google.com/store/apps/details?id=com.flipperdevices.app

## Connecting to Flipper Zero

After you download Flipper Mobile App and activate Bluetooth on your phone, you need to connect the mobile application to your Flipper Zero:

1. Activate Bluetooth on your Flipper Zero by following these steps:

    1) Go to **Main Menu** **-> Settings** **->** **Bluetooth**.
    2) Set **Bluetooth** to **ON**.

2. In Flipper Mobile App, tap **Connect**.

3. On the next page, next to the detected Flipper Zero’s name, tap **Connect**.

![[mobile2.webp]]


4. In Flipper Mobile App, **enter the pairing code** displayed on the Flipper Zero screen.

5. Tap **Pair** to finalize pairing.

6. Wait until Flipper Mobile App is done synchronizing with your Flipper Zero.

### If your Flipper Zero is not detected

- Make sure Bluetooth is activated on your Flipper Zero. -> [How to turn on Bluetooth on Flipper Zero](https://docs.flipperzero.one/basics/settings#eJsLP "How to turn on Bluetooth on Flipper Zero").
    
- Check the Bluetooth connection on your phone.
    
- Disconnect Flipper Zero from other devices. -> [How to forget all paired devices on Flipper Zero](https://docs.flipperzero.one/basics/settings#eJsLP "How to forget all paired devices on Flipper Zero").
    
- Update Flipper Zero to the latest firmware version. It is important to update your Flipper Zero regularly. -> [How to update the firmware on Flipper Zero](https://docs.flipperzero.one/basics/firmware-update "How to update the firmware on Flipper Zero").
    
- Check the latest version of Flipper Mobile App is installed on your phone. -> [App Store](https://apps.apple.com/us/app/flipper-mobile-app/id1534655259 "App Store") or [Google Play](https://play.google.com/store/apps/details?id=com.flipperdevices.app "Google Play").
    
- Reboot your Flipper Zero by pressing and holding the **LEFT** and **BACK** buttons for 5 seconds.
    

### If Flipper Mobile App fails to synchronize with your Flipper Zero

- Unpair the devices and then pair them again. -> To unpair the devices, go to **Main Menu -> Settings -> Bluetooth -> Forget All Paired Devices**.
    
- Restart your Flipper Zero. -> Press and hold the **LEFT** and **BACK** buttons.
    
- Restart your smartphone.
    
- Disable Sleep mode on your Flipper Zero. -> Go to **Main Menu -> Settings -> System** and set **Sleep Method** to **Legacy**.
    

## Flipper Mobile App: overview

After Flipper Zero is connected to Flipper Mobile App, you’ll see the **Main Menu** tab. In this tab, you can update your Flipper Zero via Bluetooth, see additional options, manually synchronize, play sound on your Flipper Zero, and more.

![[flipper-mobile-app-main-menu.webp]]

![[flipper-mobile-app-main-tab-2.webp]]

In **Device** **Info**, you can see detailed information about Flipper Zero’s hardware and firmware.

![[flipper-mobile-app-device-info.webp]]


In **Options**, depending on the operating system, you can find the backup function, saved logs, file manager, reboot function, and bug report function.


![Options on iOS](https://images.archbee.com/3StCFqarJkJQZV-7N79yY/SLD7fR8-ACrvyLBr3opYD_flipper-mobile-app-options-ios.png?format=webp "Options on iOS")

The **Archive** tab lists all the saved remotes, keys, and cards. In this tab, you can see favorites, search through the list, and restore deleted remotes, keys, and cards.
![[flipper-mobile-app-archive.webp]]

To see detailed information, tap one item from the list. In **Key Info**, you can emulate or play back saved keys, add to favorites, rename, add notes, review technical information, delete, and share keys with others.

![[flipper-mobile-app-sub-ghz.webp]]
![[flipper-mobile-app-125-khz.webp]]
![[flipper-mobile-app-nfc.webp]]

![[flipper-mobile-app-infrared.webp]]

![[flipper-mobile-app-ibutton.webp]]

In the **Apps** tab, you can access the catalog of community-developed apps and install them to your Flipper Zero via Bluetooth LE.

![[flipper-mobile-app-apps-tab.webp]]

In the **Tools** tab, you’ll find tools that expand Flipper Zero functionality, such as Mfkey32 (Extract MF Keys) for calculating MIFARE Classic keys, and Remotes Library for getting access to a wide range of infrared remotes. These tools are developed and maintained by our team.

![[mo.webp]]



# qFlipper
qFlipper - это настольное приложение, которое позволяет обновлять Flipper Zero с помощью USB-кабеля. qFlipper доступен в Windows, macOS и Linux. 

## Установка

Чтобы установить qFlipper на свой компьютер, выполните следующие действия:
1. Загрузите установочный файл qFlipper для вашей операционной системы.
    https://flipperzero.one/downloads
2. Запустите скачанный файл и следуйте инструкциям в зависимости от операционки

### Win
Далее...далее

![[qflipper_win.webp]]

### Mac
Доступно для **macOS version 10.14 и позже**

![[qflipper_mac.webp]]


### Lin
Для Linux qFlipper загружается в формате AppImage. Перед запуском qFlipper в Linux вам необходимо сделать его исполняемым:

#### Используя графический интерфейс пользователя

1. В файловом менеджере щелкните загруженный файл правой кнопкой мыши.
2. Перейдите в Свойства -> Разрешения.
3. Установите флажок Разрешить выполнение файла как программы, если вы используете файловый менеджер на базе Nautilus (Files, Nemo, Caja), или установите флажок Является исполняемым, если вы используете Dolphin, или измените выпадающий список "Выполнить" на "Любой", если вы используете PCManFM.
4. Закройте диалоговое окно.
5. Дважды щелкните по файлу AppImage для запуска.

#### Используя терминал

1. Откройте терминал.
2. Перейдите в каталог, содержащий файл AppImage.
3. Сделайте файл исполняемым. Например: ```
```
chmod +x qFlipper-x86_64-1.3.3.AppImage
```
4. Установите правила udev:
```
./qFlipper-x86_64-1.3.3.AppImage rules install
```
4. Запустите AppImage: 
```
./qFlipper-x86_64-1.3.3.AppImage
```

## Обновление флиппера
1. Подключите Flipper Zero к компьютеру с помощью USB-кабеля.
2. На компьютере запустите qFlipper.
3. В qFlipper перейдите на вкладку Advanced controls
4. Нажмите строку **Install from file** и выберите [[#Прошивка (Firmware)|скачанную прошивку.]]
![[qflipper_update_2.webp]]
5. Нажмите кнопку `INSTALL`, чтобы запустить процесс обновления.

## Backup
1. Запускаем qFlipper
2. жмем `BACKUP` на вкладке Advanced controls

![[qflipper_backup.webp]]


# Разработка


## "Hello world"
### Шаг первый: учимся собирать прошивку
```bash
git clone --recursive https://github.com/DarkFlippers/unleashed-firmware
cd unleashed-firmware
git chechout unlshd-082 #переключение на последнюю версию
./fbt COMPACT=1 DEBUG=0 updater_package
```

Check `dist/` for build outputs.

Use `flipper-z-{target}-update-{suffix}.tgz` to flash your device.

### Шаг второй: пишем приложение
Для начала, поймем, а под что мы вообще собрались писать.  
Центральный контроллер — [STM32WB55](https://www.st.com/en/microcontrollers-microprocessors/stm32wb55rg.html), два arm-ядра (одно Cortex-M4, второе Cortex-M0+, заведует всяким радио), 1 мегабайт флеша, 256 кб оперативки, 2.4ггц трансивер (Zigbee, Thread, BLE), SPI, I2C, USB, куча таймеров, криптография (включая хранилище неизвлекаемых ключей). В общем, Linux не поставить, но по меркам микроконтроллеров довольно жирный камень.  
Кроме самого микроконтроллера есть еще и субгигагерцовый трансивер — [СС1101](https://www.ti.com/lit/ds/symlink/cc1101.pdf) от TI, который может работать на основных частотах, 315/433/868/915 МГц. Для работы с NFC используется отдельный ридер, [ST25R3916](https://www.st.com/en/nfc/st25r3916.html), работа с 125 кГц метками осуществляется силами самого процессора, как и с iButton и IR.

Однако, в отличии от "обычной" разработки под МК, когда на микроконтроллере выполняется исключительно ваша логика, тут не весь камень отдан в ваше распоряжение. Помимо самого контроллера, тут есть куча железок — и трансивер, и NFC, и экран, и всякое-разное на I2C шине, типа микросхемы управления светодиодом и подсветкой. Нормально управлять всем этим в суперцикле не получится (точнее, вы в процессе этого напишите свою RTOS), поэтому тут есть операционная система — FreeRTOS, в которой, во-первых, удобно разграничивать разные логические приложения в таски, а во-вторых, которая сама занимается переключением тасков и их контекста, сама определяет, что именно надо запустить сейчас и так далее.

Например, сразу при старте, даже без запуска других приложений, уже становятся активны 19 тасков — начиная от тех, что обслуживают события с кнопок, слежение за зарядом аккумулятора и выдача данных для иконки заряда, рисование интерфейса, который рисует эту иконку и весь остальной интерфейс в придачу, и заканчивая записью-чтением из памяти и реализацией консольного интерфейса. Даже у состояния дельфина есть отдельный таск.  
Разумеется, это не означает, что они работают сразу все и активно. Большинство из них находятся в состоянии сна подавляющую часть времени, просыпаясь только тогда, когда им приходит сообщение, из ресурсов занимая только часть оперативки под свой стек.

Зачем нужна такая сложность? Ну, например, для удобства разработки. Вот хочется, например, вам в приложении сделать "дрр" вибромотором. Для этого надо не только его включить, но и выключить в нужное время. Если вы будете делать это внутри своего приложения, которое запускается на контроллере монопольно, то вам придется делать какую-то логику для ожидания перед отключением. А если ваше приложением упадет или зависнет, то вибромотор останется включенным. А это самый простой пример, гораздо сложнее разрулить такого рода штуки с другим железом, требующим жестких таймингов. А если в это время вы еще и хотите что-то на экран выводить.. Поэтому и RTOS. Тут можно просто отправить сообщение процессу, ответственному за работу с вибромотором, в котором сказать "включи его на 300мс", и забыть про это — ОС сама разбудит этот таск, сама позаботится о доставке в него сообщения, и вновь разбудит его через 300мс, чтобы оно могло вибромотор отключить. А в это время другие процессы будут продолжать работать.

Многозадачность тут вытесняющая, так что можно не думать над тем, когда отдавать управление планировщику, если считаете что-то сложное, он сам отберет у вас управление. Но наломать дров все же можно — это не настольная ОС, где до железа пять слоев абстракций, тут можно работать напрямую, например с шиной I2C, и часто эта работа требует реалтайма, поэтому существуют способы сказать RTOS, чтобы во время выполнения этого куска кода вас ни за что не прерывали. Но вот если в процессе выполнения этого кода вы уйдете в бесконечный цикл, девайсу кроме перезагрузки уже ничего не сможет помочь.

Однако, тут нет сборщиков мусора, и если вы выделяете какую-то память или ресурс специально, то в конце использования ее надо освободить, иначе могут быть спецэффекты. В каких-то ситуация просто будет утекать память, а где-то может случиться переход по невалидному адресу, что приведет к крашу, который выразится в зависании (это чтобы можно было воткнуть отладчик и посмотреть что привело к падению). **Все что вы аллоцировали — надо освободить.** Не берите грех на душу, легко может быть такая ситуация, когда забыли освободить что-то вы сейчас, а упадет другое приложение потом.

TODO
https://docs.flipper.net/development
https://yakovlev.me/hello-flipper-zero/
https://habr.com/ru/articles/594895/
https://habr.com/ru/articles/710700/
https://habr.com/ru/news/706238/
https://habr.com/ru/articles/700378/
https://habr.com/ru/companies/sportmaster_lab/articles/721000/
https://habr.com/ru/companies/selectel/articles/742438/
https://habr.com/ru/articles/744476/
https://habr.com/ru/articles/742428/
https://habr.com/ru/companies/ruvds/articles/768658/


# Video Game Module

Компания Flipper Devices [представила](https://blog.flipper.net/introducing-video-game-module-powered-by-raspberry-pi/) модуль Video Game для мультитула Flipper Zero. С его помощью пользователи могут выводить изображение на внешние мониторы, использовать Flipper Zero в качестве цифрового осциллографа или беспроводного контроллера для управления курсором мыши.

![[game_module.jpg]]

Модуль Video Game разработали в сотрудничестве с компанией Raspberry Pi. Устройство работает на базе микроконтроллера RP2040. Он же используется на плате Raspberry Pi Pico. Команде разработчиков Flipper Zero пришлось разогнать микроконтроллер, чтобы он мог генерировать видеосигнал, что позволило оснастить модуль выходом для подключения монитора или телевизора. Кроме того, разработчики добавили гироскоп и акселерометр, что позволяет использовать Flipper Zero в качестве беспроводного контроллера.

Технические характеристики модуля Video Game:

- микроконтроллер Raspberry Pi RP2040 на двухъядерном процессоре ARM Cortex-M0+ с тактовой частотой до 133 МГц;    
- 264 КБ SRAM;    
- 6-осевой датчик отслеживания положения устройства TDK ICM-42688-P;    
- порт USB-C для подключения модуля к компьютеру;    
- видеовыход с разрешением 640x480 пикселей с частотой 60 Гц;    
- 11 GPIO контактов, подключённых к микроконтроллеру, два контакта заземления и один питания на 3,3 В;    
- кнопка сброса для перезагрузки;    
- кнопка загрузки для разработчиков.    

Компания не может использовать название порта видеовыхода, потому что не получила необходимый сертификат. В блоге Flipper Devices отмечают, что первая буква в названии — H, а последняя — I.

![[game_module_2.png]]


## Видеовыход

С помощью видеовыхода можно дублировать изображение с экрана Flipper Zero на телевизор или монитор. Так данные проще увидеть и не надо присматриваться к маленькому дисплею. Модуль передаёт видеосигнал DVI-D с разрешением 640x480 пикселей и частотой обновления 60 Гц. Компания отмечает, что несмотря на маленькое разрешение, изображение на экране телевизора выглядит чётко.

## Гироскоп и акселерометр

Модуль Video Game оснащён 6-осевым датчиком отслеживания положения устройства. В нём используется гироскоп и акселерометр. С его помощью Flipper Zero можно использовать в качестве контроллера в играх или для управления курсором мыши. Специально для демонстрации возможностей компания выпустила игру [Air Arkanoid](https://lab.flipper.net/apps/air_arkanoid) и утилиту [Air Mouse](https://lab.flipper.net/apps/vgm_air_mouse). Их можно установить с помощью [[#Flipper Mobile App]] Flipper.

![[game_module_3.gif]]

Инженеры компании отдельно вывели SPI-контакты датчика отслеживания положения устройства. Это позволяет приложениям, запущенным на Flipper Zero, использовать данные датчика. Одновременно с этим контакты подключены к микроконтроллеру RP2040, чтобы прошивка модуля тоже могла воспользоваться датчиком.

![[game_module_4.jpeg]]

## Осциллограф Scoopy

Для модуля доступен [Scoopy](https://github.com/fhdm-dev/scoppy) — проект открытого осциллографа 200 кГц. С его помощью модуль можно прошить и использовать в качестве мобильного осциллографа. Для работы необходимо подключить устройство к Android-смартфону кабелем USB-C.

![[game_module_5.jpeg]]

## Прошивка и схемы

Компания полностью открыла проект, поделившись [кодом прошивки](https://github.com/flipperdevices/video-game-module) и [схемами устройства](https://docs.flipper.net/video-game-module/gpio?_gl=1*1npsue3*_ga*MTY3MzQ3OTg3Ni4xNzA3NzU2MDAw*_ga_GM78S6JK0K*MTcwNzgwNzM5MC40LjEuMTcwNzgwNzQwNS40NS4wLjA.). Все данные опубликовали на GitHub. Сторонние разработчики могут присоединиться к проекту или использовать информацию в собственных проектах. Кроме того, Flipper Devices опубликовала [демонстрационный пример](https://github.com/flipperdevices/flipperzero-game-engine) для Flipper Zero и модуля Video Game.

Все неиспользуемые пины микроконтроллера RP2040 вывели на 14-контактную гребёнку GPIO. Это делает модуль Video Game полностью совместимым с платой Raspberry Pi Pico.

## Самостоятельная сборка

Устройство вполне можно собрать самому. Инструкции доступны здесь:
https://github.com/EstebanFuentealba/Flipper-Zero-Video-Game-Module-DIY


## Video Game Module Tool

Приложение для обновления прошивки
https://lab.flipper.net/apps/video_game_module_tool