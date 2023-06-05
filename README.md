# DalyBMS_ESPHome

Конфигурация для создания прошивки ESPHome для DalyBMS

Скачайте конфигурацию

измените строки 
wifi:
  ssid: "MyNameSSID" # имя Вашей точки доступа
  password: "wifi_password" #пароль Вашей точки доступа
ap:
  ssid: "Dalybms" # имя точки доступа ESPHome
  password: "password" # пароль точки доступа ESPHome
uart:
  tx_pin: GPIO1 # UART TX порт esp
  rx_pin: GPIO3 # UART RX порт esp
  baud_rate: 9600
daly_bms:
  update_interval: 5s # интервал опроса
