# PowerSupplyGui — Альтернативное ПО для ATK-DP100

## Русский

Альтернативное приложение для управления программируемым блоком питания **Alientek ATK-DP100** (USB-C PD, 0-30V / 0-5A). Полностью совместимо с оригинальным протоколом HID-коммуникации.

### Оборудование

- Программируемый блок питания Alientek ATK-DP100 (USB-C Power Delivery, 0-30V, 0-5A)
- Компьютер с Windows (x64)
- Стандартный USB-C кабель

### Драйверы и настройка

Драйверы не требуются. Приложение использует библиотеку HidSharp для прямого доступа к USB HID-интерфейсу блока питания.

### Основные возможности (Преимущества по сравнению с оригинальным ПО)

- **Графики в реальном времени**: Построение графиков напряжения и тока с возможностью масштабирования
- **Статистика**: Среднее, максимальное, минимальное значение, размах (peak-to-peak) для напряжения и тока
- **Накопление энергии**: Подсчёт потреблённой энергии в ватт-часах (Wh)
- **10 пресетов**: Сохранение и вызов пресетов (напряжение, ток, OVP, OCP) с возможностью сохранения в JSON/INI
- **Ступенчатый режим (Step)**: Последовательное выполнение заданных шагов с настраиваемой задержкой и циклами
- **Скан-режим**: Автоматическое сканирование тока или напряжения с заданным шагом и задержкой
- **Обновление прошивки**: Встроенное окно обновления с поддержкой .bin и .atk файлов
- **CSV-логирование**: Запись напряжения, тока и мощности в CSV-файл
- **Три языка**: Русский, Английский, Немецкий (с сохранением выбора)
- **Настройки устройства**: OTP, OPP, яркость, громкость, RPP, авто-включение
- **Полностью автономная работа**: Не требует оригинальный ATK-DP100.exe

### Использование

1. Подключите ATK-DP100 к USB-порту вашего ПК.
2. Запустите `PowerSupplyGui.exe`.
3. Нажмите «Коннект» для подключения к устройству.
4. Управляйте блоком питания через интерфейс.

---

## English

An alternative application for controlling the **Alientek ATK-DP100** programmable power supply (USB-C PD, 0-30V / 0-5A). Fully compatible with the original HID communication protocol.

### Hardware

- Alientek ATK-DP100 programmable power supply (USB-C Power Delivery, 0-30V, 0-5A)
- Windows PC (x64)
- Standard USB-C cable

### Drivers & Setup

No drivers required. The application uses the HidSharp library for direct USB HID access.

### Key Features (Advantages over the Original Software)

- **Real-time Graphs**: Voltage and current plotting with zoom/pan support
- **Statistics**: Average, max, min values, peak-to-peak for voltage and current
- **Energy Accumulation**: Consumed energy tracking in watt-hours (Wh)
- **10 Presets**: Save/recall presets (voltage, current, OVP, OCP) with JSON/INI persistence
- **Step Mode**: Sequential execution of defined steps with configurable delay and cycles
- **Scan Mode**: Automatic current or voltage sweep with configurable step and delay
- **Firmware Update**: Built-in update window supporting .bin and .atk files
- **CSV Logging**: Record voltage, current and power to CSV files
- **Three Languages**: Russian, English, German (with saved preference)
- **Device Settings**: OTP, OPP, backlight, volume, RPP, auto-on
- **Fully Standalone**: No dependency on the original ATK-DP100.exe

### Usage

1. Connect the ATK-DP100 to your PC via USB.
2. Launch `PowerSupplyGui.exe`.
3. Click "Connect" to establish connection.
4. Control the power supply through the interface.

---

## Deutsch

Eine alternative Anwendung zur Steuerung des programmierbaren Netzteils **Alientek ATK-DP100** (USB-C PD, 0-30V / 0-5A). Vollständig kompatibel mit dem originalen HID-Kommunikationsprotokoll.

### Hardware

- Programmierbares Netzteil Alientek ATK-DP100 (USB-C Power Delivery, 0-30V, 0-5A)
- Windows-PC (x64)
- Standard-USB-C-Kabel

### Treiber & Einrichtung

Keine Treiber erforderlich. Die Anwendung verwendet die HidSharp-Bibliothek für direkten USB-HID-Zugriff.

### Hauptfunktionen (Vorteile gegenüber dem Original-Programm)

- **Echtzeit-Diagramme**: Spannungs- und Stromdiagramme mit Zoom-Unterstützung
- **Statistik**: Durchschnitts-, Maximal-, Minimalwerte und Spitze-Spitze für Spannung und Strom
- **Energie-Akkumulation**: Verbrauchsmessung in Wattstunden (Wh)
- **10 Presets**: Speichern/Aufrufen von Presets (Spannung, Strom, OVP, OCP) mit JSON/INI-Persistenz
- **Step-Modus**: Sequenzielle Ausführung definierter Schritte mit konfigurierbarer Verzögerung und Zyklen
- **Scan-Modus**: Automatischer Strom- oder Spannungs-Scan mit konfigurierbarem Schritt und Verzögerung
- **Firmware-Update**: Integriertes Update-Fenster mit Unterstützung für .bin- und .atk-Dateien
- **CSV-Logging**: Spannung, Strom und Leistung in CSV-Dateien aufzeichnen
- **Drei Sprachen**: Russisch, Englisch, Deutsch (mit gespeicherter Einstellung)
- **Geräte-Einstellungen**: OTP, OPP, Helligkeit, Lautstärke, RPP, Auto-On
- **Vollständig eigenständig**: Keine Abhängigkeit vom originalen ATK-DP100.exe

### Nutzung

1. Schließen Sie das ATK-DP100 per USB an Ihren PC an.
2. Starten Sie `PowerSupplyGui.exe`.
3. Klicken Sie auf „Verbinden" zur Verbindungsherstellung.
4. Steuern Sie das Netzteil über die Oberfläche.
