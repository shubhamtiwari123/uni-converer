# uni-converer
# Enhanced Timestamp Conversion Tool

A web-based utility for converting between Unix timestamps, custom epochs, and the 1899 MOMENT date system.

## Features

- **Date ↔ Unix Timestamp** conversion with timezone support
- **Custom Epoch Converter** for any epoch date and time unit
- **1899 MOMENT System** converter (minutes since Dec 30, 1899)
- Built-in verification tests
- Responsive glassmorphism UI

## Usage

1. Open the HTML file in any modern browser
2. Use the conversion sections as needed:
   - Date to Unix: Select date/time and timezone
   - Unix to Date: Enter timestamp 
   - Custom Epoch: Set epoch date and convert values
   - MOMENT: Convert 1899-based minute values

## Key Constants

- Unix Epoch: January 1, 1970 UTC
- MOMENT Epoch: December 30, 1899 UTC  
- Offset: 25,567 days (36,816,480 minutes)

## Example

```
Input: January 1, 2023 UTC
Unix: 1672531200
MOMENT: 64,723,200 minutes
```

## Browser Support

Chrome 60+, Firefox 55+, Safari 12+, Edge 79+**
