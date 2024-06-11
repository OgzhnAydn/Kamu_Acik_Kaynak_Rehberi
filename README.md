[![License](https://img.shields.io/badge/license-AGPL-blue.svg?style=flat)](https://opensource.org/licenses/AGPL-3.0)
[![Documentation](https://img.shields.io/badge/docs-latest-brightgreen.svg?style=flat)](http://docs.chan.org)
[![Support on StackOverflow](https://img.shields.io/badge/support-StackOverflow-yellowgreen.svg?style=flat)](https://stackoverflow.com/questions/tagged/ckan)
[![Build Status](https://circleci.com/gh/ckan/ckan.svg?style=shield)](https://circleci.com/gh/ckan/ckan)
[![Coverage Status](https://coveralls.io/repos/github/ckan/ckan/badge.svg?branch=master)](https://coveralls.io/github/ckan/ckan?branch=master)
[![Chat on Gitter](https://badges.gitter.im/gitterHQ/gitter.svg)](https://app.gitter.im/#/room/#Bg_Rehberi:gitter.im)




### Amaç
* Kamu kurumlarında kullanılabilecek açık kaynaklı projelerin yaygınlaştırılması amacı ile özellikle uzman ve kullanıcılar tarafından  kategorilerine göre açık kaynak uygulamaların listesinin oluşturulması 

# İçindekiler

## 1. Sunucu Sistemleri
- [İşletim Sistemi](#işletim-sistemi)
- [Veri Tabanı Yönetim Sistemi](#veri-tabanı-yonetim-sistemi)
- [Dizin Yönetimi ve Kullanıcı Cihaz Yönetimi Sistemleri](#dizin-yonetimi-ve-kullanıcı-cihaz-yonetimi-sistemleri)
- [E-Posta Sistemi](#e-posta-sistemi)
- [Alan Adı Sunucu Sistemi (DNS)](#alan-adı-sunucu-sistemi-dns)
- [Dinamik Makine Yapılandırma Protokolü (DHCP)](#dinamik-makine-yapılandırma-protokolu-dhcp)
- [Ağ İlkesi Sunucusu (NPS, RADIUS)](#ağ-ilkesi-sunucusu-nps-radius)
- [Web ve Uygulama Sunucusu](#web-ve-uygulama-sunucusu)
- [Dosya Sunucusu](#dosya-sunucusu)
- [Video Konferans Sistemi](#video-konferans-sistemi)
- [Diğer](#diğer)

## 2. Sanallaştırma Ortamları
- [Sunucu Sanallaştırma](#sunucu-sanallaştırma)
- [Konteyner Teknolojileri](#konteyner-teknolojileri)
- [Depolama Alanı Sanallaştırma](#depolama-alanı-sanallaştırma)
- [Ağ Sanallaştırma](#ağ-sanallaştırma)
- [Masaüstü Sanallaştırma ve Uygulama Sanallaştırma](#masaustu-sanallaştırma-ve-uygulama-sanallaştırma)
- [Diğer](#diğer-1)

## 3. Siber Güvenlik Yazılımları
- [Güvenlik Duvarı](#güvenlik-duvarı)
- [Web Uygulama Güvenlik Duvarı (WAF)](#web-uygulama-guvenlik-duvarı-waf)
- [Saldırı Tespit / Önleme Sistemi (IDS / IPS)](#saldırı-tespit-onleme-sistemi-ids-ips)
- [Güvenlik Bilgileri ve Olay Yönetimi (SIEM)](#guvenlik-bilgileri-ve-olay-yonetimi-siem)
- [Ağ Erişimi Kontrol Sistemi (NAC)](#ağ-erişimi-kontrol-sistemi-nac)
- [E-Posta Güvenliği](#e-posta-güvenliği)
- [Sanal Özel Ağ Sistemi (VPN)](#sanal-ozel-ağ-sistemi-vpn)
- [Ağ ve Sunucu Sistemleri İzleme Sistemi](#ağ-ve-sunucu-sistemleri-izleme-sistemi)
- [Anti-virüs](#anti-virus)
- [Güvenlik Zafiyet Yönetimi](#guvenlik-zafiyet-yonetimi)
- [Diğer](#diğer-2)

## 4. Son Kullanıcı Uygulamaları
- [İşletim Sistemi](#işletim-sistemi-1)
- [Kurumsal Uygulamalar](#kurumsal-uygulamalar)
- [Ofis Uygulamaları](#ofis-uygulamaları)
- [Multimedya Uygulamaları](#multimedya-uygulamaları)
- [Mesleki Uygulamalar](#mesleki-uygulamalar)
- [Web Uygulama Yazılımları](#web-uygulama-yazılımları)
- [Diğer](#diğer-3)

## 5. Diğer










### Proje  Aşamaları:
- Öncelik
1. Kategorilerin ve Listenin oluşturulması
1. Uyuglaması Mümkün olanlar için  uygulama örnekleri geliştirmek.
4. Listeyi sürekli güncel tutumak ve yenilemek

# Kamu Kurumları için Açık Kaynak Projeler

## Sunucu Sistemleri

| Proje            | Açıklama                                      | Kullanım Alanları                                  | Puanlama   | Kaynak     |
|------------------|-----------------------------------------------|----------------------------------------------------|------------|------------|
| Linux            | Güvenli, esnek ve özelleştirilebilir işletim sistemi | Sunucu işletim sistemi olarak geniş bir kullanım yelpazesi | ⭐⭐⭐⭐⭐ | [GitHub](https://github.com/torvalds/linux) |
| PostgreSQL       | Güçlü, açık kaynaklı ilişkisel veritabanı yönetim sistemi | Kurumsal uygulamalar, web tabanlı uygulamalar, veri depolama ve analizi | ⭐⭐⭐⭐ | [Web Sitesi](https://www.postgresql.org/) |
| Zimbra           | E-posta, takvim ve işbirliği için açık kaynak platform | Kurumsal e-posta çözümleri, ekip çalışması ve iletişim | ⭐⭐⭐ | [Web Sitesi](https://www.zimbra.com/) |
| BIND             | İnternetin en yaygın DNS sunucusu yazılımı    | Alan adı çözümlemesi, DNS hizmetleri               | ⭐⭐⭐⭐ | [Web Sitesi](https://www.isc.org/bind/) |
| ISC DHCP         | Dinamik IP adresi atama ve yapılandırma için DHCP sunucusu | Ağ yapılandırması, IP adres yönetimi               | ⭐⭐⭐ | [Web Sitesi](https://www.isc.org/dhcp/) |
| FreeRADIUS      | RADIUS protokolüne dayalı ağ erişim denetim (NAC) sunucusu | Ağ erişim denetimi, kablosuz ağ güvenliği          | ⭐⭐⭐⭐ | [GitHub](https://github.com/FreeRADIUS/freeradius-server) |
| Apache HTTP Server | Dünyanın en popüler web sunucusu             | Web siteleri, web uygulamaları, sunucu yanı yazılımlar | ⭐⭐⭐⭐ | [Web Sitesi](https://httpd.apache.org/) |
| Samba            | SMB/CIFS protokolleri üzerinden dosya ve yazıcı paylaşımı sağlayan yazılım | Dosya ve yazıcı paylaşımı, ağ dosya depolama çözümleri | ⭐⭐⭐ | [Web Sitesi](https://www.samba.org/) |
| Jitsi            | Güvenli ve ölçeklenebilir video konferans çözümü | Uzaktan iletişim, eğitim, işbirliği                | ⭐⭐⭐⭐ | [GitHub](https://github.com/jitsi) |
| Nextcloud        | Dosya depolama, paylaşım ve işbirliği platformu | Bulut depolama, işbirliği, dosya senkronizasyonu   | ⭐⭐⭐⭐ | [GitHub](https://github.com/nextcloud) |



## Yönetim ve İş Süreçleri

| Proje / Yazılım  | Açıklama                                      | Kullanım Alanları                                  | Puanlama   | Kaynak     |
|------------------|-----------------------------------------------|----------------------------------------------------|------------|------------|
| OpenProject      | Proje yönetim yazılımı                        | Proje ve görev yönetimi, zaman çizelgeleri         | ⭐⭐⭐⭐ | [Web Sitesi](https://www.openproject.org/) |
| ERPNext          | Kurumsal kaynak planlama yazılımı             | Muhasebe, envanter, İK, satış, satın alma          | ⭐⭐⭐ | [GitHub](https://github.com/frappe/erpnext) |

## Veri Analizi ve Görselleştirme

| Proje / Yazılım  | Açıklama                                      | Kullanım Alanları                                  | Puanlama   | Kaynak     |
|------------------|-----------------------------------------------|----------------------------------------------------|------------|------------|
| Metabase         | Kolayca kurulabilen veri analizi platformu    | Raporlama, veri analizi, veri görselleştirme       | ⭐⭐⭐⭐ | [GitHub](https://github.com/metabase/metabase) |
| Grafana          | Açık kaynaklı metrik analizi ve izleme platformu | Veritabanı sorgulamaları, gösterge panelleri, izleme | ⭐⭐⭐⭐ | [GitHub](https://github.com/grafana/grafana) |

## Güvenlik

| Proje / Yazılım  | Açıklama                                      | Kullanım Alanları                                  | Puanlama   | Kaynak     |
|------------------|-----------------------------------------------|----------------------------------------------------|------------|------------|
| OpenVAS          | Açık kaynaklı güvenlik açığı tarama sistemi   | Ağ güvenliği taramaları, güvenlik açıklarını belirleme | ⭐⭐⭐⭐ | [GitHub](https://github.com/greenbone/openvas) |
| OSSEC            | Host bazlı saldırı tespit sistemi (HIDS)      | Güvenlik izleme, olay müdahale                      | ⭐⭐⭐⭐ | [GitHub](https://github.com/ossec/ossec-hids) |

## Vatandaş Hizmetleri

| Proje / Yazılım  | Açıklama                                      | Kullanım Alanları                                  | Puanlama   | Kaynak     |
|------------------|-----------------------------------------------|----------------------------------------------------|------------|------------|
| FixMyStreet     | Vatandaşların altyapı sorunlarını bildirmesini sağlayan platform | Yol, kaldırım, park sorunları | ⭐⭐⭐⭐⭐ | [Web Sitesi](https://www.fixmystreet.com/) |

## Sanallaştırma Ortamları

| Proje / Yazılım  | Açıklama                                      | Kullanım Alanları                                  | Puanlama   | Kaynak     |
|------------------|-----------------------------------------------|----------------------------------------------------|------------|------------|
|       |                         |          |  |  |
|          |              |           | |  |

## Web Browsers

| Proje / Yazılım  | Açıklama                                      | Kullanım Alanları                                  | Puanlama   | Kaynak     |
|------------------|-----------------------------------------------|----------------------------------------------------|------------|------------|
| Brave            | Açık kaynaklı, Chromium tabanlı, hız ve gizliliğe önem veren tarayıcı | Hız, gizlilik, güvenlik                            | ⭐⭐⭐⭐ | [Web Sitesi](https://brave.com/) |
| Chromium         | Google tarafından başlatılan açık kaynaklı web tarayıcısı projesi | Çeşitli platformlarda tarayıcı geliştirmek için temel | ⭐⭐⭐⭐ | [Web Sitesi](https://www.chromium.org/) |
| Falkon           | Qt Framework kullanan, hafif ve çok platformlu web tarayıcısı | Hafiflik, çok platform desteği, QtWebEngine motoru  | ⭐⭐⭐ | [Web Sitesi](https://invent.kde.org/network/falkon/) |
| Midori           | WebKit motorunu kullanan hafif bir tarayıcı    | Hafiflik, WebKit motoru kullanımı, kolay katkı sağlama | ⭐⭐⭐ | [Web Sitesi](http://www.midori-browser.org/) |
| Mozilla Firefox  | Mozilla Vakfı tarafından geliştirilen web tarayıcısı | Açık kaynak, geniş eklenti desteği, güvenlik        | ⭐⭐⭐⭐ | [Web Sitesi](https://www.mozilla.org/en-US/firefox/new/) |
| NetSurf          | Kendi düzen motorunu kullanan web tarayıcısı  | Düşük kaynak tüketimi, özelleştirme olanağı         | ⭐⭐⭐ | [Web Sitesi](http://www.netsurf-browser.org) |
| PaleMoon         | Özelleştirilebilirlik odaklı bir web tarayıcısı | Özelleştirme, kullanıcı deneyimi, topluluk desteği | ⭐⭐⭐ | [Web Sitesi](https://www.palemoon.org/) |
| qutebrowser      | Klavye odaklı, minimal bir kullanıcı arayüzüne sahip tarayıcı | Klavye kısayolları, minimal arayüz, hızlı gezinme   | ⭐⭐⭐ | [Web Sitesi](https://qutebrowser.org/) |
| SeaMonkey        | İnternet paketi sunan bir tarayıcı-suit yazılımı | E-posta istemcisi, HTML düzenleyici, haber okuyucu  | ⭐⭐⭐ | [Web Sitesi](https://www.seamonkey-project.org/) |
| Tor Browser      | Tor Projesi tarafından geliştirilen, güvenlik ve gizlilik odaklı bir tarayıcı | Gizlilik, anonimlik, güvenlik                      | ⭐⭐⭐⭐ | [Web Sitesi](https://www.torproject.org/projects/torbrowser.html) |


## Parola Yöneticisi


| Proje / Yazılım  | Açıklama                                      | Kullanım Alanları                                  | Puanlama   | Kaynak     |
|------------------|-----------------------------------------------|----------------------------------------------------|------------|------------|
| Bitwarden        | Parola yöneticisi                             | Parola yönetimi                                   |            | [Web Sitesi](https://bitwarden.com/) |
| KeePass          | Parola yöneticisi                             | Parola yönetimi                                   |            | [Web Sitesi](http://keepass.info) |
| KeeWeb           | KeePass ile uyumlu, çok platformlu parola yöneticisi | Parola yönetimi, KeePass uyumluluğu            |            | [Web Sitesi](https://keeweb.info/) |
| Password Safe    | Parola yöneticisi                             | Parola yönetimi                                   |            | [Web Sitesi](https://pwsafe.org/) |
| Pass             | Standart Unix Parola Yöneticisi               | Parola yönetimi                                   |            | [Web Sitesi](https://www.passwordstore.org/) |


## OS/Distributions

| Proje / Yazılım  | Açıklama                                      | Kullanım Alanları                                  | Puanlama   | Kaynak     |
|------------------|-----------------------------------------------|----------------------------------------------------|------------|------------|
| Android-X86      | AMD ve Intel x86 işlemcili cihazlarda çalışmak üzere Google'ın Android mobil işletim sistemini taşımak için yapılan bir girişim | Mobil işletim sistemi                            |            | [Web Sitesi](http://www.android-x86.org/) |
| Arch Linux       | Hafif ve esnek bir Linux dağıtımı            | Genel amaçlı Linux dağıtımı                        |            | [Web Sitesi](https://www.archlinux.org) |
| CentOS           | Ücretsiz, kurumsal sınıf, topluluk destekli bir hesaplama platformu | Kurumsal bilgi işlemi                              |            | [Web Sitesi](https://centos.org/) |
| Debian           | Tamamen özgür yazılımdan oluşan bir Unix benzeri bilgisayar işletim sistemi | Genel amaçlı bilgisayar işletim sistemi           |            | [Web Sitesi](https://www.debian.org/) |
| Fedora           | Topluluk tarafından desteklenen Fedora Projesi tarafından geliştirilen bir Linux dağıtımı | Genel amaçlı Linux dağıtımı                      |            | [Web Sitesi](https://fedoraproject.org/) |
| FreeBSD          | BSD kökenli, ücretsiz ve açık kaynaklı Unix benzeri işletim sistemi | Genel amaçlı Unix benzeri işletim sistemi        |            | [Web Sitesi](https://www.freebsd.org) |
| Kubuntu          | Ubuntu işletim sisteminin resmi bir çeşidi olan ve KDE Plasma Masaüstü'nü kullanan bir Linux dağıtımı | Genel amaçlı Linux dağıtımı                      |            | [Web Sitesi](https://www.kubuntu.org/) |
| LineageOS        | Popüler CyanogenMod ROM'unun halefi            | Android ROM, özelleştirme                         |            | [Web Sitesi](https://www.lineageos.org/) |
| Linux            | Linus Torvalds tarafından yayınlanan bir işletim sistemi çekirdeği | İşletim sistemi çekirdeği                        |            | [Web Sitesi](https://github.com/torvalds/linux) |
| Linux Mint       | Debian ve Ubuntu'ya dayalı bir topluluk destekli Linux dağıtımı | Genel amaçlı Linux dağıtımı                      |            | [Web Sitesi](https://www.linuxmint.com/) |
| NixOS            | Saf fonksiyonel Linux Dağıtımı                 | Genel amaçlı Linux dağıtımı                      |            | [Web Sitesi](https://nixos.org/) |
| OpenBSD          | Berkeley Yazılım Dağıtımı üzerinden Berkeley Yazılım Dağıtımı'na kadar uzanan Unix benzeri bir bilgisayar işletim sistemi | Güvenlik odaklı Unix benzeri işletim sistemi     |            | [Web Sitesi](www.openbsd.org) |
| openSUSE         | SUSE Linux GmbH ve diğer şirketler tarafından desteklenen bir Linux tabanlı proje ve dağıtım | Genel amaçlı Linux dağıtımı                      |            | [Web Sitesi](https://opensuse.org/) |
| postmarketOS     | Android Telefonlar İçin LTS Linux Tabanlı Bir İşletim Sistemi | Android telefonlar için işletim sistemi           |            | [Web Sitesi](https://www.android-x86.org/) |
| SerenityOS       | SerenityOS, '90'ların kullanıcı arayüzlerine bir aşk mektubu ve özel bir Unix benzeri çekirdek ile tasarlanmıştır | İşletim sistemi                                  |            | [Web Sitesi](https://serenityos.org/) |
| Slackware        | Güç ve kararlılık odaklı en eski bakımlı Linux dağıtımı | Genel amaçlı Linux dağıtımı                      |            | [Web Sitesi](http://www.slackware.com/) |
| Ubuntu Linux     | Debian mimarisine dayalı bir Linux dağıtımı    | Genel amaçlı Linux dağıtımı                      |            | [Web Sitesi](https://www.ubuntu.com/) |
| Xubuntu          | Ubuntu işletim sisteminin resmi bir çeşidi olan ve XFCE masaüstü ortamını kullanan bir Linux dağıtımı | Genel amaçlı Linux dağıtımı                      |            | [Web Sitesi](https://xubuntu.org/) |


## Network

| Proje / Yazılım  | Açıklama                                      | Kullanım Alanları                                  | Puanlama   | Kaynak     |
|------------------|-----------------------------------------------|----------------------------------------------------|------------|------------|
| Apache           | Çok platformlu web sunucusu yazılımı           | Web sunucuları                                    |            | [Web Sitesi](https://httpd.apache.org/) |
| Firezone         | Kendi barındırmalı WireGuard® tabanlı VPN Sunucusu & Güvenlik Duvarı | VPN sunucusu ve güvenlik duvarı                   |            | [GitHub](https://github.com/firezone/firezone) |
| FreeNAS          | Ağa Bağlı Depolama yazılımı                   | Ağa bağlı depolama                               |            | [Web Sitesi](https://www.freenas.org/) |
| Let's Encrypt    | Ücretsiz, otomatik ve açık bir Sertifika Otoritesi | SSL/TLS sertifikaları                            |            | [Web Sitesi](https://letsencrypt.org/) |
| NAPALM           | NAPALM (Çok satıcılı destek ile Ağ Otomasyonu ve Programlanabilirlik Soyutlama Katmanı) | Ağ otomasyonu ve programlanabilirlik             |            | [GitHub](https://github.com/napalm-automation/napalm) |
| Nextcloud        | Kendi barındırmalı dosya senkronizasyonu ve paylaşımı ve iletişim uygulama platformu | Dosya senkronizasyonu ve paylaşımı               |            | [Web Sitesi](https://nextcloud.com/) |
| Nginx            | HTTP ve posta proxy sunucusu                   | HTTP proxy sunucusu                               |            | [Web Sitesi](https://nginx.org/) |
| Nmap             | Güvenlik Tarayıcısı, Port Tarayıcısı ve Ağ Keşif Aracı | Ağ güvenliği                                     |            | [Web Sitesi](https://nmap.org/) |
| OpenNIC          | Kullanıcı tarafından sahip olunan ve kontrol edilen Ağ Bilgi Merkezi; alternatif DNS ağı | Alternatif DNS ağı                               |            | [Web Sitesi](https://www.opennic.org/) |
| OpenSSH          | Güvenli Kabuk protokolüne dayalı bir dizi güvenlikle ilgili ağ düzeyi yardımcı programı | Güvenlikle ilgili ağ yardımcı programları         |            | [Web Sitesi](https://www.openssh.com/) |
| OpenWRT          | Gömülü Linux tabanlı proje, öncelikle gömülü cihazlarda ağ trafiğini yönlendirmek için kullanılır | Gömülü cihazlarda ağ yönlendirme işletim sistemi  |            | [Web Sitesi](https://www.openwrt.org/) |
| OPNsense         | Kolay kullanımlı, kolay yapılabilen FreeBSD tabanlı bir güvenlik duvarı ve yönlendirme platformu | Güvenlik duvarı ve yönlendirme platformu         |            | [Web Sitesi](https://opnsense.org/) |
| ownCloud         | Kendi barındırmalı dosya senkronizasyonu ve paylaşımı uygulama platformu | Dosya senkronizasyonu ve paylaşımı               |            | [Web Sitesi](https://owncloud.org/) |
| pfSense          | Web arayüzü aracılığıyla tamamen yönetilen bir güvenlik duvarı ve yönlendirme platformu olarak özel olarak tasarlanmış FreeBSD'nin ücretsiz, açık kaynaklı özelleştirilmiş bir dağıtımı | Güvenlik duvarı ve yönlendirme platformu         |            | [Web Sitesi](https://www.pfsense.org/) |
| Remmina          | Özellik açısından zengin Uzak Masaüstü Uygulaması | Uzak Masaüstü                                   |            | [Web Sitesi](https://www.remmina.org/) |
| sshuttle         | VPN olarak bir yoksul adamın proxy sunucusu olarak çalışan şeffaf bir proxy sunucusu | VPN alternatifi                                  |            | [GitHub](https://github.com/sshuttle/sshuttle) |
| Syncthing        | Eşler arası dosya senkronizasyonu              | Dosya senkronizasyonu                            |            | [Web Sitesi](https://syncthing.net/) |
| Tribler          | P2P içerik keşfi ile gizlilik geliştirilmiş BitTorrent istemcisi | BitTorrent istemcisi                             |            | [Web Sitesi](https://www.tribler.org/) |
| WireGuard        | Hızlı, modern ve güvenli VPN tüneli            | VPN tüneli                                      |            | [Web Sitesi](https://www.wireguard.com/) |
| Wireshark        | Paket analizörü                                | Ağ analizi                                       |            | [Web Sitesi](https://www.wireshark.org/) |


## FTP client 


| Proje / Yazılım       | Açıklama                                                   | Kullanım Alanları                         | Puanlama | Kaynak                                      |
|-----------------------|------------------------------------------------------------|-------------------------------------------|----------|---------------------------------------------|
| Cyberduck             | FTP ve SFTP, WebDAV ve bulut depolama için istemci        | Dosya aktarımı, bulut depolama          |          | [Web Sitesi](https://cyberduck.io)           |
| FileZilla             | Platformlar arası FTP uygulaması                           | Dosya aktarımı, FTP yönetimi            |          | [Web Sitesi](https://filezilla-project.org/) |
| WinSCP                | Microsoft Windows için SFTP, FTP, WebDAV ve SCP istemcisi   | Dosya aktarımı, güvenli dosya paylaşımı |          | [Web Sitesi](https://winscp.net/eng/index.php) |

## Mail

| Proje / Yazılım | Açıklama                                           | Kullanım Alanları                    | Puanlama | Kaynak                                   |
|-----------------|----------------------------------------------------|--------------------------------------|----------|------------------------------------------|
| Dovecot         | Linux/UNIX benzeri sistemler için IMAP ve POP3 e-posta sunucusu | E-posta sunucusu                   |          | [Web Sitesi](https://dovecot.org/)        |
| Mail-in-a-box   | Tek tıklamayla kolayca dağıtılabilir SMTP+diğer her şey sunucusu | E-posta sunucusu                   |          | [Web Sitesi](https://mailinabox.email/)   |
| Mailcow         | 'moo' ile e-posta sunucusu paketi – 🐮 + 🐋 = 💕     | E-posta sunucusu                   |          | [Web Sitesi](https://mailcow.email/)       |
| Mailu           | Docker görüntüleri kümesi olarak basit ancak tam özellikli e-posta sunucusu | E-posta sunucusu                   |          | [Web Sitesi](https://mailu.io/)            |
| Mutt            | Unix işletim sistemleri için metin tabanlı posta istemcisi | E-posta istemcisi                  |          | [Web Sitesi](http://www.mutt.org/)         |
| NeoMutt         | Komut satırı posta okuyucu                       | E-posta istemcisi                  |          | [Web Sitesi](https://www.neomutt.org/)     |

## Geliştirici

| Proje / Yazılım | Açıklama                                           | Kullanım Alanları                    | Puanlama | Kaynak                                    |
|-----------------|----------------------------------------------------|--------------------------------------|----------|------------------------------------------|
| Ansible         | Radikal basit IT otomasyon platformu             | Otomasyon                           |          | [Web Sitesi](https://www.ansible.com/)    |
| ConEmu          | Windows için ücretsiz ve açık kaynaklı sekme tabanlı terminal emülatörü | Terminal emülatörü               |          | [Web Sitesi](https://conemu.github.io/)   |
| Daytona         | Açık Kaynaklı Geliştirme Ortamı Yöneticisi       | Geliştirme ortamı yönetimi         |          | [Web Sitesi](https://www.daytona.io/)     |
| DEM             | Gömülü Geliştirme için Konteynerleştirilmiş Geliştirme Ortamı Yöneticisi | Geliştirme ortamı yönetimi         |          | [Web Sitesi](https://github.com/axem-solutions/dem) |
| Ddosify         | Dağıtılmış Performans Testi Platformu            | Performans testi                   |          | [Web Sitesi](https://github.com/ddosify/ddosify) |
| Flutter         | iOS ve Android için modern mobil uygulamalar oluşturmak için mobil uygulama SDK'sı | Mobil uygulama geliştirme          |          | [Web Sitesi](https://flutter.io/)         |
| Fossil          | Basit, yüksek güvenilirlikli, dağıtılmış yazılım yapılandırma yönetim sistemi | Yazılım yapılandırma yönetimi     |          | [Web Sitesi](https://www.fossil-scm.org/) |
| Genezio CLI     | Web sitenizi [genez.io](https://genez.io)'nun sunucu hizmeti altyapısına ücretsiz olarak dağıtmanıza yardımcı olan bir komut satırı aracı. | Web sunucusu yönetimi              |          | [Web Sitesi](https://genez.io)            |
| Git             | Dağıtılmış sürüm kontrol sistemi                  | Sürüm kontrolü                     |          | [Web Sitesi](https://git-scm.com/)        |
| GitLab          | Wiki ve hata takibi özelliklerine sahip web tabanlı Git depo yöneticisi | Depo yönetimi                      |          | [Web Sitesi](https://gitlab.com)         |
| Hook0           | Yazılım Geliştiricileri için Webhooks hizmeti     | Yazılım geliştirme                  |          | [Web Sitesi](https://www.hook0.com/)      |
| Mosh            | Roaming, kesintili bağlantı desteği ve kullanıcı tuş vuruşlarının akıllı yerel yinelemesi ve satır düzenlemesi sağlayan uzak terminal uygulaması | Uzak terminal uygulaması            |          | [Web Sitesi](https://mosh.org/)          |
| Node-RED        | Donanım cihazları, API'ler ve çevrimiçi hizmetleri yeni ve ilginç yollarla birleştirmek için programlama aracı | Donanım ve yazılım entegrasyonu    |          | [Web Sitesi](https://nodered.org/)       |
| Pixeleye        | UI hatalarını yakalamak için görsel inceleme ve test platformu | QA/Test                             |          | [Web Sitesi](https://pixeleye.io/home/)  |
| PuTTY           | Ücretsiz ve açık kaynaklı terminal emülatörü       | Terminal emülatörü                 |          | [Web Sitesi](https://www.chiark.greenend.org.uk/~sgtatham/putty/) |
| Rancher         | Tam konteyner yönetim platformu                    | Konteyner yönetimi                  |          | [Web Sitesi](https://rancher.com/)        |
| Refine          | CRUD uygulamaları oluşturmak için açık kaynaklı bir React tabanlı çerçeve | Web uygulama geliştirme            |          | [Web Sitesi](https://refine.dev)          |
| Taipy           | Web uygulamalarının GUI ve backend yönetimi için açık kaynaklı Python kütüphanesi | Web uygulama geliştirme            |          | [Web Sitesi](https://www.taipy.io)       |
| Tolgee          | Geliştirici ve çevirmen dostu yerelleştirme platformu | Yazılım geliştirme                  |          | [Web Sitesi](https://tolgee.io)           |
| VirtualBox      | Ücretsiz ve açık kaynaklı hipervizör               | Hipervizör                          |          | [Web Sitesi](https://www.virtualbox.org/) |
| Windows Terminal| Subsystem/WSL ve daha fazlası ile çalışan sekme tarzı Windows komut satırı / kabuk aracı. Entegre .json dosyası aracılığıyla özelleştirilmiş görünüm | Terminal emülatörü                 |          | [Web Sitesi](https://apps.microsoft.com/store/detail/windows-terminal/9N0DX20HK701?hl=de-de&gl=DE) |
| Yaade           | Açık kaynaklı, kendi barındıran, işbirlikçi API geliştirme ortamı | API geliştirme ortamı              |          | [Web Sitesi](https://docs.yaade.io/)      |
| Revert          | B2B ürün entegrasyonları oluşturmak için açık kaynaklı birleşik API | Yazılım geliştirme                  |          | [Web Sitesi](https://revert.dev/)         |
| Panora          | SaaS'ınıza bir entegrasyon kataloğu ekleyin. Merge.dev alternatifi - Dakikalar içinde, aylar değil | Entegrasyon yönetimi               |          | [Web Sitesi](https://panora.dev)          |






## Video

| Proje / Yazılım          | Açıklama                                                                        | Kullanım Alanları                                  | Puanlama   | Kaynak     |
|--------------------------|---------------------------------------------------------------------------------|----------------------------------------------------|------------|------------|
| Avidemux                 | Video düzenleme ve işleme için tasarlanmış bir video düzenleme programı         | Video düzenleme, video işleme                     |             | [Web Sitesi](http://fixounet.free.fr/avidemux/) |
| HandBrake                | GPL lisanslı, çok platformlu, çok iş parçacıklı bir video dönüştürücü          | Video dönüştürme, video transkodlama              |             | [Web Sitesi](https://handbrake.fr/) |
| KdenLive                 | MLT Framework, KDE ve Qt'ye dayalı bir video düzenleme yazılımı                  | Video düzenleme                                   |             | [Web Sitesi](https://kdenlive.org/) |
| Open Broadcaster Software| OBS Projesi tarafından sürdürülen yayın ve kayıt programı                        | Yayın, kayıt                                      |             | [Web Sitesi](https://obsproject.com/) |
| OpenShot Video Editor    | FreeBSD, Linux, macOS ve Windows için bir video düzenleyici                      | Video düzenleme                                   |             | [Web Sitesi](https://www.openshot.org/) |
| Shotcut                  | Ücretsiz, açık kaynak, çok platformlu bir video düzenleyici                      | Video düzenleme                                   |             | [Web Sitesi](https://shotcut.org/) |
| VirtualDub               | Basit düzenleme ve kodlama için ücretsiz bir video aracı, özellikle AVI dosyaları için | Video düzenleme, video işleme                    |             | [Web Sitesi](http://virtualdub.org/) |

## Text Editor

| Proje / Yazılım  | Açıklama                                      | Kullanım Alanları                                  | Puanlama   | Kaynak     |
|------------------|-----------------------------------------------|----------------------------------------------------|------------|------------|
| Atom             | 21. yüzyıl için yapılandırılabilir bir metin düzenleyicisi, Electron üzerine inşa edilmiş | Yapılandırılabilirlik, çok platformlu              |            | [Web Sitesi](https://atom.io/) |
| Code::Blocks     | GCC, Clang ve Visual C++ dahil olmak üzere çeşitli derleyicileri destekleyen çok platformlu bir IDE | Çoklu derleyici desteği, çapraz platform           |            | [Web Sitesi](http://www.codeblocks.org/) |
| Emacs (GNU)      | Genişletilebilir, özelleştirilebilir, kendi kendini belgeleyen gerçek zamanlı görüntü düzenleyici | Genişletilebilirlik, özelleştirilebilirlik, gerçek zamanlı görüntüleme | | [Web Sitesi](https://www.gnu.org/software/emacs/) |
| Kate Editor      | KDE özgür yazılım topluluğu tarafından geliştirilen bir metin düzenleyici | KDE topluluğu, çok platformlu                      |            | [Web Sitesi](https://kate-editor.org/) |
| Nano             | Unix benzeri hesaplama sistemleri veya işletim ortamları için bir metin düzenleyici | Komut satırı arayüzü, Unix benzeri işletim sistemleri | | [Web Sitesi](https://www.nano-editor.org/) |
| Notepad++        | Birçok dil desteği sağlayan bir not defteri değiştirici | Çoklu dil desteği, hafif                          |            | [Web Sitesi](http://www.notepad-plus-plus.org/) |
| Treehouse        | Tarayıcıda veya kendi özel uygulamanızı oluşturmak için kullanabileceğiniz hafif bir dış çizim uygulaması | Hafif, dış çizim                                   |            | [GitHub](https://github.com/treehousedev/treehouse) |
| Vim              | Eski UNIX düzenleyicisi Vi'nin büyük ölçüde geliştirilmiş bir sürümü | Klavye odaklı, genişletilebilirlik, hızlı metin işleme | | [Web Sitesi](http://www.vim.org/sponsor/index.php) |
| Visual Studio Code | Modern web ve bulut uygulamaları oluşturmak ve hata ayıklamak için yeniden tanımlanan ve optimize edilmiş bir kod düzenleyici | Modern web uygulamaları, bulut uygulamaları, hata ayıklama | | [Web Sitesi](https://code.visualstudio.com/) |


## Grafik

| Proje / Yazılım       | Açıklama                                                   | Kullanım Alanları                         | Puanlama | Kaynak                                      |
|-----------------------|------------------------------------------------------------|-------------------------------------------|----------|---------------------------------------------|
| Auto 1111 SDK         | Resimleri düzenlemek ve oluşturmak için SDK               | Resim düzenleme                           |          | [GitHub](https://github.com/saketh12/Auto1111SDK) |
| Blender               | 3D Oluşturma Yazılımı                                      | 3D tasarım, modelleme                    |          | [Web Sitesi](https://blender.org/)           |
| Caesium Image Compressor | Fotoğraflar ve görüntüler için gelişmiş sıkıştırma aracı (JPG, PNG, GIF) | Resim sıkıştırma                       |          | [Web Sitesi](https://saerasoft.com/caesium/) |
| FreeCAD               | Genel amaçlı parametrik 3D CAD modelleyici                   | 3D modelleme                             |          | [Web Sitesi](https://www.freecadweb.org/)    |
| GIMP                  | Resim düzenleme ve retuş, serbest çizim, farklı resim formatları arasında dönüştürme ve daha spesifik görevler için kullanılan raster grafik düzenleyicisi | Raster grafik düzenleme, resim retuş     |          | [Web Sitesi](https://www.gimp.org/)          |
| ImageMagick           | Raster ve vektör görüntü dosyalarını görüntüleme, dönüştürme ve düzenleme için yazılım paketi | Görüntü dönüştürme, düzenleme           |          | [Web Sitesi](https://imagemagick.org/)       |
| Inkscape              | Vektör grafik düzenleyici                                  | Vektör grafik düzenleme                  |          | [Web Sitesi](https://inkscape.org/)         |
| Krita                 | Raster grafik düzenleyici, öncelikle dijital boyama ve animasyon amaçları için tasarlanmıştır | Dijital boyama, animasyon oluşturma      |          | [Web Sitesi](https://krita.org/)            |
| LibreCAD              | 2B tasarım için bilgisayar destekli tasarım uygulaması     | 2B tasarım                               |          | [Web Sitesi](http://librecad.org/)          |
| Pinta                 | Çizim ve resim düzenleme programı                           | Çizim, resim düzenleme                   |          | [Web Sitesi](https://pinta-project.com/)    |


## Social

| Proje / Yazılım  | Açıklama                                      | Kullanım Alanları                                  | Puanlama   | Kaynak     |
|------------------|-----------------------------------------------|----------------------------------------------------|------------|------------|
| Mastodon         | Sosyal ağ sunucusu                            | Sosyal ağ                                         |            | [Web Sitesi](https://joinmastodon.org/) |
| Matrix           | Güvenli, merkezi olmayan iletişim için açık ağ | Güvenli iletişim, merkezi olmayan ağ               |            | [Web Sitesi](https://matrix.org/) |
| Pidgin           | Evrensel anlık iletişim (IM) programı         | Anlık iletişim, çok protokol desteği               |            | [Web Sitesi](https://pidgin.im/) |
| HexChat          | XChat tabanlı IRC istemcisi                  | IRC istemcisi, çok platformlu                      |            | [Web Sitesi](https://hexchat.github.io/) |
| Rocket.Chat      | En üst düzey web sohbet platformu            | Web sohbet, işbirliği araçları                     |            | [Web Sitesi](https://rocket.chat/) |
| Talk             | Disqus'a alternatif                           | Yorum sistemi                                     |            | [Web Sitesi](https://coralproject.net/) |
| WeeChat          | Hızlı, hafif ve genişletilebilir sohbet istemcisi | Sohbet istemcisi, genişletilebilirlik             |            | [Web Sitesi](https://weechat.org/) |











