# 💛 Charity Donation Management System

A web-based donation management app to collect donor details, track donations, summarize contributions, and export the donor list as a PDF.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![jsPDF](https://img.shields.io/badge/jsPDF-PDF%20Export-ff6b6b)

## Screenshots

![Home](screenshots/home.png)

## Features

- Donor registration form
- Donor details and donation history display
- Total donor count and total donation amount
- PDF export of the donor list
- Filter donors by minimum donation amount
- Bright, responsive, clean interface
- Input validation for required fields

## Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Application structure |
| CSS3 | Styling and layout |
| JavaScript | Application logic and interactivity |
| jsPDF | PDF generation |

## Project Structure

```
Charity-Donation-Management-System/
├── index.html
├── README.md
└── screenshots/
```

## How to Run

1. Clone or download this repository.

   ```bash
   git clone https://github.com/rithiksuriya/Charity-Donation-Management-System.git
   ```

2. Open the project folder.
3. Open `index.html` in a web browser.
4. Enter donor details and a donation amount.
5. Explore the donor list, summary, PDF export, and filter.

> An internet connection is needed for PDF export, since jsPDF loads from a CDN.

## Future Improvements

- Integrate a database such as MySQL
- Add secure admin authentication
- Integrate a payment gateway
- Store donor records permanently
- Add donation categories and campaign management

## Note

This is a front-end demonstration project. Donor records are stored temporarily in browser memory and are lost when the page is refreshed. Payment processing and database storage are not implemented in this version.

## Author

**Rithik Suriya M**
GitHub: [rithiksuriya](https://github.com/rithiksuriya)

## License

This project is available for educational and portfolio purposes.
