# A Note for Usha Ma'am — HRBP Role Portfolio

A single-page portfolio companion prepared as an internal communication for **Usha Srivastava, HR Head, Vodafone Idea Limited**, on the AGM — HRBP Operations (APT) conversation.

> **Not a public communication.** This site is intended for internal use in a one-to-one meeting with Vi HR leadership.

---

## Live URL

Once deployed via GitHub Pages, the site will be available at:

```
https://yogi2022.github.io/HRBP_role_v1/
```

---

## What's inside

A single-file, dependency-free static site with nine narrative sections:

1. **Hero** — a direct opening addressed to Usha Ma'am
2. **The Note** — a short letter framing why this portfolio exists
3. **Journey** — timeline through Vi (CODE Hyderabad → Corp Mumbai → SNOC Hyderabad)
4. **HR Thread** — the consistent HR interest since BITS Pilani (2022)
5. **Reading Your Work** — the differentiator: a section-by-section engagement with Usha's own published *"Bridging Geographies: HR Insights from North India to South India"* framework, plus her CDSW digital-wellbeing work
6. **APT Context** — the circle-specific setup, anchored in recent Vi Q4FY26 milestones
7. **Bridge** — where tech + people meet, with the QR-feedback initiative (with Ramana Pariti Sir) called out as a small proof point
8. **Honest Gap** — an explicit acknowledgment of the HRBP experience gap
9. **90-Day Plan** — Listen / Diagnose / Contribute, written as a learning plan not a proposal
10. **Request** — the same two-part ask from the original email, in the same humble tone

---

## Design principles

- **Vi brand-aligned but not logo-heavy** — Vi red `#EE1C25` + Vi yellow `#FDCB05` + a subtle *"Vi"* wordmark with the trademark yellow dot. No copyrighted logo reproduction.
- **"Together for Tomorrow"** referenced in the footer.
- **Restraint over flash** — the tone from the original email is preserved throughout. This is a document, not a promotional site.
- **Typography** — Fraunces (serif) for headlines, Inter (sans) for body. Both from Google Fonts, loaded async.
- **Zero external dependencies** — no build step, no framework, no CDN scripts, no analytics.
- **Mobile responsive** — reads cleanly on a phone in case Usha Ma'am opens the link on mobile.
- **Print-friendly** — a `@media print` stylesheet is included so the site prints as a clean document if needed.
- **Accessible** — semantic HTML, respectable contrast ratios, keyboard-navigable smooth-scroll.

---

## Deployment — one-time setup

**Step 1 — Push the file to the repo**

Place `index.html` at the root of `HRBP_role_v1`:

```bash
git add index.html README.md
git commit -m "Add HRBP portfolio companion page for Usha Ma'am"
git push origin main
```

**Step 2 — Enable GitHub Pages**

1. Open the repo on GitHub → **Settings** → **Pages** (left sidebar).
2. Under **Build and deployment → Source**, select **Deploy from a branch**.
3. Under **Branch**, select **`main`** and folder **`/ (root)`**. Click **Save**.
4. Wait ~30–60 seconds. Refresh the Pages settings page — a green banner will appear with the live URL: `https://yogi2022.github.io/HRBP_role_v1/`

**Step 3 — Verify**

Open the URL. Scroll through end-to-end on desktop, then on your phone. Test the nav anchor links.

**Step 4 — Share**

Copy the URL and share it once, personally, at the appropriate moment in your meeting with Usha Ma'am — not before.

---

## If you want to make changes

The entire site is one file: `index.html`. HTML, CSS, and JS are all inline. Common edits:

| Want to change | Where |
|---|---|
| Any wording | Search the section by heading text (`01 · My journey at Vi`, etc.) |
| Colours | The `:root` CSS variables at the top of the `<style>` block |
| Add / remove a section | Duplicate a `<section>` block; add a link to the `<ul class="nav-links">` |
| Update the 90-day plan | The `.plan-grid` inside `<section id="plan">` |

After any change, commit and push — Pages will redeploy automatically in under a minute.

---

## Content sources — verified from your uploaded files

Every claim on the page is grounded in one of the source documents you shared:

- **Your profile / experience** — Vi timeline (CODE Hyd → Corp Mumbai → SNOC Hyd), BITS MBA, TA for HRM & OB (3 semesters), MANAV HR Club, Quiet Quitting publication in IJOA/Emerald, Inkspire white paper 2nd place on Succession Planning, HiRe 2nd place at Interface 2022
- **JD_HRBP_file1.docx** — Role scope (300+ base employees, PD cycle, MIS/SAP reporting, statutory compliance, HR Shared Services coordination, cluster-level ER)
- **HRBP_role_interviewer1.docx** — Sheethal Preethi's context; CEO Abhijit Kishore's Q4FY26 statement (7 benchmark parameters, net positive subs since Feb 2026, 5G in 80+ cities, 4G to 48M+ population)
- **Usha_Srivastava_about_HRBP_role1.docx** — Her Bridging Geographies article (6 recommendations quoted verbatim in the "Reading Your Work" section) and her CDSW Advisory Group appointment on Digital Wellbeing
- **mail_send_VP-EVPs.docx** — The humble tone, the QR-feedback initiative with Ramana Pariti Sir, the exact framing of the two-part request

Nothing on the page has been fabricated or inferred beyond what these documents support.

---

*Prepared with care. Together for Tomorrow.*
