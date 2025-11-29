# Contributing to CollectiVAI

Thank you for your interest in contributing to **CollectiVAI**! 🙌  

CollectiVAI is an independent project exploring **democratic, human-centred AI**  
with a strong European focus. This document describes how to contribute across  
the repositories under the `collectiv-ai` organisation.

---

## 1. Ways to contribute

You can help in many ways:

- 🐛 **Report bugs** – problems in the app, docs or scripts  
- 💡 **Suggest features** – ideas for the App, Chain, website or docs  
- 📚 **Improve documentation** – fix typos, clarify sections, add examples  
- 🧪 **Test & give feedback** – especially for the iOS/macOS app and docs  
- 🌍 **Civic use cases** – ideas from cities, universities, NGOs, civic tech  
- 🔐 **Security & ethics review** – feedback on security and governance aspects

You do **not** need to be an AI expert. Clear, honest feedback is already valuable.

---

## 2. Repositories

Main repos:

- **Org profile & meta:** `.github`  
- **App (iOS / iPadOS / macOS):** `collectiv-ai-app`  
- **Cosmos App-Chain:** `collectiv-ai-app-chain`  
- **Website & docs:** `collectiv-ai.github.io`  
- **Branding:** `collectiv-ai-branding`  
- **Business plan & strategy:** `collectiv-ai-business`  
- **Founder profile & portfolio:** `collectiv-ai-about-founder`  
- **Sponsors & partners:** `collectiv-ai-sponsors`

Each repository may have its own `README`, `CONTRIBUTING` or `SECURITY` details.  
Please read them first.

---

## 3. How to open issues

1. **Search first**  
   Check existing issues to avoid duplicates.

2. **Use templates (if available)**  
   Choose “Bug report” or “Feature request” where provided.

3. **Be specific**  
   - What happened? What did you expect?  
   - Steps to reproduce (if it’s a bug)  
   - Environment (e.g. iOS version, macOS version, device, etc.)

4. **Be respectful**  
   Follow the [Code of Conduct](./CODE_OF_CONDUCT.md).

---

## 4. How to submit pull requests

1. **Fork** the repository.  
2. **Create a branch** for your change:  
   `feature/…` or `fix/…` (for example `feature/add-en-docs`).  
3. Make small, focused changes where possible.  
4. Ensure the project still builds / tests (if applicable).  
5. Write a clear PR description:
   - What you changed  
   - Why you changed it  
   - Any open questions or follow-ups

6. Link related issues with `Fixes #123` when appropriate.

---

## 5. Coding & style guidelines (high-level)

These may be refined per repo, but in general:

- **Swift / SwiftUI (App)**  
  - prefer clear, descriptive names  
  - keep views small and composable  
  - avoid premature optimisation; clarity first

- **Markdown / docs**  
  - use short sections, headings and lists  
  - keep EN/DE structure parallel where possible  
  - explain concepts in accessible language (not only for experts)

- **Shell scripts / infrastructure**  
  - comment non-obvious commands  
  - avoid destructive actions by default  
  - never hardcode secrets or private data

---

## 6. Security & sensitive topics

CollectiVAI touches on:

- democracy & governance,  
- AI safety & ethics,  
- security & infrastructure.

Please:

- avoid sharing sensitive personal data in issues/PRs,  
- **never** publish secrets, API keys or access tokens,  
- report security issues via the process described in  
  [`SECURITY.md`](./SECURITY.md).

---

## 7. License & attribution

Each repository has its own `LICENSE` file. By contributing, you agree that:

- your contributions will be licensed under the repository’s licence,  
- you have the right to contribute the code/content.

If in doubt, ask in an issue before you start.

---

## 8. Questions?

If you’re unsure where to start or how to help:

- open a **discussion / issue** in the relevant repository, or  
- contact: **info@collectivai.org**

Thank you for helping to build democratic, human-centred AI. 💛💙
