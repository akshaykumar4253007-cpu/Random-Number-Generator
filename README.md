# Random Number Generator

<div align="center">
  
![Random Number Generator Logo](https://techonexus.com/wp-content/uploads/2025/09/Black-and-White-X-Letter-Digital-Company-Logo-3.png)

**Generate random numbers instantly for games, contests, research, and everyday use**

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/your-username/random-number-generator/pulls)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

</div>

## 🎯 Overview

A powerful, lightweight Random Number Generator that creates truly random sequences for any purpose. Perfect for giveaways, games, research, decision-making, and professional applications.

## ✨ Features

- 🎲 **Custom Range Generation** - Set any minimum and maximum values
- 📊 **Bulk Number Generation** - Generate multiple numbers simultaneously
- 🔄 **Duplicate Control** - Allow or prevent duplicate numbers
- 📈 **Smart Sorting** - No sort, ascending, or descending order
- 📱 **Multiple Formats** - Various display options for different use cases
- 🚀 **Instant Results** - Real-time generation with one-click copy
- 📱 **Responsive Design** - Works perfectly on all devices

## 🚀 Quick Start

### Basic Usage

1. **Set your range** (minimum and maximum values)
2. **Choose quantity** of numbers to generate
3. **Configure options** (duplicates, sorting, format)
4. **Click Generate** and get instant results!

### Example Configurations

```javascript
// For lottery numbers:
Range: 1-50, Count: 6, No duplicates

// For testing data:
Range: 1000-9999, Count: 20, Allow duplicates

// For prize drawings:
Range: 1-1000, Count: 5, No duplicates
```

## 🎮 Use Cases

### 🎯 **Content Creators & Marketers**
- Select giveaway winners fairly
- Randomize content scheduling
- Create interactive audience games
- Conduct prize drawings

### 🎓 **Educators & Students**
- Generate random math problems
- Select students for classroom activities
- Create research samples
- Assign random group numbers

### 🎲 **Gamers & Developers**
- Create random character stats
- Generate loot drops and rewards
- Determine random game events
- Tournament seeding

### 💼 **Business Professionals**
- A/B testing group assignment
- Fair client/case distribution
- Random task assignments
- Quality control testing

## 📋 Configuration Options

### Range Settings
- **Minimum**: Starting number (can be negative)
- **Maximum**: Ending number (any positive value)
- **Count**: Number of random values to generate

### Control Options
- **Duplicates**: Allow or prevent repeated numbers
- **Sorting**: 
  - None (true random order)
  - Ascending (low to high)
  - Descending (high to low)
- **Output Formats**:
  - Comma-separated text
  - Space-separated text
  - Spreadsheet row (tab-separated)
  - Spreadsheet column (line-separated)

## 🛠️ Installation

### Option 1: Direct HTML Integration
```html
<!-- Include the generator in your HTML -->
<div id="random-number-generator">
  <!-- Copy the HTML/CSS/JS from the repository -->
</div>
```

### Option 2: JavaScript Module
```javascript
// Import as module (if available)
import RandomNumberGenerator from './random-number-generator.js';

// Initialize
const rng = new RandomNumberGenerator({
  min: 1,
  max: 100,
  count: 5
});
```

### Option 3: WordPress/Elementor
```php
// For WordPress Elementor integration
// Use the provided widget file from this repository
```

## 📁 Project Structure

```
random-number-generator/
├── index.html                 # Main implementation
├── styles/
│   └── main.css              # Core styles
├── scripts/
│   └── generator.js          # Main functionality
├── examples/
│   ├── basic-usage.html      # Basic implementation example
│   └── advanced-usage.html   # Advanced features example
└── README.md                 # This file
```

## 🔧 Technical Details

### Algorithms
- Uses cryptographically strong random number generation
- Efficient duplicate prevention algorithms
- Optimized sorting and formatting

### Browser Support
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

### Performance
- Generates 1000 numbers in < 100ms
- Handles ranges up to ±9 quadrillion
- Memory efficient for large generations

## 🎯 Examples

### Basic Number Generation
```javascript
// Generate 10 random numbers between 1-100
Settings: Min=1, Max=100, Count=10, No duplicates
Output: 34, 67, 12, 89, 45, 23, 78, 56, 91, 3
```

### Advanced Usage
```javascript
// For statistical sampling
Settings: Min=1, Max=1000, Count=50, No duplicates, Ascending
Output: Sorted unique numbers for research sampling

// For game development  
Settings: Min=3, Max=18, Count=6, Allow duplicates, No sorting
Output: Random character attributes for RPG games
```

## 🤝 Contributing

We welcome contributions! Please feel free to submit pull requests, report bugs, or suggest new features.

### Development Setup
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Reporting Issues
Please use the [GitHub issue tracker](https://github.com/your-username/random-number-generator/issues) for:
- Bug reports
- Feature requests
- Documentation improvements

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built with modern web standards
- Accessibility-focused design
- Mobile-first responsive approach
- Community-driven improvements

## 📞 Support

If you have any questions or need help:
1. Check the [examples folder](/examples) for implementation guides
2. Open an [issue](https://github.com/your-username/random-number-generator/issues)
3. Review existing questions and solutions

---

<div align="center">

**Made with ❤️ for developers, creators, and everyone who needs a little randomness in their life**

[⭐ Star this repo](https://github.com/your-username/random-number-generator) if you find it useful!

</div>
