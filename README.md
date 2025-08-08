# 🛎️ WackyFlip-Support

**Customer Support & Help Center UI for Wacky Flip**


`WackyFlip-Support` is the codebase powering the **customer support portal** and **help center** on [wackyflip.com](https://wackyflip.com). It enables players to find answers, submit tickets, browse FAQs, and get timely assistance with their Wacky Flip experience.

---

## 🎯 Features

| Feature                    | Description                                                                    |
| -------------------------- | ------------------------------------------------------------------------------ |
| 📚 FAQ Section             | Well-organized, searchable knowledge base covering common questions and issues |
| 📨 Ticket Submission       | Users can submit support requests with attachments and track ticket status     |
| 💬 Live Chat Integration   | Embedded chat widget for real-time help (optional)                             |
| 🧩 Troubleshooting Wizards | Interactive guides to diagnose and resolve common problems                     |
| 🔍 Search & Filter         | Powerful search and category filters for quick navigation                      |
| 🛠 Admin Dashboard         | Internal tools for support staff to manage tickets, FAQs, and responses        |
| 🌐 Multilingual Support    | Localization ready for global players                                          |

---

## 🛠 Tech Stack

* **Frontend Framework:** React + TypeScript
* **UI Library:** Chakra UI or TailwindCSS (customized for branding)
* **State Management:** Redux Toolkit or Zustand
* **Backend Integration:** REST/GraphQL APIs to WackyFlip-Support-Backend (separate repo)
* **Chat Services:** Optional integration with Intercom, Zendesk, or custom chat bots

---

## 📁 Repository Structure

```
WackyFlip-Support/
├── components/
│   ├── FAQList.tsx
│   ├── TicketForm.tsx
│   ├── ChatWidget.tsx
│   └── AdminDashboard/
├── pages/
│   ├── index.tsx
│   ├── faq.tsx
│   ├── submit-ticket.tsx
│   └── ticket-status.tsx
├── hooks/
├── utils/
├── styles/
├── public/
└── README.md
```

---

## 🚀 Getting Started

1. Clone the repo:

```bash
git clone https://github.com/WackyFlip/WackyFlip-Support.git
cd WackyFlip-Support
npm install
```

2. Start the development server:

```bash
npm run dev
```

3. Open your browser at [http://localhost:3000](http://localhost:3000) to view the support portal UI.

---

## 📬 Contribution Guidelines

* Follow the coding standards outlined in `CONTRIBUTING.md`
* Submit bug reports or feature requests via GitHub Issues
* Ensure accessibility and mobile responsiveness for all components
* Write unit and integration tests for new features

---

## 🔗 Related Repositories

* [`WackyFlip-AccountPortal`](https://github.com/wackyflipgame/WackyFlip-AccountPortal) – For account-related support actions
* [`WackyFlip-DocsSite`](https://github.com/wackyflipgame/WackyFlip-DocsSite) – Documentation portal for self-service help
* [`WackyFlip-API`](https://github.com/wackyflipgame/WackyFlip-API) – Backend APIs for ticket management and support workflows

---

## 📜 License

MIT © 2025 Wacky Flip Studios
