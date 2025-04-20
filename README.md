# PiguinTV OS

Sistema operativo ligero para Raspberry Pi, TV Box y máquinas virtuales, ideal para streaming con control remoto Bluetooth.

## 🚀 Cómo usar

### 1. Generar imagen
```bash
chmod +x build-scripts/build.sh
./build-scripts/build.sh
```

### 2. Grabar en USB/SD
```bash
chmod +x build-scripts/flash.sh
./build-scripts/flash.sh /ruta/a/imagen.img
```

### 3. Iniciar en VirtualBox
- Crear VM tipo Linux (Debian 64bit o similar)
- Asignar la imagen generada como disco duro
- Iniciar

### 4. Emparejar control remoto
```bash
chmod +x tools/remotesupport/bluetooth_setup.sh
sudo tools/remotesupport/bluetooth_setup.sh
```

### 5. Probar servicios
- Netflix
- YouTube
- Control remoto
