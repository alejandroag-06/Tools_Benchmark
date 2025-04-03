# 🖥️ Guía Rápida: Cómo Usar Speccy para Analizar tu PC

**Introducción**
**Speccy** es tu aliado perfecto para conocer los componentes de tu equipo. Esta aplicación muestra de forma clara y organizada toda la información relevante de tu hardware y sistema operativo. ¡Aprende a usarla en minutos!

---

## 📥 Instalar Speccy

<table>
  <tr>
    <td width="55%" style="border: none; padding: 10px">
      <h3>Método 1: Microsoft Store</h3>
      1. Abre la <strong>Microsoft Store</strong><br>
      2. Busca <em>Speccy</em><br>
      3. Haz clic en <strong>Instalar</strong>
    </td>
    <td width="45%" style="border: none; padding: 10px">
      <img src="imgs/speccy/mstore.png" width="750">
    </td>
  </tr>
</table>

---

<table>
  <tr>
    <td width="55%" style="border: none; padding: 10px">
      <h3>Método 2: Página Oficial</h3>
      1. Descarga desde: <a href="https://www.ccleaner.com/es-es/speccy/download">ccleaner.com/speccy</a> <br>
      2. Ejecuta el archivo <code>.exe</code>
    </td>
    <td width="45%" style="border: none; padding: 10px">
      <img src="imgs/speccy/speccy.png" width="750">
    </td>
  </tr>
</table>

## 🔍 Índice
1. [🚀 1.- Interfaz Principal de Speccy](#-interfaz-principal-de-speccy)  
2. [📂 2.- Sistema Operativo](#-sistema-operativo)  
3. [⚙️ 3.- CPU](#-cpu)  
4. [🧠 4.- RAM](#-ram)  
5. [🔌 5.- Placa Base](#-placa-base)  
6. [🎮 6.- Gráfica](#-gráfica)  
7. [💾 7.- Almacenamiento](#-almacenamiento)  
8. [📀 8.- Unidades Ópticas](#-unidades-ópticas)  
9. [🔊 9.- Audio](#-audio)  
10. [🖱️ 10.- Periféricos](#-periféricos)  
11. [🌐 11.- Red](#-red) 

---
<a id="-interfaz-principal-de-speccy"></a>

## 🚀 **1.- Interfaz Principal de Speccy**

Al abrir Speccy, verás una pantalla dividida en dos bloques clave:

### 📋 **Panel de Resumen (Sumario)**

Aquí se listan los componentes principales de tu PC. Cada ítem te da acceso rápido a detalles específicos:

- **Sistema operativo**: Versión y tipo de Windows instalado.
- **CPU**: Modelo y marca del procesador.
- **RAM**: Capacidad total de memoria.
- **Placa base**: Fabricante y modelo de la tarjeta madre.
- **Gráfica**: Tarjeta gráfica integrada o dedicada.
- **Almacenamiento**: Discos duros o SSD detectados.

### 🔍 **Panel de Detalles Técnicos**

Al seleccionar un componente del resumen, aquí se despliegan datos avanzados:

- **Monitor**: Resolución y frecuencia de refresco.
- **Audio**: Controladores y dispositivos de sonido.
- **Unidades ópticas**: Estado de lectores de CD/DVD.

✨ **Tip**: Usa el **menú lateral izquierdo** para saltar directamente a categorías como "Red" o "Periféricos".

---

![Imagen 1: Vista principal de Speccy con resumen y detalles técnicos](imgs/speccy/img1.png)

---
<a id="-sistema-operativo"></a>

# 📂 2.- Sistema Operativo

Esta sección centraliza información crítica sobre tu sistema y configuraciones clave. Te explicamos qué datos son más relevantes y cómo interpretarlos:


## 🔍 **Datos Principales**

### 1. **Información Básica**

- **Versión de Windows**: Ej: *Windows 11 Pro 64-bit*.
- **Tipo de ordenador**: Indica si es físico o virtual (*Virtual* en este caso).
- **Fecha de instalación**: Útil para identificar actualizaciones recientes o problemas posteriores.

### 2. **Seguridad**

- **Control de Cuentas (UAC)**: Nivel de notificaciones (*Por defecto*).
- **Cortafuegos y Antivirus**: Estado (*Activado*) y nombre del monitor (*Windows Defender*).
- **Actualizaciones de virus**: Verifica si la base de datos está *Actualizada*.

### 3. **Tiempo de Actividad**

- **Último arranque**: Fecha y hora del inicio del sistema.
- **Tiempo activo actual**: Duración desde el último reinicio (ej: *2 horas, 47 minutos*).

### 4. **Configuraciones Regionales**

- **Zona horaria**: GMT +1 (España).
- **Idioma y formato**: Español, fecha (*dd/MM/aaaa*), moneda (€).

---

![Imagen 1: Detalles del sistema operativo y seguridad](imgs/speccy/img2.png)
![Imagen 2: Configuraciones regionales y tiempo de actividad](imgs/speccy/img3.png)

---

## 💡 **¿Para qué sirve esta información?**

- **Diagnóstico rápido**: Verifica si el antivirus está activo o si hay problemas de actualizaciones.
- **Solución de errores**: El tiempo de actividad ayuda a identificar reinicios inesperados.
- **Compatibilidad**: Configuraciones regionales aseguran que programas muestren fechas, horas y monedas correctamente.

⚠️ **Nota**: Evita compartir datos sensibles como el *número de serie de Windows*.

---
<a id="-cpu"></a>

## ⚙️ 3.- Procesador (CPU)  
### ¿Qué información encontrarás aquí?  
Speccy detalla el rendimiento y capacidades de tu CPU. Así puedes interpretar los datos:  

<div style="display: flex; gap: 20px; flex-wrap: wrap">
  <div style="flex: 1; min-width: 250px">
  
  ### 📌 Especificaciones Clave  
  - **Modelo**: Intel Core i7-13620H (13ª Gen)  
  - **Núcleos/Hilos**: 10/16 → Ideal para streaming o edición.  
  - **Caché L3**: 24.5 MB (acelera tareas repetitivas).  

  ### 🔄 Rendimiento en Tiempo Real  
  - **Frecuencias**: ~2918 MHz (valores estables = buen funcionamiento).  
  - **Tecnologías**:  
    - *Hyperthreading*: Activo → Multitarea fluida.  
    - *AVX2/AES*: Soporte para cifrado y apps especializadas.  

  </div>
  <div style="flex: 1; min-width: 250px">
    <img src="imgs/speccy/img4.png" style="width: 100%; border-radius: 8px">
  </div>
</div>

💡 **Tip**: Si los núcleos están al 100% constantemente, cierra apps en segundo plano o actualiza tu CPU.

---
<a id="-ram"></a>

# 🧠 4.- RAM


Esta sección muestra información breve sobre la memoria. Aunque es breve, estos datos son clave:


## 📌 **Datos Esenciales**

- **RAM Total**: 16 GB (capacidad máxima de tu sistema).
- **En Uso**: 42% (ideal mantenerlo bajo 80% para buen rendimiento).
- **Disponible**: ~9 GB (memoria libre para nuevas tareas).

## 💡 **¿Cómo usarlo?**

- Si el **% en uso** supera 90%, cierra programas pesados.
- **Memoria virtual**: 17 GB total (espacio en disco usado como "RAM extra").

---

![Imagen: Estadísticas de RAM en Speccy](imgs/speccy/img5.png)

---

⚠️ **Nota**:

- *SPD no detectado*: Indica que Speccy no puede leer datos técnicos de los módulos de RAM (común en equipos virtuales o ciertas marcas).

---
<a id="-placa-base"></a>

# 🔌 5.- Placa Base


Esta sección muestra detalles técnicos de la placa base y sus conexiones:


## 📋 **Datos Clave**

- **Fabricante**: *LENOVO* (equipos preensamblados).
- **Modelo**: *LNVNB161216 (U3E1)* (identifica compatibilidad con componentes).
- **BIOS**: Versión *LTCN34WW* (actualizarlo puede mejorar estabilidad).

---

## 🛠️ **Ranuras PCI-E**

Speccy muestra todas las ranuras disponibles, aunque no siempre refleje su uso físico:

| Tipo de Ranura | Estado      | Observaciones |  
|----------------|-------------|---------------|  
| **PCI-E x1**   | *En uso*    | Posiblemente usada por dispositivos integrados (ej: Wi-Fi o tarjeta de red). |  
| **PCI-E x4**   | *Disponible*| Ideal para ampliar almacenamiento (ej: SSD NVMe) o tarjetas de bajo consumo. |  
| **PCI-E x1**   | *Disponible*| Libre para añadir hardware adicional (ej: tarjeta de sonido). |

---

![Imagen: Detalles de la placa base y ranuras PCI-E](imgs/speccy/img6.png)

---

💡 **Consejos Prácticos**:

1. Si quieres añadir una GPU u otro hardware, usa la ranura **PCI-E x4** (mayor ancho de banda).
2. Verifica el manual de tu placa base para confirmar límites de potencia y compatibilidad.

---
<a id="-gráfica"></a>

# 🎮 6.- Gráfica


Esta sección muestra información sobre tu pantalla y tarjeta gráfica:


## 🖥️ **Monitor**

- **Nombre**: Suele ser genérico (ej: *Generic PnP Monitor*) en portátiles o PCs preensamblados.
- **Resolución actual**: 1536x864 (ajustes activos del sistema).
- **Frecuencia de refresco**: 60 Hz (ideal para uso cotidiano).
- **Tamaño nativo**: 1920x1080 (resolución máxima recomendada).

---

## 🔧 **Tarjeta Gráfica Integrada**

- **Modelo**: *Intel UHD Graphics* (común en procesadores modernos).
- **Controlador**: Versión *32.0.101.5763* (actualízalo para mejor rendimiento).
- **Compatibilidad**: Soporta resoluciones HD/Full HD y tareas básicas de diseño.

---

![Imagen: Detalles de gráfica y monitor en Speccy](imgs/speccy/img7.png)

---

💡 **Consejos Prácticos**:

1. Si usas **juegos o software 3D**, verifica si tu GPU soporta DirectX/Vulkan en la sección "Instrucciones" de la CPU.
2. Un nombre genérico en el monitor **no indica problemas**; es normal en equipos con gráficos integrados.
3. Para pantallas externas, Speccy mostrará otro dispositivo en *\\\\.\DISPLAY2* (si está conectado).

---
<a id="-almacenamiento"></a>

# 💾 7.- Almacenamiento


Esta sección detalla la información técnica y cómo está distribuido el espacio en tu disco:


## 🖴 **Disco Principal**

- **Modelo**: *SOLIDIGM SSDPFINW010TZL* (SSD de 953 GB).
- **Interfaz**: *Desconocido* (común en equipos OEM; no afecta rendimiento).

---

## 📂 **Particiones y Sistemas de Archivos**

| Partición | Sistema de Archivos | Uso Principal |  
|-----------|---------------------|---------------|  
| **C:**    | NTFS                | Sistema operativo y programas (Windows). |  
| **FAT32** | FAT32               | Partición pequeña para recuperación o EFI. |

⚠️ **NTFS en Linux**:

- Linux puede **leer** NTFS, pero para **escribir** requiere herramientas como `ntfs-3g`.
- Para dual-boot, considera formatear en **exFAT** (compatible con Windows/Linux/macOS).

---

![Imagen: Detalles de almacenamiento en Speccy](imgs/speccy/img8.png)

---

💡 **Consejos Prácticos**:

1. **NTFS vs FAT32**:
   - NTFS: Ideal para Windows (soporta archivos >4 GB).
   - FAT32: Útil para memorias USB o compatibilidad universal.
2. La partición de **654 MB** (NTFS) suele ser reservada para actualizaciones del sistema.
3. *S.M.A.R.T no soportado*: No es crítico; herramientas como CrystalDiskInfo dan más detalles.

---
<a id="-unidades-ópticas"></a>

# 📀 8.- Unidades Ópticas


Esta sección detecta dispositivos como lectores de CD, DVD o Blu-Ray. Así funciona:


## 🛠️ **¿Qué verías si tuvieras una?**

- **Modelo**: Ej: *ASUS DRW-24B1ST*.
- **Tipo**: Lector/Grabadora (ej: DVD-RW).
- **Detalles**: Firmware, velocidad máxima de lectura/escritura.

---

![Imagen: Estado de unidades ópticas en Speccy](imgs/speccy/img9.png)

---

💡 **Nota**:

- Si no aparece nada, significa que tu PC no tiene unidad óptica física conectada (común en equipos modernos).

---
<a id="-audio"></a>

# 🔊 9.- Audio


Esta sección lista los dispositivos de sonido detectados por tu sistema. Así se interpreta:


## 🎧 **Datos Clave**

- **Tarjetas de sonido**:
  
  - *Realtek High Definition Audio*: Controlador principal para altavoces/auriculares.
  - *Intel Smart Sound Technology*: Gestiona audio Bluetooth (si hay dispositivos conectados).
- **Dispositivos activos**:
  
  - **Reproducción**: *Altavoces (Realtek Audio)* (salida de audio predeterminada).
  - **Grabación**: *Micrófonos (Realtek Audio)* (entrada de voz o sonido).

---

![Imagen: Configuración de audio en Speccy](imgs/speccy/img10.png)

---

💡 **Nota**:

- Si no aparecen dispositivos, verifica conexiones o reinstala controladores.

---
<a id="-periféricos"></a>

# 🖱️ 10.- Periféricos


Esta sección lista los dispositivos de entrada y salida detectados:

## ⌨️ **Teclado**

- **Teclado PS/2 estándar**: Suele ser el teclado integrado en portátiles (marcado como *Intel LPC Controller*).
- **Dispositivo HID**: Genérico (aparece incluso si no hay teclado externo conectado).

## 🖱️ **Mouse**

- **Mouse ELAN**: Táctil integrado en portátiles (controlador de precisión).
- **Mouse USB**: El físico conectado (*Proveedor: Unknown* es normal en dispositivos básicos).

---

![Imagen: Listado de periféricos en Speccy](imgs/speccy/img11.png)

---

💡 **Notas rápidas**:

1. **Impresoras virtuales**: *Microsoft Print to PDF* es una función del sistema, no requiere hardware físico.
2. Los dispositivos *HID* repetidos son controladores estándar de Windows.

---
<a id="-red"></a>

# 🌐 11.- Red

Esta sección muestra cómo tu PC se integra en la red local e internet. Te explicamos lo esencial:


## 📡 **Conexión Principal**

- **Tipo de adaptador**: *Realtek RTL8852BE WiFi 6* (tecnología de alta velocidad inalámbrica).
- **Configuración IP**:
  - *DHCP Activado*: Tu dirección IP y servidores DNS se asignan automáticamente.
  - *Puerta de enlace*: Dispositivo que gestiona el tráfico entre tu red e internet.

---

## 🖧 **Red Local**

- **Nombre del PC**: Identificador único en la red (ej: *DESKTOP-T9V2443*).
- **Grupo de trabajo**: *WORKGROUP* (configuración estándar para redes domésticas).
- **Recursos compartidos**: *No hay recursos compartidos* (seguridad básica por defecto).

---

## 🔄 **Conexiones Activas**

Speccy lista procesos que usan la red:

- **Navegadores**: *Chrome, Edge*.
- **Servicios del sistema**: *svchost.exe, lsass.exe*.
- **Aplicaciones de terceros**: *GitKraken, Ollama*.

---

![Imagen 1: Configuración de red y adaptadores](imgs/speccy/img12.png)
![Imagen 2: Conexiones TCP y recursos compartidos](imgs/speccy/img13.png)

---

💡 **Consejos Prácticos**:

1. **Wi-Fi 6**: Aprovecha velocidades altas si tu router lo soporta.
2. **Conexiones TCP**: Si ves procesos desconocidos, verifica su legitimidad para descartar malware.
3. **Evita compartir**: Direcciones IP, nombres de PC o rutas de archivos sensibles en foros públicos.

---

¡Felicidades! Tras terminar esta guia ya deberias entender como funciona Speccy 🎉

