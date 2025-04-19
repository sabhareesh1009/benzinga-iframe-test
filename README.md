# Benzinga Earnings Widget iFrame Integration

This project demonstrates how to embed the Benzinga Earnings Widget in a webpage using an iframe. It provides a simple interface for configuring the widget with different parameters.

## Features

- Embed the Benzinga Earnings Widget in any webpage
- Configure widget title, days to show, and quarter
- Dynamic updates without page reload
- Responsive design that works on all devices

## Usage

Simply open the `benzinga-earning-iframe.html` file in a web browser to see the widget in action.

### Configuration Options

The following parameters can be configured:

- **Title**: Custom title for the earnings widget
- **Days to Show**: Number of days of earnings data to display (3, 5, or 7)
- **Quarter**: Filter earnings by quarter (Q1, Q2, Q3, or Q4)

## Implementation

The widget is embedded using a standard iframe element:

```html
<iframe 
  src="https://benzinga-earning-app.netlify.app/widget?title=Earnings%20Calendar&daysToShow=5&quarter=Q1" 
  title="Benzinga Earnings Widget"
  style="border: 0;"
></iframe>
```

Parameters are passed via URL query parameters:

- `title`: The widget title
- `daysToShow`: Number of days to display
- `quarter`: Which quarter to show (Q1, Q2, Q3, Q4)

## Live Demo

A live version of this integration is available at:

[https://benzinga-iframe-test.netlify.app/](https://benzinga-iframe-test.netlify.app/)

## Related Projects

- [Benzinga Earnings Widget](https://github.com/sabhareesh1009/benzinga-project) - The main widget project
- [Earnings Widget React Integration](https://github.com/sabhareesh1009/earnings-widget-test) - React integration example
