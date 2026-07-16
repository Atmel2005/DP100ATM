# PowerSupplyGui — Альтернативное ПО для ATK-DP100

## Deutsch

Alternative Anwendung zur Steuerung des programmierbaren Netzteils **Alientek ATK-DP100**. Vollständig kompatibel mit dem originalen HID-Kommunikationsprotokoll.

### Ausrüstung

- Programmierbares Netzteil Alientek ATK-DP100
- Computer mit Windows (x64)
- Mitgeliefertes Kabel
- Externe Stromquelle

### Treiber & Einrichtung

Treiber werden nicht benötigt. Die Anwendung verwendet die HidSharp-Bibliothek für direkten Zugriff auf das USB-HID-Interface des Netzteils.

### Hauptfunktionen (Vorteile gegenüber dem Original-Programm)

- **Echtzeit-Diagramme**: Darstellung von Spannungs- und Stromdiagrammen mit Zoom-Funktion
- **Statistik**: Durchschnitts-, Maximal-, Minimalwerte und Spitze-Spitze für Spannung und Strom
- **Energie-Akkumulation**: Erfassung des Energieverbrauchs in Wattstunden (Wh)
- **10 Presets**: Speichern und Aufrufen von Presets (Spannung, Strom, OVP, OCP) mit JSON/INI-Persistenz
- **Step-Modus**: Sequenzielle Ausführung definierter Schritte mit einstellbarer Verzögerung und Zyklen
- **Scan-Modus**: Automatischer Strom- oder Spannungs-Scan mit einstellbarem Schritt und Verzögerung
- **Firmware-Update**: Integriertes Update-Fenster mit Unterstützung für .bin- und .atk-Dateien
- **CSV-Logging**: Aufzeichnung von Spannung, Strom und Leistung in CSV-Dateien
- **Drei Sprachen**: Russisch, Englisch, Deutsch (mit Speicherung der Auswahl)
- **Geräte-Einstellungen**: OTP, OPP, Helligkeit, Lautstärke, RPP, Auto-On

### Nutzung

1. Schließen Sie das ATK-DP100 per USB an Ihren Computer an.
2. Starten Sie `PowerSupplyGui.exe`.
3. Klicken Sie auf „Verbinden" zur Herstellung der Verbindung zum Gerät.
4. Steuern Sie das Netzteil über die Oberfläche.

---

## Українська

Альтернативна програма для керування програмованим блоком живлення **Alientek ATK-DP100**. Повна сумісність з оригінальним протоколом HID-комунікації.

### Обладнання

- Програмований блок живлення Alientek ATK-DP100
- Комп'ютер з Windows (x64)
- Комплектний кабель
- Зовнішнє джерело живлення

### Драйвери та налаштування

Драйвери не потрібні. Програма використовує бібліотеку HidSharp для прямого доступу до USB HID-інтерфейсу блоку живлення.

### Основні можливості (Переваги порівняно з оригінальним ПЗ)

- **Графіки в реальному часі**: Побудова графіків напруги та струму з можливістю масштабування
- **Статистика**: Середнє, максимальне, мінімальне значення, розмах (peak-to-peak) для напруги та струму
- **Накопичення енергії**: Підрахунок спожитої енергії у ватт-годинах (Wh)
- **10 пресетів**: Збереження та виклик пресетів (напруга, струм, OVP, OCP) з можливістю збереження в JSON/INI
- **Ступінчастий режим (Step)**: Послідовне виконання заданих кроків з налаштовуваною затримкою та циклами
- **Режим сканування**: Автоматичне сканування струму або напруги з заданим кроком та затримкою
- **Оновлення прошивки**: Вбудоване вікно оновлення з підтримкою .bin та .atk файлів
- **CSV-логування**: Запис напруги, струму та потужності у CSV-файл
- **Три мови**: Російська, Англійська, Німецька (зі збереженням вибору)
- **Налаштування пристрою**: OTP, OPP, підсвітка, гучність, RPP, авто-ввімкнення

### Використання

1. Підключіть ATK-DP100 до USB-порту вашого комп'ютера.
2. Запустіть `PowerSupplyGui.exe`.
3. Натисніть «Підключити» для встановлення з'єднання з пристроєм.
4. Керуйте блоком живлення через інтерфейс.

---

## English

An alternative application for controlling the **Alientek ATK-DP100** programmable power supply. Fully compatible with the original HID communication protocol.

### Hardware

- Alientek ATK-DP100 programmable power supply
- Windows PC (x64)
- Included cable
- External power supply

### Drivers & Setup

No drivers required. The application uses the HidSharp library for direct USB HID access.

### Key Features (Advantages over the Original Software)

- **Real-time Graphs**: Voltage and current plotting with zoom support
- **Statistics**: Average, max, min values, peak-to-peak for voltage and current
- **Energy Accumulation**: Consumed energy tracking in watt-hours (Wh)
- **10 Presets**: Save/recall presets (voltage, current, OVP, OCP) with JSON/INI persistence
- **Step Mode**: Sequential execution of defined steps with configurable delay and cycles
- **Scan Mode**: Automatic current or voltage sweep with configurable step and delay
- **Firmware Update**: Built-in update window supporting .bin and .atk files
- **CSV Logging**: Record voltage, current and power to CSV files
- **Three Languages**: Russian, English, German (with saved preference)
- **Device Settings**: OTP, OPP, backlight, volume, RPP, auto-on

### Usage

1. Connect the ATK-DP100 to your PC via USB.
2. Launch `PowerSupplyGui.exe`.
3. Click "Connect" to establish connection to the device.
4. Control the power supply through the interface.

---

## Русский

Альтернативное приложение для управления программируемым блоком питания **Alientek ATK-DP100**. Полностью совместимо с оригинальным протоколом HID-коммуникации.

### Оборудование

- Программируемый блок питания Alientek ATK-DP100
- Компьютер с Windows (x64)
- Комплектный кабель
- Внешний источник питания

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

### Использование

1. Подключите ATK-DP100 к USB-порту вашего ПК.
2. Запустите `PowerSupplyGui.exe`.
3. Нажмите «Коннект» для подключения к устройству.
4. Управляйте блоком питания через интерфейс.
