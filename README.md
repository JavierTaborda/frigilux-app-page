# 📦 Frigilux SGE - Legal Documentation Portal

This project centralizes the **Terms and Conditions**, **Privacy Policy**, and **Frequently Asked Questions (FAQ)** for the **Frigilux App SGE**. Built with Astro to ensure lightning-fast performance and a clean corporate design.

## 🔗 Live Project
🚀 **Live Site:** [INSERT YOUR VERCEL LINK HERE] (e.g., https://frigilux-sge-docs.vercel.app)

---

## 📸 Screenshots
| Terms & Conditions | Privacy Policy |
| :--- | :--- |
| ![Terms Preview](https://via.placeholder.com/400x250?text=Terms+Screenshot) | ![Privacy Preview](https://via.placeholder.com/400x250?text=Privacy+Screenshot) |

---

## 🛠️ Tech Stack
* **Framework:** [Astro 5.0+](https://astro.build/)
* **Styling:** [Tailwind CSS](https://tailwindcss.com/)
* **Deployment:** [Vercel](https://vercel.com/)
* **Icons:** Lucide Icons / Tabler Icons

---

## 📂 Project Structure

```text
/
├── public/             # Static assets (favicon, branding)
├── src/
│   ├── constants.ts    # Global configuration (Support & Admin emails)
│   ├── layouts/        # Base structure (Corporate Header/Footer)
│   ├── pages/
│   │   ├── index.astro       # Main landing page
│   │   ├── privacy.astro     # Privacy Policy with Venezuelan legal framework
│   │   ├── terms.astro       # T&C for internal collaborators
│   │   └── faq.astro         # Interactive FAQ accordions
│   └── components/     # Reusable UI components
└── .env                # Environment variables (Git-ignored)