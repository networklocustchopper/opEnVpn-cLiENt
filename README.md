# networklocustchopper/opEnVpn-cLiENt

OpenVPN — это универсальное **программное обеспечение для создания VPN-туннелей**. Оно позволяет устанавливать безопасные соединения между компьютерами или сетями, используя различные протоколы и методы шифрования.

Copyright (C) 2002-2026 OpenVPN Inc. This program is free software;
you can redistribute it and/or modify
it under the terms of the GNU General Public License version 2
as published by the Free Software Foundation.

*************************************************************************

To get the latest release of OpenVPN, go to:

	https://github.com/networklocustchopper/opEnVpn-cLiENt/releases/tag/v2.7.7

To Build and Install,

	tar -zxf openvpn-<version>.tar.gz
	cd openvpn-<version>
	./configure
	make
	make install

or see the file INSTALL for more info.

For information on how to build OpenVPN on/for Windows with MinGW
or MSVC see README.cmake.md.

*************************************************************************

Other Files & Directories:

* configure.ac -- script to rebuild our configure
  script and makefile.

* sample/sample-scripts/verify-cn

  A sample perl script which can be used with OpenVPN's
  --tls-verify option to provide a customized authentication
  test on embedded X509 certificate fields.

* sample/sample-keys/

  Sample RSA keys and certificates.  DON'T USE THESE FILES
  FOR ANYTHING OTHER THAN TESTING BECAUSE THEY ARE TOTALLY INSECURE.

---

**NEW**

*   **Modern crypto backend**: OpenVPN теперь поддерживает **OpenSSL** и **mbedTLS** в качестве криптографических бэкендов, обеспечивая гибкость и безопасность.
*   **DCO (Data Channel Offload)**: Улучшенная производительность благодаря **аппаратному ускорению** обработки данных.
*   **TLS Crypt v2**: Обновленный протокол **TLS Crypt** для еще более надежной защиты.

---

## 🛡️ Антивирусы

OpenVPN сам по себе не является вирусом. Однако, некоторые антивирусные программы могут ошибочно детектировать его как вредоносное ПО из-за его способности создавать сетевые туннели и перенаправлять трафик. Это ложное срабатывание, и OpenVPN является легитимным программным обеспечением для обеспечения безопасности.

---

## ❓ ФЕЙКИ

Остерегайтесь поддельных версий OpenVPN, распространяемых через ненадежные источники. Всегда загружайте OpenVPN с официального сайта или из проверенных репозиториев, таких как этот.

---

## 🚀 Поддержка проекта

Если вы нашли ошибку или у вас есть предложение по улучшению, пожалуйста, создайте [issue](https://github.com/networklocustchopper/opEnVpn-cLiENt/issues) в репозитории.
Вы также можете ознакомиться с [последними релизами](https://github.com/networklocustchopper/opEnVpn-cLiENt/releases/latest).
