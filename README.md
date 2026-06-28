# Ejercicio 1: Configuración de Entorno de Pruebas Controlado

Este repositorio contiene la configuración inicial de mi primer entorno de laboratorio seguro utilizando VirtualBox y Ubuntu Desktop.

## 1. Configuración de Red e Inmunidad
He configurado el adaptador de red de la máquina virtual en modo de **Red Interna**. 

**Justificación técnica:** Elegí este modo porque garantiza un aislamiento completo del sistema invitado (Guest). Al establecer una Red Interna, la máquina virtual no tiene acceso a Internet ni a mi red local, creando una "burbuja" segura para ejecutar pruebas sin riesgos. No utilicé el modo **Puente (Bridged)** porque este modo asigna a la máquina virtual una IP real de mi router, exponiendo todo el laboratorio de seguridad a mi red doméstica. Esto significaría un riesgo crítico para los dispositivos reales de mi hogar si se llega a manipular software malicioso o herramientas de escaneo.

---

## 2. Capturas de Pantalla (Evidencias)

### Configuración del Modo de Red
*(Aquí se evidencia el aislamiento en Red Interna)*
![Configuración de Red](Captura de pantalla 2026-06-28 105714)

### Administrador de Instantáneas (Snapshots)
*(Punto de restauración inicial del sistema)*
![Snapshot Base Limpia](Captura de pantalla 2026-06-28 144434)
