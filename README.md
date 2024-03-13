
# JavaScript Date Formatter

This project is aimed at learning the Date object in JavaScript by building a simple date formatter. The formatter can convert dates into various formats based on user preferences.

## Installation

Clone the repository to your local machine using the following command:

```bash
git clone https://github.com/prasiddha007/jsDateFormatter.git
```

## Usage

1. Include the `formatter.js` file in your HTML file:

   ```html
   <script src="formatter.js"></script>
   ```

2. Use the `formatDate` function to format your date:

   ```javascript
   const date = new Date();
   const formattedDate = formatDate(date, "dd-mm-yyyy");
   console.log(formattedDate); // Output: "13-03-2024"
   ```

## Date Format Options

You can specify the date format using the following options:

- `dd-mm-yyyy`: Day, Month, Year (default)
- `yyyy-mm-dd`: Year, Month, Day
- `mm-dd-yyyy-h-mm`: Month, Day, Year, Hours, Minutes

## Contributing

Contributions are welcome! Please follow these guidelines:

1. Fork the repository
2. Create a new branch (`git checkout -b feature`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature`)
6. Create a new Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
