# BloatMonster legal pages

This is a standalone, dependency-free static site for BloatMonster's Privacy Policy and Terms of Use. Each document contains English and Traditional Chinese in one page, so the public URLs remain stable:

- `/privacy/`
- `/terms/`

## Draft status

The pages are **not ready to publish**. Replace `[OPERATOR_NAME]`, `[CONTACT_EMAIL]`, and `[EFFECTIVE_DATE]` with confirmed details. Review the data-processing statements against the release build and RevenueCat configuration. Then remove the visible draft labels and `noindex` metadata from all pages.

## Publish with GitHub Pages

Create a **public** repository for this standalone project in the intended GitHub account. Push this directory as the repository root. In repository **Settings → Pages**, select **Deploy from a branch**, `main`, and `/(root)`. GitHub Pages will then serve `index.html`, `privacy/index.html`, and `terms/index.html`. Record the actual URL shown by GitHub Pages and verify both document links in a signed-out browser before adding them to BloatMonster or App Store Connect.

The Apple standard licensed-application EULA remains a separate App Store setting unless a custom EULA is submitted in App Store Connect. These self-authored Terms of Use are intended as the app's publicly linked service terms.

No dependencies or build step are required.
