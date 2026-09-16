â”‚   â”‚   â”œâ”€â”€ components/ # Componentes reutilizables (CalendarGrid, MonthYearHeader, etc.)
â”‚   â”‚   â”œâ”€â”€ dialogs/    # DiÃ¡logos (Settings, AssignByRange, PDFExport, DayAlert, etc.)
â”‚   â”‚   â”œâ”€â”€ screens/    # Pantallas principales (MainCalendarScreen, StatsAndAgendaScreen, DayDetailSheet)
â”‚   â”‚   â”œâ”€â”€ theme/      # Paletas ColorScheme M3, TipografÃ­a y Formas
â”‚   â”‚   â””â”€â”€ viewmodel/  # ShiftViewModel y estados de UI reactivos
â”‚   â”œâ”€â”€ util/           # Motores ShiftEngine, PdfExportHelper, IcsExportHelper, BackupManager, AppStrings (13 idiomas)
â”‚   â””â”€â”€ widget/         # AppWidgetProviders (Calendario Mensual, Hoy, PrÃ³ximos, Resumen)
â””â”€â”€ res/
    â”œâ”€â”€ drawable/       # Vectores grÃ¡ficos, iconos de lanzador e ilustraciones
    â”œâ”€â”€ layout/         # Layouts XML para Widgets de escritorio
    â””â”€â”€ values/         # Strings traducidos, temas y estilos
```

---

## ðŸš€ CompilaciÃ³n y EjecuciÃ³n

### Requisitos Previos

* **Android Studio:** Ladybug (2024.2.1) o superior.
* **JDK:** Java 17 o Java 21.
* **Android SDK:** Min SDK 24 (Android 7.0), Target/Compile SDK 35 (Android 15).

### Comandos Gradle

```bash
# Compilar APK de depuraciÃ³n
gradle assembleDebug

# Compilar APK de producciÃ³n
gradle assembleRelease

# Ejecutar tests unitarios locales
gradle :app:testDebugUnitTest
```

---

## ðŸ”’ Privacidad y Seguridad Local

* **Sin telemetrÃ­a externa:** No se recopilan ni envÃ­an datos analÃ­ticos, calendarios ni notas personales a servidores externos.
* **Persistencia local segura:** Los datos se almacenan exclusivamente en el almacenamiento privado de la aplicaciÃ³n mediante SQLite / Room.
* **Control total del usuario:** Copias de seguridad en formato JSON estÃ¡ndar para exportar o importar en cualquier momento.

---

## ðŸ“„ Fichas de PublicaciÃ³n en Play Store

Para consultar los textos oficiales, tÃ­tulos y metadatos ASO para Google Play Console, consulta [PLAY_STORE_METADATA.md](PLAY_STORE_METADATA.md).

---

## âš–ï¸ Licencia

Este proyecto estÃ¡ bajo los tÃ©rminos de la [Licencia MIT](LICENSE). 
