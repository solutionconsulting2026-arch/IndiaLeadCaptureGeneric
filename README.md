# Bharat Commercial Bank — Digital Lead Capture Demo (India)

A modern, responsive digital onboarding and Online Lead Capture (OLC) demonstration portal tailored for the Indian retail banking and financial services sector, powered by CRMNEXT.

---

## 🌟 Overview

This project demonstrates a streamlined, paperless customer acquisition workflow simulating instant retail banking lead generation in India:
- **Product Offerings**: Comprehensive Retail Banking, Personal Financing, Card Solutions, and Wealth Services.
- **Indian Financial KYC Identifiers**: Captures PAN / Aadhaar reference, Indian mobile numbers (+91), residential address, and annual income in INR (₹).
- **Core Banking CRM Integration**: Direct integration with CRMNEXT Online Lead Capture (OLC) gateway with automated deduplication and branch Relationship Manager (RM) assignment.
- **Dynamic Confirmation**: Automated 302 HTTP redirection to a personalized confirmation page (`thank-you.html`) with dynamic applicant greeting and reference tracking ID.

---

## 📁 Repository Structure

```text
├── index.html         # Main banking portal & digital lead application form
├── thank-you.html     # Confirmation page with dynamic parameter extraction & roadmap
├── bank-logo.svg      # Vector brand logo (Bharat Commercial Bank)
├── bank-icon.svg      # SVG favicon / application icon
├── .gitignore         # Ignores extraneous demo assets
└── README.md          # Project documentation
```

---

## 🚀 Key Features

1. **Responsive & Modern UI**: Built with pure semantic HTML5, modern CSS3 (custom CSS properties, flexbox, CSS grid), and vanilla JavaScript. No heavy external frameworks required.
2. **Indian Localization**:
   - Currency: Indian Rupee (₹ INR)
   - Identity: PAN / Aadhaar
   - Phone format: 10-digit Indian mobile standard
   - Regulatory notices: Reserve Bank of India (RBI) sandbox disclaimer & DPDP Act compliance.
3. **Form Validation**: Client-side validation ensuring valid email formatting, required fields, and interactive focus highlighting.
4. **Resilient Submission Handler**:
   - Seamlessly handles live web hosting (`http://` / `https://`) via standard form POST with 302 redirect.
   - Gracefully handles local `file:///` evaluation with asynchronous `fetch` fallback.
5. **Interactive Modals**: In-page modal dialogs for Terms & Conditions and Privacy / Data Protection policies.

---

## 💻 Running the Demo Locally

Simply open `index.html` in any modern web browser, or launch a lightweight local server:

```bash
# Python 3
python -m http.server 8000
```
Then navigate to `http://localhost:8000`.

---

## 🌐 Deploying to GitHub Pages

1. In your GitHub repository, navigate to **Settings** &gt; **Pages**.
2. Under **Build and deployment** &gt; **Branch**, select `main` and folder `/ (root)`.
3. Click **Save**.
4. Your application will be live at:
   `https://<username>.github.io/<repository-name>/`

---

## 📄 License & Disclaimer

*Disclaimer: This website is strictly for demonstration purposes simulating digital retail banking in India. All submitted information is handled within an isolated demonstration sandbox.*
