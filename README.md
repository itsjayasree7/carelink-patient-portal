# CareLink: Healthcare Appointment & Patient Portal

A responsive, single-page patient portal built with HTML5, CSS3, and Bootstrap 5. Patients can register, book an appointment, and browse appointment and health information, all in the browser.

> **Academic project.** CareLink is not a real medical service. All patient records, doctors, and contact details are made-up sample data.

## Features

- **Patient registration form** with HTML5 validation (required fields, email format, date limits)
- **Dependent dropdowns:** choosing a department loads that department's doctors
- **Date rules:** date of birth can't be in the future and appointments can't be in the past
- **Appointments table** with live search (name, doctor, department, ID) and a status filter
- **Summary tiles** showing Total, Confirmed, Pending, and Completed counts
- **Health information cards** for each patient
- **Toast confirmation** after a booking
- Accessible focus styles, ARIA live regions, and a mobile-friendly layout

## Tech stack

- HTML5, CSS3, vanilla JavaScript
- [Bootstrap 5.3](https://getbootstrap.com/) and [Bootstrap Icons](https://icons.getbootstrap.com/) (via CDN)
- [Inter](https://fonts.google.com/specimen/Inter) font (via Google Fonts)

## Run it

No build step. Clone the repo and open `index.html` in a browser.

```bash
git clone https://github.com/itsjayasree7/carelink-patient-portal.git
cd carelink-patient-portal
# then open index.html
```

An internet connection is needed the first time so the CDN files (Bootstrap, icons, font) can load.

## Limitations

- Data is stored in memory only, so new appointments disappear when the page is refreshed.
- There is no backend, authentication, or real data storage. Don't enter real personal or medical information.

## Possible next steps

- Persist appointments with `localStorage` or a backend
- Edit and cancel appointments
- Doctor availability and time-slot conflict checks

## License

[MIT](LICENSE)
