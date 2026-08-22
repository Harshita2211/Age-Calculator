# 🎂 Age Calculator

A simple, elegant, and fully responsive **Age Calculator** web application built with vanilla HTML, CSS, and JavaScript. Enter your date of birth and instantly get your exact age in years, months, and days—plus additional statistics like total weeks, hours, and minutes lived!

---

## ✨ Features

- 📅 **Date Input**: Simple date picker interface for entering your birth date
- 🧮 **Accurate Calculations**: Computes age in multiple units:
  - Years, Months, and Days (primary display)
  - Total months, weeks, days, hours, and minutes passed
- 📱 **Fully Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- 🎨 **Modern UI**: Clean, attractive interface with gradient background and smooth styling
- ⚡ **Instant Results**: Real-time age calculation on form submission
- 🔧 **No External Dependencies**: Built with pure vanilla JavaScript—no frameworks required

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| **HTML5** | Structure and semantic markup |
| **CSS3** | Styling, layout, and responsive design |
| **JavaScript (ES6)** | Logic, DOM manipulation, and event handling |

---

## 📁 Project Structure

```
Age-Calculator/
├── index.html       # Main HTML file with form and result container
├── style.css        # Styling and responsive design
├── script.js        # Age calculation logic and event listeners
└── README.md        # Project documentation (this file)
```

---

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge, etc.)
- No installation or dependencies required!

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Harshita2211/Age-Calculator.git
   cd Age-Calculator
   ```

2. **Open in your browser**:
   Simply double-click `index.html` or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (with http-server package)
   npx http-server
   ```

3. **Access the app**:
   - Direct: Open `index.html` in your browser
   - Local server: Visit `http://localhost:8000`

---

## 📖 How to Use

1. **Enter your birthdate**: Click on the date input field and select your date of birth
2. **Click "Calculate Age"**: Submit the form
3. **View results**: Your age will be displayed in multiple formats:
   - **Age**: Years, Months, and Days
   - **Months Passed**: Total months since birth
   - **Weeks Passed**: Total weeks since birth
   - **Days Passed**: Total days since birth
   - **Hours Passed**: Total hours since birth
   - **Minutes Passed**: Total minutes since birth

---

## 💡 Key Functionality

### Age Calculation Logic (`script.js`)

The calculator uses the following approach:

1. **Parse Input**: Extracts the selected birth date from the date picker
2. **Calculate Time Difference**: Finds the milliseconds between today and birth date
3. **Convert to Different Units**: Converts milliseconds to seconds, minutes, hours, days, weeks, months, and years
4. **Display Results**: Renders formatted results showing age in multiple units

### Calculation Formula
```javascript
Time Difference (ms) → Years, Months, Days
- 1 year ≈ 365.25 days (accounting for leap years)
- 1 month ≈ 30.436875 days (average)
- 1 week = 7 days
```

---

## 🎨 Design Features

- **Gradient Background**: Eye-catching teal to green gradient
- **Responsive Layout**: Container adapts to screen size
- **Form Styling**: Clean input fields and interactive button
- **Result Display**: Well-organized result cards with clear typography
- **Shadow Effects**: Subtle shadows for depth and modern look

---

## 🔄 Browser Compatibility

| Browser | Support |
|---------|---------|
| Chrome | ✅ Full support |
| Firefox | ✅ Full support |
| Safari | ✅ Full support |
| Edge | ✅ Full support |
| Opera | ✅ Full support |

---

## 📱 Responsive Design

- **Desktop (600px+)**: Full-width container centered on page
- **Tablet (768px)**: Optimized layout for medium screens
- **Mobile**: Touch-friendly date picker and readable text sizes

---

## 🐛 Known Limitations

- Date input format depends on browser locale (HTML5 date picker)
- Calculations are based on average days per month/year (accounting for leap years)
- No timezone considerations; uses local system date

---

## 🚀 Future Enhancements

- [ ] Add timezone support
- [ ] Export age calculation as PDF or image
- [ ] Dark mode toggle
- [ ] Multiple age format options (zodiac sign, Chinese zodiac, etc.)
- [ ] Age comparison feature (compare ages with friends)
- [ ] Birthday reminder notifications
- [ ] Localization support (multiple languages)

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! 

### How to Contribute

1. Fork the repository
   ```bash
   git clone https://github.com/Harshita2211/Age-Calculator.git
   ```

2. Create a new branch
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. Make your changes and commit
   ```bash
   git commit -m "Add: your feature description"
   ```

4. Push to your branch
   ```bash
   git push origin feature/your-feature-name
   ```

5. Open a Pull Request

---

## 📋 Code Quality

- Clean, well-commented code
- ES6+ JavaScript best practices
- Semantic HTML structure
- CSS follows modern standards
- No external dependencies

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙋‍♀️ About

Created with ❤️ by [Harshita2211](https://github.com/Harshita2211)

### Connect & Support

- 🌟 Star this repository if you find it useful!
- 💬 Open an issue for bugs or feature requests
- 🍴 Fork and contribute improvements

---

## 📚 Resources

- [MDN Web Docs - Date API](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date)
- [HTML Input Date](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/date)
- [CSS Grid & Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout)

---

**Happy Age Calculating! 🎉**
