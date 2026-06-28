# Расширенная версия GeoIP

Автоматизированный пайплайн для регулярной сборки и конвертации баз данных GeoIP на основе [Loyalsoldier/geoip](https://github.com/Loyalsoldier/geoip). 
Можно использовать прямые ссылки на скачивание артефактов для настройки сетевых узлов:

* **OPNsense / pfSense:** Использование сгенерированных текстовых списков в качестве внешних URL (URL Table (IPs)) для создания динамических Alias'ов в правилах Firewall.
* **Xray-core/V2Ray:** Использование обновленного `geoip.dat` для гибкого роутинга трафика (маршрутизация по геолокации, Split DNS и bypass-правила).

## Дополнительно включает в себя категории:

### Cloud / CDN

- geoip:akamai
- geoip:amazon
- geoip:cdn77

### Tech

- geoip:microsoft

## Используемые ресурсы

- https://github.com/Loyalsoldier/geoip
- https://github.com/8bitsaver/maxmind-geoip
- https://github.com/lord-alfred/ipranges
