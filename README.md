# TransactApp

Gestión de finanzas personales y control de inventario de efectivo.

## Instalación

### Opción 1: Instalador en línea (Recomendado)
1. Abre **Microsoft Edge**
2. Haz clic en **"Instalar ahora"** (transactapp.application)
3. Ejecuta el archivo descargado cuando el navegador lo permita

### Opción 2: Instalador offline
1. Descarga **setup.exe**
2. Ejecuta el instalador
3. **Nota:** Si el antivirus bloquea la instalación, desactívalo temporalmente y vuelve a intentar

### Requisitos del sistema
- Windows 7 o superior
- Conexión a internet (para la primera instalación)
- Al menos 100 MB de espacio en disco

## Características

- **Gestión de finanzas personales**: Controla tus ingresos y gastos
- **Inventario de efectivo**: Administra el dinero en efectivo disponible
- **Registro de transacciones**: Historial completo de todas las operaciones

## Uso

1. Después de la instalación, busca **TransactApp** en el menú Inicio
2. La aplicación guardará todos tus datos en una base de datos SQLite local
3. Los datos se almacenan en: `%APPDATA%\TransactApp\` (Windows)

## Version

1.0.2.5

## Estructura de archivos

```
TransactApp-Deploy/
├── setup.exe              # Instalador offline
├── TransactApp.application # Manifiesto ClickOnce
├── index.html             # Página de descarga
├── README.md              # Este archivo
└── Application Files/     # Archivos de la aplicación
    └── TransactApp_1_0_2_4/
        ├── TransactApp.exe
        ├── TransactApp.dll
        └── runtimes/      # Librerías nativas (SQLite)
```

## Solución de problemas

- **Error al abrir**: Desactiva el antivirus temporalmente
- **No conecta a internet**: Verifica tu conexión o usa setup.exe offline
- **Datos corruptos**: Elimina la carpeta en `%APPDATA%\TransactApp\` y reinicia la app

---

# TransactApp

Personal finance management and cash inventory control.

## Installation

### Option 1: Online Installer (Recommended)
1. Open **Microsoft Edge**
2. Click **"Install now"** (transactapp.application)
3. Run the downloaded file when prompted by the browser

### Option 2: Offline Installer
1. Download **setup.exe**
2. Run the installer
3. **Note:** If antivirus blocks the installation, temporarily disable it and try again

### System Requirements
- Windows 7 or higher
- Internet connection (for first installation)
- At least 100 MB of disk space

## Features

- **Personal finance management**: Track your income and expenses
- **Cash inventory**: Manage available cash
- **Transaction logging**: Complete history of all operations

## Usage

1. After installation, search for **TransactApp** in the Start menu
2. The application saves all data to a local SQLite database
3. Data is stored in: `%APPDATA%\TransactApp\` (Windows)

## Version

1.0.2.5

## File Structure

```
TransactApp-Deploy/
├── setup.exe              # Offline installer
├── TransactApp.application # ClickOnce manifest
├── index.html             # Download page
├── README.md              # This file
└── Application Files/     # Application files
    └── TransactApp_1_0_2_4/
        ├── TransactApp.exe
        ├── TransactApp.dll
        └── runtimes/      # Native libraries (SQLite)
```

## Troubleshooting

- **Error opening**: Temporarily disable antivirus
- **No internet connection**: Check your connection or use offline setup.exe
- **Corrupted data**: Delete the folder at `%APPDATA%\TransactApp\` and restart the app
