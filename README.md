# MotorIQ VIN Report Generator

![MotorIQ Logo](https://cdn.builder.io/api/v1/image/assets/TEMP/c23e8f63986471ea66e2ace2b2d12f1ca12307930e7b844eb19a1544502e16c4?placeholderIfAbsent=true&apiKey=ba3b1c7e72bc4feaa662c5eb385ebd67)

## 🚗 Overview

The MotorIQ VIN Report Generator is a sophisticated HTML/CSS/JavaScript solution that creates visually stunning, data-rich PDF reports for vehicle identification numbers (VINs). These reports provide comprehensive vehicle information including theft history, odometer readings, specs, and more - all beautifully formatted according to our Figma design system.

## ✨ Key Features

- **Dynamic Page Generation**: Automatically builds report pages based on available data
- **Multilingual Support**: Full localization for EN 🇬🇧, FR 🇫🇷, IT 🇮🇹, DE 🇩🇪, and ES 🇪🇸
- **Unit Conversion**: Toggle between metric and imperial measurements
- **Interactive Charts**: Data visualization using Chart.js
- **Modular Architecture**: Reusable code snippets for consistent styling
- **API Integration**: Seamless connectivity with PDFMonkey.io for rendering

## 🛠️ Technical Architecture

### Core Components

- **HTML Templates**: Base structure with Liquid templating
- **CSS Styling**: Clean, consistent design using Tailwind CSS
- **Chart.js**: Interactive data visualizations for vehicle metrics
- **Snippets System**: Modular HTML components for:
  - Status indicators (warnings, confirmations)
  - Alert boxes (red, yellow)
  - Data visualizations
  - Section layouts

### Data Processing

The generator processes VIN data from JSON sources, including:

- Vehicle specifications
- Theft records across multiple countries
- Odometer history with anomaly detection
- Market value analysis and projections
- Safety equipment and features
- Emissions data and environmental impact

### Integration Points

- **PDFMonkey.io**: Handles the HTML-to-PDF rendering process
- **API Webhooks**: Enables automated report generation and delivery
- **Figma Design System**: Ensures visual consistency with the MotorIQ brand

## 📊 Report Sections

- **Vehicle Overview**: Make, model, year, fuel type
- **Theft Status**: Verification against international databases
- **Odometer Analysis**: History tracking with rollback detection
- **Market Value**: Retail, trade-in, and auction values
- **Manufacturer Details**: Production information
- **Emissions & Taxes**: Environmental impact assessment
- **Vehicle Specifications**: Comprehensive technical data
- **Equipment & Features**: Safety, comfort, and entertainment systems

## 🌐 Internationalization

The system supports multiple languages through a comprehensive translation system stored in `languages.json`. Language selection is controlled via the `language` parameter, affecting all text elements throughout the report.

## 🔄 Unit Conversion

Reports can be generated in either metric or imperial units based on the `is_metrics` flag:

- **Metric**: km, km/h, l/100km, g/km, mm, kg
- **Imperial**: miles, mph, mpg, lbs, inches

## 🚀 Usage

The generator is designed to be used as part of the MotorIQ application ecosystem.

## 📝 License

© MotorIQ - All Rights Reserved

---
