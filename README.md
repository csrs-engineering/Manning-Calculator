# Culvert Sizing Tool

A web-based calculator for sizing circular and box culverts using Manning's equation. This tool helps engineers, contractors, and drainage specialists quickly determine appropriate culvert dimensions based on design flow, slope, and material properties.

## 🌊 Live Demo

Visit the live application: [Culvert Sizing Tool](https://yourusername.github.io/culvert-sizing-tool/)

## 📋 Features

The Culvert Sizing Tool offers:

- **Circular Culvert Calculator**
  - Calculates required diameter in inches
  - Rounds up to nearest standard culvert size
  - Accounts for different flow depth conditions
  - Provides detailed calculation breakdown

- **Box Culvert Calculator**
  - Determines dimensions in feet
  - Offers width-to-height ratio control
  - Handles height constraints
  - Suggests alternative standard sizes

- **Comprehensive About Section**
  - Explains Manning's equation
  - Provides Manning's roughness coefficients
  - Discusses design considerations
  - Lists standard culvert sizes

## 🔧 Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- No external libraries or frameworks required

## 🚀 Getting Started

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/culvert-sizing-tool.git
   cd culvert-sizing-tool
   ```

2. Open any HTML file in your browser:
   ```bash
   open index.html
   ```

### Deployment

This is a static website that can be deployed to:

- **GitHub Pages**: Already set up and available at https://yourusername.github.io/culvert-sizing-tool/
- **Any static web hosting**: Simply upload all HTML files to your host

## 🧮 Calculation Methods

### Manning's Equation

The tool uses Manning's equation for open channel flow:

```
Q = (1.49/n) × A × R^(2/3) × S^(1/2)
```

Where:
- Q = Flow rate (cubic feet per second)
- n = Manning's roughness coefficient
- A = Cross-sectional area of flow (square feet)
- R = Hydraulic radius (feet) = A / Wetted Perimeter
- S = Channel slope (feet/feet)

### Units

- All calculations use English units
- Circular culvert results are provided in inches
- Box culvert results are provided in feet

## 🛠️ Customization

To customize this tool for your specific needs:

1. Modify the standard culvert sizes in the JavaScript code
2. Adjust the Manning's roughness coefficients
3. Change the UI colors by editing the CSS variables

## ⚠️ Disclaimer

This tool is intended for preliminary design calculations and educational purposes. Final culvert designs should be verified by qualified engineers according to local standards and regulations.

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📞 Contact

Project Link: [https://github.com/csrs-engineering/culvert-sizing-tool](https://github.com/csrs-engineering/culvert-sizing-tool)

---

Made with ❤️ for the civil engineering community
