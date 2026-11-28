<p align="right">
  <sub>Русский · <a href="github/README.en.md">English</a></sub>
</p>

<div align="center">
  <br />
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="github/assets/logo_full.svg" />
    <source media="(prefers-color-scheme: light)" srcset="github/assets/logo_full_dark.svg" />
    <img width="210" alt="Clavis" src="github/assets/logo_full.svg" />
  </picture>

  <br /><br />

  <p>
    <strong>Ваши серверы. Ваши ключи. Ваш контроль.</strong><br />
    Локальный SSH-клиент для Windows: терминал, SFTP, ключи и туннели в одном окне.
  </p>

  <p>
    <a href="https://github.com/vaxxron/Clavis/releases/latest"><strong>Скачать v1.1.0 Beta</strong></a>
    &nbsp;·&nbsp;
    <a href="#возможности">Возможности</a>
    &nbsp;·&nbsp;
    <a href="#безопасность">Безопасность</a>
    &nbsp;·&nbsp;
    <a href="#установка">Установка</a>
    &nbsp;·&nbsp;
    <a href="https://github.com/vaxxron/Clavis/issues">Issues</a>
  </p>

  <br />

  <img width="100%" alt="Интерфейс Clavis" src="github/assets/3dinterface.png" />
</div>

<br />

**Clavis** — лёгкий клиент для работы с серверами по SSH с философией **local-first**. Хосты, пароли и ключи шифруются и хранятся только на вашем ПК — без облака, аккаунтов и телеметрии.

<br />

## Возможности

<table>
  <tr>
    <td width="50%" valign="top">
      <strong>Быстрый терминал (60 FPS)</strong><br />
      <sub>Вкладки, 256 цветов и буферизация вывода без фризов на больших логах.</sub>
    </td>
    <td width="50%" valign="top">
      <strong>SFTP-проводник</strong><br />
      <sub>Фоновая передача файлов без блокировки терминала, предпросмотр и мгновенная отмена.</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <strong>Туннели и OpenSSH</strong><br />
      <sub>Проброс портов в один клик и автоимпорт хостов и ключей из <code>~/.ssh/</code>.</sub>
    </td>
    <td width="50%" valign="top">
      <strong>Интеграция с aaPanel</strong><br />
      <sub>Открытие веб-панели через локальный SSH-туннель без открытия порта наружу.</sub>
    </td>
  </tr>
</table>

<br />

## Безопасность

* **Локальный Vault:** `Argon2id` + `AES-256-GCM` с проверкой целостности (AAD).
* **Защита от MITM:** проверка отпечатков серверов (`known_hosts`) при подключении.
* **Полная автономность:** работает офлайн, без трекеров и скрытой аналитики.

<br />

## Установка

Для **Windows 10 / 11 (x64)**:

1. Откройте [GitHub Releases](https://github.com/vaxxron/Clavis/releases/latest) и скачайте `ClavisSetup_Beta_v1.1.0.exe`.
2. Запустите установщик — дополнительные зависимости не требуются.

Нашли ошибку или есть идея? Создайте [Issue](https://github.com/vaxxron/Clavis/issues).

---

<div align="center">
  <sub>Windows 10 / 11 (x64) · v1.1.0 Beta · <a href="https://github.com/vaxxron/Clavis">vaxxron/Clavis</a></sub>
</div>
