# Apple-Android-DNS-Config
Коллекция DoH (DNS over HTTPS) и DoT (DNS over TLS) DNS-конфигураций (.mobileconfig для Apple, DoT для Android и DoH для браузеров). Приватность, минимальные логи, стабильная работа с AI и игровыми сервисами.

## Поддерживаемые устройства
- iPhone (iOS) — файл .mobileconfig
- iPad (iPadOS) — файл .mobileconfig
- MacBook / iMac (macOS) — файл .mobileconfig
- Android — DoT
- Браузеры, которые поддерживают DoH

## Цели
- Программное обеспечение предназначено исключительно для некоммерческого использования в образовательных и исследовательских целях. Не для распространения.

## Цели исследований, изучение:

- наблюдение ведения логов активности, либо минимальных логов активности (подписаны в скобочках (Private))
- повышения конфиденциальности
- снижения трекинга
- блокировки рекламы и мусора (где поддерживается)
- прямой работы с нейросетями (GPT, Grok и т. д.) и игровыми сервисами - (после установки подписаны в скобочках как Game или AI)
- минимальных задержек при работе с нейросетями и играми


## Формат
- «.mobileconfig» устанавливаются напрямую в систему Apple.
- «DoT» для Android и др.
- «DoH» для браузеров и др.

## Состав DoH (DNS over HTTPS), DoT (DNS over TLS) - серверов
В скобочках указан DoH, присутствующий в конфигурации для Apple, который также можно использовать в любом браузере или системе, поддерживающей DoH.




🧠 Нейросети / игровые сервисы (после установки на Apple подписаны как AI или Game):


1. https://dns.comss.one/dns-query — (AI, Game, RU) Comss.one — публичный DoH, РФ — https://www.comss.ru/page.php?id=7315

2. https://dns.malw.link/dns-query — (AI, Game, DE) malw.link — DoH с фильтрами рекламы/мусора, США — https://info.dns.malw.link/

3. https://5u35p8m9i7.cloudflare-gateway.com/dns-query — (AI, Game, DE) Cloudflare Gateway — корпоративный стабильный DoH, США — https://info.dns.malw.link/

4. https://xbox-dns.ru/dns-query — (AI, Game, RU) Xbox-DNS — DoH для игр и нейросетей, РФ — https://xbox-dns.ru/

5. https://dns.astracat.ru/dns-query — (AI, Game, RU) AstraCat — DoH для AI и обхода цензуры, РФ — https://astracat.ru/

6. https://dns.nullsproxy.com/dns-query — (Game) NullsProxy DNS — DoH для обхода региональных ограничений Supercell (Brawl Stars, Clash Royale, Clash of Clans), РФ/Беларусь — https://nullsproxy.com/

7. https://dns.geohide.ru:8443/dns-query — нет в конфигурации .mobileconfig — DoH для игр и нейросетей, РФ — https://dns.geohide.ru:8443/



🧠 То же самое, но DoT (DNS over TLS) для Android:

dns.comss.one

dns.malw.link

5u35p8m9i7.cloudflare-gateway.com

xbox-dns.ru

dns.astracat.ru

dns.nullsproxy.com

dns.geohide.ru:8443





🔒 Приватные DoH (DNS over HTTPS) (минимальные логи)  (после установки подписаны в скобочках (Private)) для браузеров в том числе.


1. https://dns.digitale-gesellschaft.ch/dns-query — (CH, Private) Digitale-Gesellschaft — приватный европейский DoH без логов, Швейцария — https://www.digitale-gesellschaft.ch/dns/

2. https://dns2.digitale-gesellschaft.ch/dns-query — (CH, Private) Digitale-Gesellschaft 2 — резервный приватный DoH без логов, Швейцария — https://www.digitale-gesellschaft.ch/dns/

3. https://doh.libredns.gr/dns-query — (DE, Private) LibreDNS — приватный DNS без цензуры и логов, ЕС (Греция) — https://libredns.gr/

4. https://anycast.uncensoreddns.org/dns-query — (DK, Private) UncensoredDNS Anycast — приватный DNS без фильтрации и логов, Дания — https://blog.uncensoreddns.org/

5. https://unicast.uncensoreddns.org/dns-query — (DK, Private) UncensoredDNS Unicast — приватный DNS без фильтрации и логов, Дания — https://blog.uncensoreddns.org/

6. https://dns.switch.ch/dns-query — (CH, Private) Swit.ch — академический приватный DoH, Швейцария — https://www.switch.ch/dns/

7. https://dns.quad9.net/dns-query — (SE, EG, Private) Quad9 — приватный DNS с защитой от угроз без логов, Швейцария — https://quad9.net/

8. https://basic.rethinkdns.com/dns-query — (PL, Private) RethinkDNS — приватный DNS с блокировкой трекеров, ЕС — https://rethinkdns.com/

9. https://freedns.controld.com/p0/dns-query — (Private, DE) Control D Unfiltered — приватный DNS без фильтрации, Канада — https://controld.com/

10. https://freedns.controld.com/p2/dns-query — (Private, DE) Control D Malware — приватный DNS с защитой от вредоноса, Канада — https://controld.com/



🔒 То же самое, но DoT (DNS over TLS) для Android:

dns.digitale-gesellschaft.ch

dns2.digitale-gesellschaft.ch

dot.libredns.gr

anycast.uncensoreddns.org

unicast.uncensoreddns.org

dns.switch.ch

dns.quad9.net

basic.rethinkdns.com

p0.freedns.controld.com

p2.freedns.controld.com




🌍 Публичные и универсальные DoH (DNS over HTTPS) для браузеров в том числе.

1. https://dns.google/dns-query — (FL) Google DNS — публичный высокосовместимый DNS, США — https://developers.google.com/speed/public-dns/docs/doh

2. https://doh.opendns.com/dns-query — (DE) OpenDNS (Cisco) — коммерческий публичный DNS, США — https://support.opendns.com/hc/en-us/articles/360038086532-Using-DNS-over-HTTPS-DoH-with-OpenDNS

3. https://dns.nextdns.io/dns-query — (RU) NextDNS — настраиваемый DoH с выборочным логированием, США — https://nextdns.io/

4. https://1dot1dot1dot1.cloudflare-dns.com/dns-query — (FL) Cloudflare DoH/DoT — быстрый публичный DNS, США — https://1.1.1.1/

5. https://cloudflare-dns.com/dns-query — (FL) Cloudflare (classic) — стандартный публичный DoH, США — https://developers.cloudflare.com/1.1.1.1/encryption/dns-over-https/

6. https://odoh.cloudflare-dns.com/dns-query — (FL) Cloudflare ODoH — обфусцированный DoH для анонимности, США — https://blog.cloudflare.com/oblivious-dns/

7. https://security.cloudflare-dns.com/dns-query — (FL) Cloudflare Malware Filter — публичный DNS с блокировкой вредоноса, США — https://developers.cloudflare.com/1.1.1.1/encryption/dns-over-https/

8. https://dns.adguard-dns.com/dns-query — (DE) AdGuard DNS (Filtered) — DoH с фильтрацией рекламы/трекеров, Кипр (разработчики РФ) — https://adguard-dns.io/kb/general/dns-providers/

9. https://unfiltered.adguard-dns.com/dns-query — (DE) AdGuard DNS (Unfiltered) — DoH без фильтрации, Кипр (разработчики РФ) — https://adguard-dns.io/kb/general/dns-providers/

10. https://common.dot.dns.yandex.net/dns-query — (RU) Yandex DNS (Unfiltered) — базовый публичный DoH, РФ — https://yandex.ru/support/dns/

11. https://safe.dot.dns.yandex.net/dns-query — (RU) Yandex DNS (Filtered) — DoH с фильтрацией, РФ — https://yandex.ru/support/dns/

12. https://doh.sb/dns-query — (DE) Doh.sb — публичный DoH с защитой от вредоносных доменов, Германия — https://doh.sb/



🌍 То же самое, но DoT (DNS over TLS) для Android:

dns.google

doh.opendns.com

dns.nextdns.io

1dot1dot1dot1.cloudflare-dns.com

cloudflare-dns.com

odoh.cloudflare-dns.com

security.cloudflare-dns.com

dns.adguard-dns.com

unfiltered.adguard-dns.com

common.dot.dns.yandex.net

safe.dot.dns.yandex.net

doh.sb






## Примечание
DNS — не VPN. IP-адрес не меняется.
Некоторые серверы могут работать нестабильно из-за планового обслуживания, технических неисправностей, DDoS‑атак или других внешних факторов.

## Отказ от ответственности:
Распространение запрещено. Приведённые выше сервера не принадлежат разработчикам ПО. Данное программное обеспечение предназначено исключительно для некоммерческого использования в образовательных, исследовательских целях и не для распространения. Разработчики не несут ответственности за любую коммерческую деятельность либо распространение с использованием и по использованию данного ПО, за последствия использования, стабильность серверов, юридические претензии третьих лиц.


