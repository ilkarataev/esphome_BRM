# esphome_Board_Relays_Modules  
В репозитории находятся файлы для создания плат. Платы управляют 8 и 4 стандатрными релейными модулями.  
  
### 8 релейный модуль  
Gerber,BOM файл 8_relays_modules/gerber_file/  
Компоненты для распайки:  
Ссылки и стоимость в Челябинске с Али конечно будет дешевле.  
1.Hilink 220v->5. - 1штука [300р](https://procontact74.ru/22-zaryadnye-ustrojstva-bloki-pitaniya/221-impulsnye-bpi/ac-dc-preobrazovatel-220v---5v-06a-hi-link-hlk-pm01).  
2.Esp32 30 pins, на моей написанно devkitv1 - 1 штука [500р](https://procontact74.ru/14-arduino-elektronnye-moduli/222/bluetooth---wi-fi-modul-esp-32-devkit-v1-new).    
3.Стойка PCHSS-6 - 2штуки 5р\*2=[10р](https://procontact74.ru/ustanovochnye-izdeliya/stoyki-dlya-pp/stojka-pchss-6-05906)  
4.Стойка PCHSN-20 - 2штуки 12\*2=[24р](https://procontact74.ru/ustanovochnye-izdeliya/stoyki-dlya-pp/stoyka-pchsn-20)  
5.Клеммник KF301-2P или XY301V-A-2P синний - 1штука. [10р](https://procontact74.ru/27-kommutaciya/05-nakonechniki-klemmy/053-klemmniki-nazhimnye-razryvnye/xy301v-2p-5mm-05307)  
6.Клеммник XY301V-A-3P 5.08мм синий - 6 штук.6*12р=[72р](https://procontact74.ru/27-kommutaciya/05-nakonechniki-klemmy/053-klemmniki-nazhimnye-razryvnye/xy301v-3p-5mm-05308)  
7.Два болта m3.  
8.Резистор smd 0805 10K - 6 штук [6р](https://procontact74.ru/01-elektronnyie-komponentyi-/40-rezistory/407-chip-0805/10-kom-40750)  
9.Конденцатор 0805 4.7 nf 50V - 6штук [12р](https://procontact74.ru/01-elektronnyie-komponentyi-/41-kondensatory/416-smd/47-nf-41637)  
10.Header-Female-2.54_1x10 -1 штука (если найти сразу на длинной ноге то можно не надствалять).[10р](https://procontact74.ru/27-kommutaciya/02-razemy/razyemyi-bls%2C-bld%2C-pls%2C-pld/pbs-1x10-shag254-02006)  
11.Надствака для 10 позиции штыревой разъем 1x10 ряд 2,54. [10р](https://procontact74.ru/27-kommutaciya/02-razemy/razyemyi-bls%2C-bld%2C-pls%2C-pld/pls-40-tin-luzhenyj-02008) можно использовать от шилда [WEMOS](https://procontact74.ru/14-arduino-elektronnye-moduli/drayveryi-dvigateley%2C-shildyi/shild-dlya-wemos-d1-14232) отдельно такие разъемы я не нашел.  
12.Разъем 2.54мм PBS-1x16 (PBS-16) - 2ш(подключение есп32). [26р](https://procontact74.ru/27-kommutaciya/02-razemy/razyemyi-bls%2C-bld%2C-pls%2C-pld/razyem-2-54mm-pbs-1x16-%28pbs-16%29)  

[Реле 530р](https://procontact74.ru/14-arduino-elektronnye-moduli/releynyie-moduli/modul-rele-8-kanalov-14229) 

Итого компоненты без платы выходят 1500р.  
<img src="https://raw.githubusercontent.com/ilkarataev/esphome_BRM/main/8_relays_modules/images/All_up.jpg" alt="front side" width="50%" height="50%"><img src="https://raw.githubusercontent.com/ilkarataev/esphome_BRM/main/8_relays_modules/images/My_board_alone_down.jpg" alt="back side" width="50%" height="50%">

Остальные фото в папке 8_relays_modules/images
### 4 релейный модуль  
Gerber,BOM файл 4_relays_modules/gerber_file/  
Корпус для печати на 3д принтере 4_relays_modules/box/
Компоненты для распайки:  
1.Hilink 220v->5. - 1штука [300р](https://procontact74.ru/22-zaryadnye-ustrojstva-bloki-pitaniya/221-impulsnye-bpi/ac-dc-preobrazovatel-220v---5v-06a-hi-link-hlk-pm01).   
2.Esp12F или Esp12e [у версии F лучше разведена антена](https://www.letscontrolit.com/wiki/index.php/Basics:_ESP8266_Types_and_Boards#:~:text=Esp%2D12E%20and%20ESP%2D12F,-%5BPic%5D%20%5BPinout&text=The%20only%20difference%20is%20the,pins%20lead%20to%20the%20outside.) - 1 штука [Esp12e-170р](https://procontact74.ru/14-arduino-elektronnye-moduli/222/wi-fi-modul-esp-12e-na-esp8266-14213) [Esp12F-195р](https://procontact74.ru/14-arduino-elektronnye-moduli/222/wi-fi-modul-esp-12f-na-esp8266-)    
3.Стойка PCHSS-6 - 2штуки 5р\*2=[10р](https://procontact74.ru/ustanovochnye-izdeliya/stoyki-dlya-pp/stojka-pchss-6-05906)  
4.Стойка PCHSN-20 - 2штуки 12\*2=[24р](https://procontact74.ru/ustanovochnye-izdeliya/stoyki-dlya-pp/stoyka-pchsn-20)  
5.Клеммник KF301-2P или XY301V-A-2P синний - 1штука. [10р](https://procontact74.ru/27-kommutaciya/05-nakonechniki-klemmy/)  
6.Клеммник XY301V-A-3P 5.08мм синий - 4 штук.4*12р=[48р](https://procontact74.ru/27-kommutaciya/05-nakonechniki-klemmy/053-klemmniki-nazhimnye-razryvnye/xy301v-3p-5mm-05308)   
7.Два болта m3.  
8.Резистор smd 0805 10K - 7 штук [7р](https://procontact74.ru/01-elektronnyie-komponentyi-/40-rezistory/407-chip-0805/10-kom-40750)   
9.Конденцатор 0805 4.7 nf 50V - 4 штуки [8р](https://procontact74.ru/01-elektronnyie-komponentyi-/41-kondensatory/416-smd/47-nf-41637)   
10.Header-Female-2.54_1x10 -1 штука (если найти сразу на длинной ноге то можно не надствалять).[10р](https://procontact74.ru/27-kommutaciya/02-razemy/razyemyi-bls%2C-bld%2C-pls%2C-pld/pbs-1x10-shag254-02006)  
11.Надствака для 10 позиции штыревой разъем 1x10 ряд 2,54. [10р](https://procontact74.ru/27-kommutaciya/02-razemy/razyemyi-bls%2C-bld%2C-pls%2C-pld/pls-40-tin-luzhenyj-02008) можно использовать от шилда [WEMOS](https://procontact74.ru/14-arduino-elektronnye-moduli/drayveryi-dvigateley%2C-shildyi/shild-dlya-wemos-d1-14232) отдельно такие разъемы я не нашел.   
12. Микросхема ams1117-3.3v [7р](https://procontact74.ru/01-elektronnyie-komponentyi-/45-mikroshemy/stabilizatoryi/ams1117-33-sot-223-450112)  
13. 74HC505A [10р на алиэкспреессе](https://aliexpress.ru/item/1005002345871977.html?spm=a2g0s.9042311.0.0.5e2c33ed3ppD1P&_ga=2.122879435.1199030528.1625373881-299414465.1625373881)  
14. Конденцатор 0805 10uf - 1 штука [5р](https://procontact74.ru/01-elektronnyie-komponentyi-/41-kondensatory/416-smd/10-uf-41650)  
15. Конденцатор 0805 22uf - 1 штука [6р](https://procontact74.ru/01-elektronnyie-komponentyi-/41-kondensatory/416-smd/chip-0805-22-uf-10v-x5r-)  

[Реле 312р](https://procontact74.ru/14-arduino-elektronnye-moduli/releynyie-moduli/modul-rele-4-kanala-14078)  
Итого без платы 962р  

<img src="https://raw.githubusercontent.com/ilkarataev/esphome_BRM/main/4_relays_modules/images/front_side_v4.1.jpg" alt="front side" width="50%" height="50%"><img src="https://raw.githubusercontent.com/ilkarataev/esphome_BRM/main/4_relays_modules/images/back_side_v4.1.jpg" alt="back side" width="50%" height="50%">

<img src="https://raw.githubusercontent.com/ilkarataev/esphome_BRM/main/4_relays_modules/images/front_side_v4.1(solder).jpg" alt="front side" width="50%" height="50%"><img src="https://raw.githubusercontent.com/ilkarataev/esphome_BRM/main/4_relays_modules/images/back_side_v4.1(solder).jpg" alt="back side" width="50%" height="50%">