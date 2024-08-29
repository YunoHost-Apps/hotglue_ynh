<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Hotglue untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/hotglue.svg)](https://ci-apps.yunohost.org/ci/apps/hotglue/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/hotglue.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/hotglue.maintain.svg)

[![Pasang Hotglue dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=hotglue)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Hotglue secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Hotglue is a Content Manipulation Software that allows visual consistency between editing and viewing.
In order to start editing you need to add `__DOMAIN____PATH__/edit` to the end of the URL, eg https://hotglue.me/demo/edit

Checkout other Hotglue sites: https://hotglue.me/latest



**Versi terkirim:** 1.04~ynh1

**Demo:** <https://hotglue.me/demo/>

## Tangkapan Layar

![Tangkapan Layar pada Hotglue](./doc/screenshots/screenshot.jpg)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://hotglue.me>
- Dokumentasi pengguna resmi: <https://discourse.superglue.it/c/hotglue>
- Dokumentasi admin resmi: <https://discourse.superglue.it/c/hotglue>
- Depot kode aplikasi hulu: <https://github.com/k0a1a/hotglue2>
- Gudang YunoHost: <https://apps.yunohost.org/app/hotglue>
- Laporkan bug: <https://github.com/YunoHost-Apps/hotglue_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/hotglue_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/hotglue_ynh/tree/testing --debug
atau
sudo yunohost app upgrade hotglue -u https://github.com/YunoHost-Apps/hotglue_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
