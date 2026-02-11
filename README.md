# doh-dot-config

# Apple-Android-DNS-Config

Collection of DoH (DNS over HTTPS) and DoT (DNS over TLS) configurations for testing and personal use.

## Supported Devices
- macOS → MacBook, iMac, Mac mini, Mac Pro
- Apple TV
- iPad (iPadOS)
- iPhone (iOS)
- Apple Watch
- iPod touch
- Android - DoT
- Browsers - DoH

## Purpose
- Personal testing only, not for redistribution
- Testing network performance and latency with AI services and games
- Privacy protection and tracker/ad reduction
- Direct usage with AI and gaming services

AI / gaming servers (appear as Xbox or GPT on Apple after install)

1. (GPT, RU) AstraCat (AI) https://dns.astracat.ru/dns-query — DoH for AI/games; RU
2. (Xbox) Xbox-DNS https://xbox-dns.ru/dns-query — DoH for games & AI; RU
3. (GPT, FL) Cloudflare Gateway https://5u35p8m9i7.cloudflare-gateway.com/dns-query — stable corporate DoH; US
4. (GPT, DE) dns.malw.link https://dns.malw.link/dns-query — filtered DoH; DE
5. (GPT, RU) Comss.one https://dns.comss.one/dns-query — public DoH; RU

Same — DoT for Android

1. dns.astracat.ru
2. xbox-dns.ru
3. 5u35p8m9i7.cloudflare-gateway.com
4. dns.malw.link
5. dns.comss.one

Private DoH (low logs) (shows as Private)

1. Control D Malware (Private, DE) https://freedns.controld.com/p2/dns-query — protection; CA
2. Control D Unfiltered (Private, DE) https://freedns.controld.com/p0/dns-query — no filter; CA
3. RethinkDNS (PL, Private) https://basic.rethinkdns.com/dns-query — tracker block; EU
4. Quad9 (SE, EG, Private) https://dns.quad9.net/dns-query — threat block; CH
5. UncensoredDNS (DK, Private) https://anycast.uncensoreddns.org/dns-query — no filter; DK
6. LibreDNS (DE, Private) https://doh.libredns.gr/dns-query — no censor; EU
7. Digitale-Gesellschaft 2 (CH, Private) https://dns2.digitale-gesellschaft.ch/dns-query — backup; CH
8. Digitale-Gesellschaft (CH, Private) https://dns.digitale-gesellschaft.ch/dns-query — private EU; CH

Same — DoT for Android

1. p2.freedns.controld.com
2. p0.freedns.controld.com
3. basic.rethinkdns.com
4. dns.quad9.net
5. unicast.uncensoreddns.org or anycast.uncensoreddns.org
6. dot.libredns.gr
7. dns2.digitale-gesellschaft.ch
8. dns.digitale-gesellschaft.ch

Public & universal DoH

1. AdGuard Unfiltered https://unfiltered.adguard-dns.com/dns-query — no filter; CY/RU
2. AdGuard Filtered https://dns.adguard-dns.com/dns-query — filtered; CY/RU
3. Cloudflare Malware https://security.cloudflare-dns.com/dns-query — protection; US
4. Cloudflare ODoH https://odoh.cloudflare-dns.com/dns-query — obfuscated; US
5. Cloudflare classic https://cloudflare-dns.com/dns-query — standard; US
6. Cloudflare DoH/DoT https://1dot1dot1dot1.cloudflare-dns.com/dns-query — fast; US
7. NextDNS https://dns.nextdns.io/dns-query — customizable; EU
8. OpenDNS (Cisco) https://doh.opendns.com/dns-query — commercial; US
9. Google DNS https://dns.google/dns-query — compatible; US
10. Doh.sb (DE) https://doh.sb/dns-query — malware block; DE
11. Yandex Filtered https://safe.dot.dns.yandex.net/dns-query — filtered; RU
12. Yandex Unfiltered https://common.dot.dns.yandex.net/dns-query — basic; RU

Same — DoT for Android

1. unfiltered.adguard-dns.com
2. dns.adguard-dns.com
3. security.cloudflare-dns.com
4. family.cloudflare-dns.com
5. cloudflare-dns.com
6. 1dot1dot1dot1.cloudflare-dns.com
7. dns.nextdns.io
8. doh.opendns.com
9. dns.google
10. doh.sb
11. safe.dot.dns.yandex.net
12. common.dot.dns.yandex.net

## Notes
- Repository is public for visibility, but intended for testing purposes
