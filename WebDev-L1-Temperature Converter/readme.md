# Temperature Converter

A clean and responsive **Temperature Converter Web Application** built with HTML5, CSS3, and Vanilla JavaScript. The application allows users to convert temperatures between **Celsius, Fahrenheit, and Kelvin** through a simple and intuitive interface.

## ✨ Features

* Convert between Celsius, Fahrenheit, and Kelvin
* Numeric temperature input
* Temperature unit selection
* Instant conversion results
* Displays all three temperature units
* Input validation
* Absolute-zero validation
* Clear error messages
* Responsive design
* Clean and modern user interface
* Keyboard support using the Enter key
* Smooth UI interactions and animations

## 🌡️ Supported Units

The converter supports:

* **Celsius (°C)**
* **Fahrenheit (°F)**
* **Kelvin (K)**

### Conversion Formulas

**Celsius → Fahrenheit**

```text
°F = (°C × 9/5) + 32
```

**Fahrenheit → Celsius**

```text
°C = (°F − 32) × 5/9
```

**Celsius → Kelvin**

```text
K = °C + 273.15
```

**Kelvin → Celsius**

```text
°C = K − 273.15
```

## ⚠️ Input Validation

The application prevents physically invalid temperatures below absolute zero.

| Unit       | Minimum Valid Temperature |
| ---------- | ------------------------: |
| Celsius    |                 -273.15°C |
| Fahrenheit |                 -459.67°F |
| Kelvin     |                       0 K |

Invalid values produce a clear validation message instead of generating an incorrect result.

## 🛠️ Technologies Used

* **HTML5** — Semantic structure
* **CSS3** — Layout, responsive design, animations, and visual styling
* **Vanilla JavaScript** — Conversion logic, validation, and interaction

No external frameworks or libraries are required.

## 📁 Project Structure

```text
temperature-converter/
│
├── index.html
├── style.css
├── script.js
│
├── assets/
│   └── images/
│
└── README.md
```

## 🎨 Design

The interface follows a clean, modern application-style design with:

* Centered converter interface
* Large temperature input
* Unit selector
* Prominent conversion button
* Individual result cards
* Clear typography
* Rounded UI elements
* Subtle shadows and animations
* Responsive spacing and layout

The design focuses on **simplicity, readability, and ease of use**.

## 📱 Responsive Design

The application is optimized for:

* Desktop
* Laptop
* Tablet
* Mobile devices

On smaller screens, the converter automatically adapts its layout, typography, buttons, and result cards for comfortable touch interaction.

## ⚙️ How It Works

1. Enter a temperature value.
2. Select the input unit.
3. Click **Convert**.
4. The application validates the input.
5. The temperature is converted into the other supported units.
6. The results are displayed in separate output cards.

## 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/your-username/temperature-converter.git
```

Navigate to the project:

```bash
cd temperature-converter
```

Open `index.html` in a browser, or run it using a local development server such as VS Code Live Server.

## 📌 Project Goals

This project was created to practice and demonstrate:

* HTML5 structure
* CSS3 responsive design
* JavaScript fundamentals
* DOM manipulation
* Mathematical calculations
* Form validation
* User interaction
* Responsive UI development

## 🔮 Future Improvements

Potential future features include:

* Automatic conversion while typing
* Temperature conversion history
* Dark mode
* Copy result button
* More temperature units
* Temperature scale visualization
* Conversion history stored in local storage
* PWA support

## 📄 License

This project is created for educational and portfolio purposes.
