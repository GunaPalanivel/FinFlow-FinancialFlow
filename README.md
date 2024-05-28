# Fin Flow - A Fintech Bank Application

![Project Logo](/screenshots/screenshot_dashboard.jpg)

Fin Flow is a financial SaaS platform developed with Next.js, offering users seamless connectivity to multiple bank accounts, real-time transaction monitoring, fund transfers, and comprehensive financial management capabilities.

## Introduction

Fin Flow provides a modern solution for efficient financial management. Leveraging Next.js, TypeScript, and a robust tech stack including Appwrite, Plaid, and Dwolla, Fin Flow ensures secure authentication, seamless bank integration, and intuitive user experience.

## Built for STPI Govt of India SRM FINTECH HACKATHON (May 2024 - June 2024)

It is planned to conduct a SRM Hackathon in the Financial Technologies domain for the students of SRM Group in Collaboration with Software Technology Parks of India, Chennai.

This Hackathon will be Coordinated by Career Centre, SRMIST, School of Computing and SIIC.

There will be Preliminary round followed by Finals.

Preliminary rounds will be conducted in respective campuses, and Finals will be conducted at Kattankulathur campus.

## Problem Statement

`Problem Statement 6: Seamless Cross-Border Payments`

Objective:
Build a platform to facilitate fast, low-cost, and secure cross-border payments.

Description:
Traditional cross-border payment methods are often slow and expensive. Develop a solution
that uses blockchain or other innovative technologies to enable seamless international money
transfers with low fees and high security. The platform should ensure compliance with
international regulations and offer a user-friendly experience. - `Fin Flow based on this problem statement.`

## Links

- [Project Proposal](https://docs.google.com/document/d/1Kw8WHjGpgzTIlk_jzB6_XWWIZRKouFMY-zMR6uMbd9U/edit?usp=sharing)

- [Project Presentation](https://docs.google.com/presentation/d/1CgVdegk2c3cXJR1jx0TQQSXkpeXsXcxfsibwzXfozXQ/edit?usp=sharing)

- [Figma Design](https://www.figma.com/design/j0iEGwY418brI56FRFBpKF/Fin-Flow?node-id=1-1019&t=f58jXFeR8cWOQMEw-1)

- [Figjam Flow Diagram](https://www.figma.com/board/GC5JpNbFHa7gSyyD5I7MRK/Fin-Flow-logical-diagram-flow?node-id=0-1&t=sMwNxjOCCi5qEfd7-1)

## Team Members

- [Guna Palanivel](https://www.linkedin.com/in/guna-palanivel/)
- [Dinesh Raj](https://www.linkedin.com/in/dinesh-raj-r/)
- [Rohith Varma](https://www.linkedin.com/in/rohith-varma-b2b006214/)

## Tech Stack

- [**Next.js**:](https://nextjs.org/)

  - Provides server-side rendering for enhanced performance and SEO optimization.
  - **Usage**: Next.js is the primary framework utilized for server-side rendering (SSR) in Fin Flow, providing enhanced performance and SEO optimization.
  - **Benefits**: Its SSR capabilities ensure faster loading times and improved search engine visibility, contributing to a better user experience.

- [**TypeScript**:](https://www.typescriptlang.org/)

  - Ensures type safety and code reliability throughout the development process.
  - **Usage**: TypeScript is employed extensively throughout the development process of Fin Flow, ensuring type safety and code reliability.
  - **Benefits**: By enforcing strict typing, TypeScript reduces the likelihood of runtime errors and enhances code maintainability, especially in large codebases.

- [**Appwrite**:](https://appwrite.io/)

  - Enables secure user authentication and data management for the platform.
  - **Usage**: Appwrite serves as the backend solution for Fin Flow, handling user authentication and data management tasks.
  - **Benefits**: With Appwrite, Fin Flow ensures secure user authentication processes and efficient management of user data. Additionally, its comprehensive features, including database management and file storage, contribute to the platform's reliability.

- [**Plaid**:](https://plaid.com/)

  - Facilitates seamless integration with multiple bank accounts, ensuring real-time transaction updates.
  - **Usage**: Plaid integration in Fin Flow facilitates seamless connections with multiple bank accounts, enabling real-time transaction updates.
  - **Benefits**: By leveraging Plaid's robust APIs, Fin Flow empowers users with comprehensive insights into their financial activities across various accounts. This integration enhances user engagement and fosters trust in the platform.

- [**Dwolla**:](https://www.dwolla.com/)

  - Powers fund transfer functionalities, allowing users to securely transfer funds to other accounts.
  - **Usage**: Dwolla powers fund transfer functionalities securely within Fin Flow.
  - **Benefits**: With Dwolla, users can securely transfer funds to other accounts, leveraging its reliable payment processing capabilities. Dwolla's features, such as its ACH transfer system, ensure smooth and secure transactions for users.

- [**React Hook Form**:](https://react-hook-form.com/)

  - Offers a robust solution for form management, enhancing user interaction.
  - **Usage**: React Hook Form is utilized in Fin Flow for efficient and robust form management.
  - **Benefits**: Its lightweight nature and built-in validation capabilities enhance user interaction by providing a seamless form-filling experience. React Hook Form contributes to improved usability and reduces development time by simplifying form handling logic.

- [**Zod**:](https://zod.dev/)

  - Provides schema validation for data integrity and security.
  - **Usage**: Zod is integrated into Fin Flow for schema validation, ensuring data integrity and security.
  - **Benefits**: By validating user input against predefined schemas, Zod helps prevent data inconsistencies and vulnerabilities. Its straightforward API and runtime validation capabilities enhance the overall reliability of the application.

- [**TailwindCSS**:](https://tailwindcss.com/)

  - Enhances UI design with modern styling and responsiveness.
  - **Usage**: TailwindCSS is employed in Fin Flow to enhance UI design with modern styling and responsiveness.
  - **Benefits**: By using utility classes, TailwindCSS allows for rapid UI development and customization, resulting in a sleek and visually appealing interface. Its mobile-first approach ensures consistent user experiences across various devices, improving accessibility and user satisfaction.

- [**Chart.js**:](https://www.chartjs.org/)

  - Enables visualization of financial data for better insights.
  - **Usage**: Chart.js is integrated into Fin Flow for visualizing financial data in interactive and visually appealing charts.
  - **Benefits**: Its extensive chart types and customization options enable users to gain insights into their finances effectively. Chart.js enhances data visualization capabilities within the application, facilitating informed decision-making and enhancing user engagement.

- [**ShadCN**:](https://ui.shadcn.com/)
  - Offers UI components for building a sleek and user-friendly interface.
  - **Usage**: ShadCN provides UI components utilized in Fin Flow for building a sleek and user-friendly interface.
  - **Benefits**: By leveraging ShadCN's UI components, Fin Flow ensures consistency in design and a polished user interface. ShadCN's components offer pre-styled elements that streamline UI development, reducing development time and effort while maintaining design coherence.

## Features

- **Authentication**: Implements ultra-secure SSR authentication with proper validations and authorization for enhanced security.
- **Bank Integration**: Integrates seamlessly with Plaid to connect multiple bank accounts, providing users with a holistic view of their finances.
- **Home Page**: Displays a comprehensive overview of user accounts, including total balance, recent transactions, and spending insights.
- **My Banks**: Allows users to view the complete list of connected banks along with respective balances and account details.
- **Transaction History**: Provides pagination and filtering options for viewing transaction history across different banks.
- **Real-time Updates**: Reflects changes across all relevant pages instantly upon connecting new bank accounts, ensuring up-to-date information for users.
- **Funds Transfer**: Enables users to transfer funds securely using Dwolla, with required fields and recipient bank ID for smooth transactions.
- **Responsiveness**: Ensures seamless adaptation to various screen sizes and devices, providing a consistent user experience across desktop, tablet, and mobile platforms.

## Quick Start

Follow these steps to set up the project locally on your machine.

### Prerequisites

Make sure you have the following installed on your machine:

- **Git**

```link
https://git-scm.com/downloads
```

- **Node.js**

```link
https://nodejs.org/en/download/
```

- **npm (Node Package Manager)**[ Install npm globally using the following command:]

```bash
npm install -g npm
```

### Installation [To run the project locally]

Clone the repository

```bash
git clone https://github.com/GunaPalanivel/FinFlow-FinancialFlow.git
```

Navigate to the project directory

```bash
cd finflow-financialflow
```

Install the dependencies

```bash
npm install
```

Start the development server

```bash
npm run dev
```

## User Account Creation with Appwrite

In this section, the application leverages Appwrite, an open-source backend server, to simplify the process of creating and managing user accounts for web and mobile applications.

### Overview

Appwrite offers a variety of features, including user authentication, database management, file storage, and more, making it a powerful tool for developers. The application utilizes Appwrite's Email Password Session feature to allow users to create secure accounts using their email addresses and passwords.

### Key Features

- Simplifies user account management for web and mobile applications.
- Offers secure user authentication through email and password sessions.
- Provides comprehensive documentation and a user-friendly interface for easy integration and development.
- Supports multiple programming languages and frameworks, ensuring versatility and accessibility.

## Dwolla Integration for Payment Processing

Once users have created their accounts, the application integrates with Dwolla, an online payment platform that facilitates secure fund transfers.

### Overview

Dwolla offers a reliable way for users to send, receive, and request money, making it an ideal choice for handling financial transactions within the application. The application generates unique Dwolla customer URLs and IDs for each user to establish a secure connection between the application and Dwolla.

### Key Features

- Facilitates secure fund transfers through Dwolla's platform.
- Generates unique Dwolla customer URLs and IDs for seamless connectivity.
- Provides a reliable solution for sending, receiving, and requesting money within the application.

## Plaid Link Integration for Bank Account Connection

To offer users a comprehensive financial management experience, the application integrates with Plaid Link, a service that enables secure connections between bank accounts and third-party applications.

### Overview

Plaid Link simplifies the process of accessing real-time transaction data and balance updates, empowering users with valuable financial insights. Users can securely link their bank accounts to the application through Plaid Link, facilitating the exchange of data between Plaid and the platform.

### Key Features

- Enables secure connections between bank accounts and the application.
- Simplifies access to real-time transaction data and balance updates.
- Provides a seamless user experience for managing finances within the application.

## Fund Transfer Process

The application provides users with a seamless fund transfer process, leveraging the integrations with Appwrite, Dwolla, and Plaid.

### Overview

Users initiate the fund transfer process by submitting a form, providing the recipient's public bank account ID obtained from the Appwrite Bank Collection. The application retrieves bank details from the collection, initiates a fund transfer through Dwolla, and updates transaction history in the Appwrite "Transaction" collection upon successful completion.

### Key Features

- Initiates fund transfers securely through Dwolla.
- Retrieves bank details from the Appwrite Bank Collection.
- Updates transaction history for transparency and accountability.

## How to Contribute

Contributions are welcome! If you want to contribute to this project, follow these steps:

1. Fork the repository
2. Create a new branch: `git checkout -b feature/new-feature`
3. Make your changes and commit them: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature/new-feature`.
5. Submit a pull request.

## Conclusion

By leveraging Appwrite, Dwolla, and Plaid integrations, the application offers users a robust platform for user account management, payment processing, and financial transactions. The seamless integration of these services ensures a secure, efficient, and user-friendly experience for managing finances within the application.

## License

This project is licensed under the [MIT License](LICENSE)

---

#### This project is currently under development.

```
This readme provides a comprehensive overview of Fin Flow, a financial SaaS platform, emphasizing its technical architecture, features, and integrations. It offers a clear understanding of the project's structure, technology stack, and functionalities, enabling developers and users to grasp its capabilities effectively.
```
