# Kganya Wellness Center 💗

> **You Are Not Alone.** *Kganya* means "light" in Sepedi/Sesotho.

An inclusive, anonymous wellness companion for **moms, dads, and anyone feeling low in South Africa**. Kganya pairs a gentle chatbot with self-care tools, anonymous peer-group entry points, and always-visible crisis helplines.

> ⚠️ **Not a diagnostic or therapy tool.** Kganya offers wellness support only and encourages professional help. This is a **portfolio concept / demo**, not a live clinical product.

---

## Why Kganya?

Postnatal depression isn't only a mothers' issue. Dads experience it too, often silently, and men in South Africa are less likely to seek help than women because of stigma, social norms, and access. General low mood cuts across gender, age, and parenthood. Kganya is designed to lower the barrier to reaching out: no login, no profile, no judgment.

## Features

- **Chat companion.** A friendly assistant that responds to how you're feeling (low mood, sleep, baby crying, bonding, work or money stress, relationship strain, guilt, anger) and offers quick-reply chips to keep the conversation easy.
- **5-question mood check-in.** A short, gentle check-in covering enjoyment, anxiety, low mood, connection, and safety. It is not a scored diagnosis.
- **Self-care toolkits** for three audiences:
  - **Moms:** night-feed breathing, skin-to-skin pauses, gentle stretches
  - **Dads / men:** after-work reset, phone-free walk, how to talk to your partner, shoulder-drop reset
  - **Everyone:** 5-4-3-2-1 grounding, hydration check, private journal prompts
- **Anonymous peer-group entry points:** New Moms (0-12 months), New Dads & Paternal Wellness, Men's Circle, General Depression Support, Partners & Family, and Young Adults Stress. Groups need a nickname only: no name, photo, or email.
- **High-risk language detection.** If a message or the safety question signals risk, the conversation pauses and shows helplines immediately, alongside a grounding exercise and a nudge to reach a trusted person.
- **Human agent handoff.** Asking for "an agent" or "a counselor" surfaces WhatsApp and phone options, plus a simulated volunteer message form.
- **Always-visible safety bar** with SADAG, Lifeline SA, and WhatsApp shortcuts pinned to the bottom of the page.
- **Responsive design** with a warm pink palette, built to work on phones and desktops.

## South African helplines

| Service | Contact | Notes |
| --- | --- | --- |
| SADAG Suicide Crisis Line | 0800 567 567 | 24h, free |
| Lifeline SA | 0861 322 322 | 24h |
| SADAG WhatsApp | 076 146 8416 | Chat on WhatsApp |
| Emergency services | 112 | From any phone |

If you or someone near you is in immediate danger, call **112**.

## Tech stack

- **React** (single-page app)
- **Tailwind CSS** v3 for styling
- **Inter** typeface with system fallbacks
- Bundled into **one self-contained HTML file**, with no backend, no build step, and no external API calls

The chatbot is **rule-based** (keyword and intent matching), not powered by a language model.

## Getting started

There's nothing to install.

1. Clone or download this repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo>.git
   cd <your-repo>
   ```
2. Open the HTML file in any modern browser:
   ```bash
   open "Mindcare-Website (3).html"     # macOS
   xdg-open "Mindcare-Website (3).html" # Linux
   start "Mindcare-Website (3).html"    # Windows
   ```

### Host it on GitHub Pages (optional)

1. Rename the HTML file to `index.html`.
2. In your repo, go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Your site will be live at `https://<your-username>.github.io/<your-repo>/`.

## Project structure

```
kganya-wellness-center/
├── Mindcare-Website (3).html   # The complete app (React + Tailwind, bundled)
└── README.md
```

## Privacy and limitations

- **Demo only.** This version does not save your answers or store any data.
- A real deployment would need encrypted, opt-in storage, clear consent controls, and moderated groups.
- The support-group joins, live agent chat, and volunteer message form are **simulated** in this demo.
- Some figures shown on the page (such as the "light seekers today" counter and the sample testimonial) are illustrative placeholders.
- Kganya does not replace a clinic, counselor, or doctor. If low mood lasts more than two weeks or affects daily life, please speak to a professional or a trusted person.

## Roadmap ideas

- Real anonymous, moderated peer groups
- Live volunteer chat
- Encrypted, opt-in mood tracking
- Additional South African languages (isiZulu, isiXhosa, Sepedi, Afrikaans)
- Clinic and support-service locator

## Contributing

Suggestions and improvements are welcome. Open an issue to discuss what you'd like to change, or submit a pull request. Please keep contributions sensitive to the mental-health context of the project.

## License

Add your preferred license here (for example, [MIT](https://choosealicense.com/licenses/mit/)).

---

*Kganya • Light • You belong here.* 💗
