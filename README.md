# GhostARP

Una herramienta gráfica (GUI) desarrollada en Python para realizar ataques de ARP Spoofing y escaneo de red local. Diseñada con `tkinter` y utilizando `scapy`, esta aplicación permite visualizar dispositivos en la red y suplantar direcciones IP con facilidad.

## ✨ Características

- Escaneo de red LAN para descubrir dispositivos conectados
- Identificación del fabricante del dispositivo usando su MAC
- Interfaz gráfica simple e intuitiva
- Envío continuo de paquetes ARP spoofing
- Soporte para múltiples sistemas (Windows, Linux, MacOS)


## 🚀 Instalación

Clona el repositorio y navega a la carpeta del proyecto:

```bash
git clone https://github.com/CodeX-su/GhostARP/
cd nombre-del-repo
```

Instala las dependencias:

```bash
pip install -r requirements.txt
```

> En Linux, puede que necesites instalar tkinter:
>
> ```bash
> sudo apt install python3-tk
> ```

## ▶️ Uso

Ejecuta el script:

```bash
python script_mejorado.py
```

1. Pulsa en **"Escanear Red"** para ver los dispositivos conectados.
2. Selecciona un objetivo de la lista.
3. Pulsa **"Iniciar Spoofing"** para comenzar el ataque.

## 📦 Requisitos

- Python 3.7+
- `scapy`
- `mac-vendor-lookup`
- `tkinter` (normalmente incluido en instalaciones de Python)

## ⚠️ Advertencia Legal

Este software se proporciona con fines **educativos y de pruebas en entornos controlados**. No utilices esta herramienta en redes sin autorización explícita. El uso indebido puede ser **ilegal**.

## 📄 Licencia

Este proyecto está bajo la licencia MIT.
