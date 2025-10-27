# Engage App

A powerful, self-hostable application to automatically monitor GitHub repository releases and receive instant email or Apprise notifications. 
## ✨ Key Features

- **Automated Release Monitoring**: Add public GitHub repositories and let the app automatically check for new releases in the background.
- **Flexible Notifications**:
  - **Email**: Configure SMTP settings to receive detailed email notifications.
- **Flexible Release Filtering**:
    - **Global Settings**: Define application-wide rules for which release types (stable, pre-release, draft) to monitor.
    - **Per-Repository Overrides**: Customize filtering rules for individual repositories.
    - **Regex-Powered Precision**: Use "Include" and "Exclude" regular expression patterns for fine-grained control over release tags. The "Include" pattern overrides the standard channel filters, giving you ultimate control.
- **Modern & Responsive UI**:
    - Clean, intuitive interface built with ShadCN UI and Tailwind CSS.
    - Full dark mode support.
    - Responsive design for both desktop and mobile use.
- **Internationalization (i18n)**: Supports English and German out of the box.
- **Data Management**: Easily import or export your list of monitored repositories via JSON.
- **System Diagnostics**: A built-in test page to verify GitHub API connectivity and notification service (SMTP, Apprise) configuration.


## 🛠️ Tech Stack

- **Framework**: [Next.js](https://nextjs.org/) (App Router)
- **UI**: [React](https://react.dev/), [TypeScript](https://www.typescriptlang.org/), [Tailwind CSS](https://tailwindcss.com/), [ShadCN UI](https://ui.shadcn.com/)
- **Internationalization**: [next-intl](https://next-intl.dev/)
- **Authentication**: [iron-session](https://github.com/vvo/iron-session)
- **Notifications**: [Nodemailer](https://nodemailer.com/), [Apprise](https://github.com/caronc/apprise)

---
