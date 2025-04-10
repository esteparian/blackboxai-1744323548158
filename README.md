
Built by https://www.blackbox.ai

---

# Red de Comunicación

## Project Overview
The "Red de Comunicación" project is a web application designed to facilitate communication and reporting of labor issues for users. The application allows users to log in, communicate directly with a central office, report problems, send multimedia files, collect points based on their reports, and request benefits. This application is built with user experience in mind and employs modern design principles using Tailwind CSS and Font Awesome.

## Installation
To run the project locally, follow these steps:

1. **Clone or Download the Repository**
   ```bash
   git clone <repository-url>
   cd red-de-comunicacion
   ```

2. **Open the Project**
   You can open the project by navigating to the `index.html` file in your web browser or by using a local server (such as *Live Server* in VS Code).

   ```bash
   open index.html
   ```

## Usage
1. **Login:** Enter your mobile phone number to log in.
2. **Dashboard:** After a successful login, you will be redirected to the main dashboard where you can:
   - Communicate with the central office.
   - Report problems.
   - Send multimedia files.
   - View your accumulated points and benefit status.
3. **Interactions:** Use the provided forms to submit requests, report incidents, or upload files.

## Features
- **User Login:** Authentication using mobile phone numbers.
- **Dynamic Dashboard:** Offers various functionalities such as communication, reporting issues, and multimedia uploads.
- **Responsive Design:** Utilizes Tailwind CSS for a responsive and modern UI.
- **Points System:** Users earn points for reporting issues which can be redeemed for benefits.
- **Modals for Feedback:** Feedback for user actions through modals indicating successful submissions.

## Dependencies
The project does not have a standard `package.json` file which usually indicates dependencies, as it appears to be primarily built with HTML, CSS, and JavaScript without any Node.js dependencies. However, it uses external libraries:
- [Tailwind CSS](https://tailwindcss.com/): For styling.
- [Font Awesome](https://fontawesome.com/): For icons.

## Project Structure
The project structure is as follows:

```
red-de-comunicacion/
│
├── index.html          # Login page
├── home.html           # Dashboard page
├── comunicacion.html    # Communication form page
├── denuncia.html       # Report an issue page
├── multimedia.html     # Upload multimedia page
├── puntos.html         # Points and reports history page
├── beneficio.html      # Request benefits page
├── puntoTrabajo.html    # Declare work location page
├── admin.html          # Admin panel for managing users and reports
└── other necessary HTML files...
```

## Conclusion
This application provides crucial functionalities for users to communicate and report labor-related issues efficiently. By using modern web development practices, it ensures an engaging user experience while being easy to navigate and use. 

Feel free to contribute or modify the project as per your needs!