# NavBot documentation

The NavBot documentation site uses Mintlify and MDX. Its introduction and product links are based on the [NavBot website](https://navbot.com/).

## Content

- `docs.json`: site name, theme, navigation, branding, and support links.
- `index.mdx`: NavBot introduction and product families.
- `quickstart.mdx`: product selection and support resources.
- `logo/`, `favicon.png`, and `images/`: official NavBot brand and product assets.

Product questions and support requests go to [sales@navbot.com](mailto:sales@navbot.com).

## Local preview

Install Node.js 20.17 or later using a Mintlify-supported LTS release, then install the CLI:

```bash
npm i -g mint
```

From the directory containing `docs.json`, run:

```bash
mint dev
```

Open the local URL printed by the CLI, normally `http://localhost:3000`.

## Check changes

```bash
mint validate
mint broken-links
```

To check the current CLI guidance, run `mint instructions`. If your installed version does not support it, use `npx mint@latest instructions`.

## Publishing

Connect this repository to the separate NavBot project in Mintlify and install the Mintlify GitHub App for this repository. Changes pushed to the configured deployment branch trigger a new deployment. Review the result in the project's **Publishes** page.

## Content sources

- [NavBot](https://navbot.com/)
- [About NavBot](https://navbot.com/pages/about)
- [Kinatric D2](https://navbot.com/products/kinatric-d2)
- [Kinatric D2W](https://navbot.com/products/kinatric-d2w)
- [NavBot FAQ](https://navbot.com/pages/faq)

The local logo, favicon, and Kinatric D2 image are sourced from the official website. Keep model specifications and setup instructions tied to the relevant product's published resources.
