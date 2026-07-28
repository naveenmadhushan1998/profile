# Naveen Siriwardhana — Portfolio & IT Tools Lab

Personal portfolio and a collection of free, browser-based utility tools built by **Naveen Siriwardhana**, Senior System & Infrastructure Engineer. Hosted entirely as a static site on **GitHub Pages**.

🔗 **Live Site:** https://YOUR-USERNAME.github.io/

## About

This site is a single-page portfolio profile combined with a growing lab of small, fast, ad-free tools. Every tool runs 100% client-side in the browser — no backend, no data collection, no tracking. Some tools include Sinhala-language UI and outputs, tailored for Sri Lankan users (tax rates, CEB electricity slabs, NIC decoding, etc.).

## 🧰 Tools Included

| Tool | File | Description |
|---|---|---|
| Sri Lanka Salary Tax Calculator | `tax-calculator.html` | APIT / income tax calculation using current IRD slab rates |
| CEB Electricity Bill Calculator | `ceb-calculator.html` | Estimates monthly electricity bill using CEB domestic tariff slabs |
| Sri Lanka NIC Decoder | `nic.html` | Converts old ↔ new NIC formats and extracts DOB, age, gender |
| Age & Birthday Calculator | `age-calculator.html` | Exact age breakdown and birthday countdown |
| BMI & Fitness Calculator | `bmi-fitness-calculator.html` | BMI, estimated daily calories, and health advice (Sinhala) |
| Loan / EMI Calculator | `loan-emi-calculator.html` | Monthly installment calculator for housing/vehicle/personal loans |
| Unit Converter | `unit-converter.html` | Length, weight, data, and currency conversions |
| Password Generator | `password-generator.html` | Secure password generator with strength meter |
| Subnet Calculator | `subnet-calculator.html` | IPv4 CIDR subnet, mask, and host-range calculator |
| Image Compressor | `image-compressor.html` | Client-side image resize & compression tool |
| Countdown Timer | `countdown-timer.html` | Countdown to any custom event date/time |
| Online Stopwatch | `stopwatch.html` | Stopwatch with lap timer and keyboard shortcuts |
| QR Code Generator | `qr-generator.html` | Generates custom QR codes from text/URLs |
| WiFi QR Code Generator | `wifi-qr-generator.html` | Generates scannable WiFi connection QR codes |

## 🛠️ Tech Stack

- HTML5, vanilla JavaScript
- [Tailwind CSS](https://tailwindcss.com/) (via CDN)
- [Font Awesome](https://fontawesome.com/) icons
- [QRCode.js](https://davidshimjs.github.io/qrcodejs/) for QR generation
- [HLS.js](https://github.com/video-dev/hls.js/) for live video streaming
- Google Fonts — Plus Jakarta Sans & JetBrains Mono

## 📁 Project Structure

```
├── index.html                  # Main profile / landing page
├── tools.html                  # Tools index
├── 404.html                    # Custom error page
├── robots.txt
├── sitemap.xml
├── *.html                      # Individual tool pages
└── profile.jpg
```

## 🚀 Running Locally

No build step required. Clone the repo and open `index.html` directly in a browser, or serve it locally:

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPO.git
cd YOUR-REPO
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## 📄 License

This project is shared for personal/portfolio purposes. Feel free to reference the code for learning, but please don't republish it as your own.

## 📬 Contact

Built and maintained by **Naveen Siriwardhana**.
