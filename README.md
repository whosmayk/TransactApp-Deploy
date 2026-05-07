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

1. После instalación, busca **TransactApp** en el menú Inicio
2. La aplicación guardará todos tus datos en una base de datos SQLite local
3. Los datos se almacenan en: `%APPDATA%\TransactApp\` (Windows)

## Version

1.0.2.4

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