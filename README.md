# UOG Timetable Generator

A simple and elegant timetable generator for University of Gujrat (UOG) students and faculty.

## Features

- **Dynamic Timetable Generation**: Paste your course data and instantly generate a formatted timetable
- **Print & Download**: Print or save your timetable as PDF in landscape mode
- **Responsive Design**: Clean, modern interface that works on all devices
- **Easy Data Input**: Simple tab-separated format for course data entry

## How to Use

1. Copy your course data (Course Code, Section, Title, Credits, Instructor, Day, Time, Room)
2. Paste it into the textarea
3. Click "Generate Timetable"
4. Print or download your formatted timetable

## Data Format

Your data should be tab-separated with the following columns:
```
Course Code    Section    Course Title    Cr. Hrs.    Instructor    Lecture Day    Lecture Time    Room
CS-255         EB         Computer Org    3           John Doe      MON           13:30-15:00     B205
```

## Live Demo

Visit the live application: [UOG Timetable Generator](https://uog-time-table.vercel.app/)

## Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/MussabPro/UOG-TimeTable.git
   ```

2. Open `index.html` in your browser or serve it with a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   ```

## Deployment

This project is designed to be deployed on Vercel:

1. Push your code to GitHub
2. Import your repository on Vercel
3. Deploy automatically

## Technologies Used

- Pure HTML, CSS, and JavaScript
- No external dependencies
- Responsive design with print optimization

## Contact

- **Email**: mussabomair16@gmail.com
- **GitHub**: [MussabPro](https://github.com/MussabPro)

## License

This project is open source and available under the [MIT License](LICENSE).