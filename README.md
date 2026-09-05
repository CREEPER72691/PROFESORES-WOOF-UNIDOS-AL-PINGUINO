# Droidian

**Droidian** es una distribución Linux basada en Debian dirigida a dispositivos móviles. El objetivo del proyecto es transformar teléfonos y tabletas Android en sistemas Linux de escritorio móvil completamente funcionales, ofreciendo un entorno familiar, de código abierto y centrado en la privacidad.

## 🚀 Características Principales

* **Base Debian:** Utiliza los repositorios oficiales de Debian (usualmente la rama *Testing*), lo que garantiza acceso a miles de paquetes de software libre.
* **Arquitectura de Adaptación:** Emplea tecnologías como **Halium** y contenedores LXC para comunicarse con los controladores (drivers) de Android subyacentes, permitiendo que el hardware (Wi-Fi, Bluetooth, cámara) funcione sin recrear los drivers desde cero.
* **Interfaz de Usuario:** Por defecto utiliza **Phosh** (Phone Shell desarrollada por Purism) o **Plasma Mobile**, interfaces optimizadas para pantallas táctiles y pantallas pequeñas.
* **Convergencia:** Al conectar el dispositivo a un monitor, teclado y ratón, la interfaz se adapta para ofrecer una experiencia de escritorio Linux de escritorio completa.

## 🛠️ Requisitos del Sistema

Para instalar Droidian en un dispositivo, generalmente se requiere:
* Un dispositivo con el **bootloader desbloqueado**.
* Compatibilidad con **Halium** (usualmente dispositivos que venían de fábrica con Android 9 o superior).
* Un menú de recuperación personalizado instalado (como **TWRP** o **OrangeFox**).

## 📦 Instalación General

*Nota: Los pasos específicos pueden variar según el modelo exacto del dispositivo.*

1. **Descarga:** Obtén la imagen oficial correspondiente a tu dispositivo desde el sitio web de Droidian.
2. **Modo Recuperación:** Reinicia tu teléfono en modo de recuperación (Recovery).
3. **Limpieza:** Realiza una limpieza de fábrica (Wipe / Data Reset).
4. **Instalación:** Transfiere el archivo de Droidian al dispositivo y flashea el archivo `.zip` de instalación.
5. **Reinicio:** Reinicia el sistema y espera a que cargue la pantalla de bienvenida.

## 👥 Contribuciones y Comunidad

Droidian es un proyecto de código abierto impulsado por la comunidad. Puedes colaborar de las siguientes maneras:
* Reportando errores (Issues) en este repositorio.
* Ayudando a portar Droidian a nuevos dispositivos móviles.
* Traduciendo la interfaz o mejorando la documentación oficial.

## 📄 Licencia

Este proyecto se distribuye bajo los términos de la Licencia Pública General de GNU (GPL). Consulta el archivo `LICENSE` para más detalles.
