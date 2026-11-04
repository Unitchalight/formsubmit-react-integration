# 📬 FormSubmit React Integration

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=15,8,25&height=210&section=header&text=FormSubmit%20React%20Integration&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Send%20Emails%20from%20Your%20React%20Form%20%E2%80%94%20No%20Backend%20Needed&descAlignY=56&descSize=17" width="100%"/>

<br/>

[![Version](https://img.shields.io/badge/version-2.4.0-3D5A80?style=for-the-badge&logo=semanticrelease&logoColor=white)](https://github.com)
[![React](https://img.shields.io/badge/React-18%2B-98C1D9?style=for-the-badge&logo=react&logoColor=black)](https://react.dev)
[![License](https://img.shields.io/badge/license-MIT-EE6C4D?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](LICENSE)
[![Setup](https://img.shields.io/badge/setup-2%20minutes-E0FBFC?style=for-the-badge&logo=clockify&logoColor=black)](https://formsubmit.co)

<br/>

### ✉️ A clean, typed React integration for FormSubmit — working contact forms in minutes

*⚡ No Backend • 🎯 Type-Safe • 🛡️ Spam Protection • ♿ Accessible*

<br/>

<a href="https://share.google/Izra4isP5mRowoU6a">
  <img src="https://img.shields.io/badge/🚀_LIVE_DEMO-3D5A80?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=2A4059" alt="Live Demo" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/Izra4isP5mRowoU6a">
  <img src="https://img.shields.io/badge/📥_GET_CODE-98C1D9?style=for-the-badge&logo=github&logoColor=black&labelColor=6F98B0" alt="Get Code" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/Izra4isP5mRowoU6a">
  <img src="https://img.shields.io/badge/📚_DOCS-EE6C4D?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=BB5038" alt="Docs" height="45"/>
</a>

</div>

<img width="1672" height="941" alt="eda47438-3e1c-4121-a903-47c3028660e3" src="https://github.com/user-attachments/assets/ad9bbe46-1c31-43f1-88d8-1f810d8ce2ae" />


<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🌟 About

**FormSubmit React Integration** is a ready-to-use, fully typed React component set that connects your contact forms to **FormSubmit.co** — a free email forwarding service that requires **zero backend**.

Drop in the component, add your email, and start receiving submissions. Validation, loading states, error handling, spam protection, and accessibility are all handled out of the box.

> 💡 **Perfect for:** Portfolio contact forms, landing page signups, feedback forms, or any React project that needs a working form **without a server**.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎯 Key Features

<div align="center">

| ⚡ **Zero Backend** | 🎯 **TypeScript** | 🛡️ **Spam Protection** |
|:---:|:---:|:---:|
| No server, no API<br/>keys, no config | Full type safety<br/>& autocomplete | Honeypot + optional<br/>CAPTCHA support |

| ♿ **Accessible** | 🎨 **Customizable** | 🔄 **State Handling** |
|:---:|:---:|:---:|
| ARIA labels, focus<br/>management, keyboard | Style with CSS,<br/>Tailwind or MUI | Loading, success,<br/>error — all handled |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🏆 Why This Integration

<div align="center">

| 💎 **Advantage** | 📝 **Description** |
|:---|:---|
| ⏱️ **2-Minute Setup** | Copy one component and change one email string — done |
| 🎯 **Type-Safe** | Full TypeScript types for props, responses, and errors |
| 🛡️ **Spam-Resistant** | Built-in honeypot field + support for FormSubmit's CAPTCHA |
| ♿ **WCAG-Aware** | Proper labels, error announcements, and keyboard navigation |
| 🎨 **Unstyled by Design** | Bring your own CSS, Tailwind, or component library |
| 🔄 **Complete UX** | Loading spinner, success message, retry — no extra work |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎬 Component in Action

<div align="center">

```ascii
╔══════════════════════════════════════════════════╗
║  📬  FormSubmit React Integration  v2.4.0        ║
╠══════════════════════════════════════════════════╣
║                                                  ║
║  Name                                            ║
║  ┌────────────────────────────────────────────┐  ║
║  │ Jane Doe                                   │  ║
║  └────────────────────────────────────────────┘  ║
║                                                  ║
║  Email                                           ║
║  ┌────────────────────────────────────────────┐  ║
║  │ jane@example.com                       ✅  │  ║
║  └────────────────────────────────────────────┘  ║
║                                                  ║
║  Message                                         ║
║  ┌────────────────────────────────────────────┐  ║
║  │ Hey, I'd love to work with you on...       │  ║
║  └────────────────────────────────────────────┘  ║
║                                                  ║
║  [ ✉️ Send Message ]                             ║
║                                                  ║
║  ✅ Message sent successfully!                   ║
╚══════════════════════════════════════════════════╝
```

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧩 Project Structure

```
📬 formsubmit-react-integration/
├── 🎯 src/
│   ├── components/            # React components
│   │   ├── ContactForm.tsx
│   │   ├── FormField.tsx
│   │   └── SubmitButton.tsx
│   ├── hooks/                 # Form logic hooks
│   │   ├── useFormSubmit.ts
│   │   └── useValidation.ts
│   ├── types/                 # TypeScript types
│   └── utils/                 # Helpers
├── 🎨 examples/               # Usage examples
│   ├── basic/
│   ├── tailwind/
│   └── mui/
├── 🧪 tests/                  # Vitest + Testing Library
└── 📖 docs/                   # Setup & API reference
```

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🛠️ Tech Stack

<div align="center">

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![FormSubmit](https://img.shields.io/badge/FormSubmit.co-EE6C4D?style=for-the-badge&logo=maildotru&logoColor=white)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🤝 Community

Found a bug? Want to add support for another form provider?

<div align="center">

<a href="https://share.google/Izra4isP5mRowoU6a">
  <img src="https://img.shields.io/badge/💬_Join_Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" height="35"/>
</a>
<a href="https://share.google/Izra4isP5mRowoU6a">
  <img src="https://img.shields.io/badge/🐞_Report_Issue-3D5A80?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>
<a href="https://share.google/Izra4isP5mRowoU6a">
  <img src="https://img.shields.io/badge/⭐_Star_Repo-EE6C4D?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.

> **Note:** FormSubmit is an independent third-party service. This project is an unofficial community integration and is **not affiliated with FormSubmit**. Always review FormSubmit's terms and privacy policy before using it in production.

<br/>

<div align="center">

### 📬 Made with ✉️ by the FormSubmit React Team

*If this integration saved you a backend — star the repo!*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=15,8,25&height=120&section=footer" width="100%"/>

</div>
