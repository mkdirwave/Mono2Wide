# m2w (Mono2Wide Premium Pseudo-Stereo Expander)

A minimalistic and professional pseudo-stereo expander JSFX plugin for **REAPER**, developed by **mkdirwave**. It is specifically designed to turn monophonic recordings (vocals, acoustic guitars, synths, loops) into wide, lush, and 100% mono-compatible stereo tracks.

## ✨ Algorithm & Audio Features
* **Micro-Pitch Detuning (LFO):** Features smooth pitch shifting within ±7 cents using low-frequency modulation (LFO) and linear interpolation. Completely free of digital clicks, phase resets, or audio artifacts.
* **Symmetrical Haas Effect:** Delay ranging from 0 to 100% (mapped to 0–30 ms) is distributed symmetrically between channels, keeping the goniometer focus perfectly centered.
* **Phase Balance Protection:** Side channels are decoupled from the center mono signal by a fixed pre-delay (20 ms). This prevents anti-phase comb filtering, frequency cancellation, and volume drops when mixing.
* **100% Mono Compatibility:** When summing the master track back to mono, the side components phase-cancel each other out perfectly without any distortion or loss of original tone.

## 🎛 Interface (Vintage Rack Light Theme)
The plugin features a custom hardware-inspired graphical user interface aligned to a perfect pixel matrix:
* **Pitch Detune (%)** — depth of the micro-pitch shifting (*Default: 50%*).
* **Haas Delay (%)** — delay time / stereo spreading width.
* **Center Level (dB) / Side Level (dB)** — independent volume control for the dry mono and processed stereo signals.
* **PC Power Switch (MONO Button)** — volume-compensated, beautifully animated rectangular toggle for instant mono-compatibility auditing.
* **Vintage LED Displays** — custom screens with realistic neon/LED glow emulation and strict fixed-width alignment for values.
* **Responsive Control** — custom hand-cursor indicators and instant real-time audio parameters recalculation as you drag the knobs.

---

# m2w (Премиальный псевдостерео-расширитель Mono2Wide)

Минималистичный и professional-уровень плагин псевдостерео-расширителя для **REAPER**, разработанный **mkdirwave** в нативном формате Cockos JSFX. Идеально подходит для превращения монофонических записей (вокал, акустическая гитара, синтезаторы, лупы) в широкое, плотное и моносовместимое стерео.

## ✨ Особенности алгоритма
* **Micro-Pitch Detuning (LFO):** Плавное смещение тона в пределах ±7 центов с использованием низкочастотной модуляции (LFO) и линейной интерполяции. Полное отсутствие цифрового треска, щелчков и фазовых сбросов.
* **Симметричный эффект Хааса:** Задержка от 0 до 100% (0–30 мс) распределяется между левым и правым каналами симметрично, удерживая фокус гониометра строго по центру.
* **Защита фазового баланса:** Сайд-каналы оторваны от центрального моно-сигнала фиксированной пред-задержкой (20 мс). Это исключает гребенчатую фильтрацию, противофазное вычитание частот и падение громкости.
* **100% Моносовместимость:** При суммировании стерео-трека обратно в моно, сайд-компоненты полностью взаимоуничтожаются, сохраняя исходный тон без фазовых искажений.

## 🎛 Особенности интерфейса (Винтажный светлый рэк)
Интерфейс выполнен в премиальном аппаратном стиле и выверен по идеальной геометрической сетке:
* **Pitch Detune (%)** — глубина микро-питчшифтинга (*По умолчанию: 50%*).
* **Haas Delay (%)** — время задержки (разведение стереобазы по сторонам).
* **Center Level (dB) / Side Level (dB)** — раздельный контроль уровня сухого моно и обработанного стерео-сигнала.
* **Клавиша питания ПК (Кнопка MONO)** — прямоугольный объемный тумблер с неоновой бирюзовой LED-подсветкой для мгновенной проверки фазы.
* **Рэковые LED-экранчики** — кастомные дисплеи с эффектом аналогового свечения (Glow) и фиксированным моноширинным шрифтом.
* **Интерактивность** — динамический курсор-рука (`Hand`) при наведении на элементы и мгновенный отклик звука на движение мыши.

## 🚀 Installation / Установка
1. Download the `m2w.jsfx` file / Скачайте файл `m2w.jsfx`.
2. In REAPER, navigate to / В REAPER перейдите в меню: `Options -> Show REAPER resource path in explorer/finder...`
3. Copy the file into the **Effects** folder / Скопируйте файл в папку **Effects**.
4. Open **FX Browser** in REAPER, right-click, and select **Scan for new plugins** / Откройте браузер эффектов, нажмите правой кнопкой мыши и обновите список плагинов.
5. Find the plugin in the **JS** category / Ищите плагин в категории **JS**.

## 📄 License
This project is licensed under the MIT License / Проект распространяется под свободной лицензией MIT.
