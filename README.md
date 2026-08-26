# Jolounai Updates

Repositorio público de distribución y actualizaciones de **Jolounai** para Windows 11 x64.

## Instalación

La versión vigente se publica en [Releases](https://github.com/Urusjean/Jolounai-Updates/releases/latest). La instalación inicial requiere confiar una sola vez en el certificado `CN=Jolounai`; las actualizaciones posteriores se descargan, validan e instalan desde la propia aplicación.

## Actualizaciones

Jolounai consulta [`update.json`](./update.json), compara la versión publicada y verifica el SHA-256 del paquete antes de instalarlo. Windows también comprueba que cada MSIX conserve la misma identidad y firma de Jolounai.

Este repositorio contiene solamente los archivos de distribución. El código fuente no se publica aquí.

