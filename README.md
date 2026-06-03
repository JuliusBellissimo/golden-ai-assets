# Golden AI Public Asset Bucket

This repository is the public asset bucket for Golden AI / Hermes automation.

Hermes creates approved social media images locally. This repo hosts public image URLs used for Meta / Instagram publishing, including image assets that Instagram Graph API can fetch over HTTPS.

## Safety rules

This repository must never contain:

- API keys
- Access tokens
- `.env` files
- Private customer data
- Secrets or credentials of any kind
- Private screenshots, documents, or internal-only files

Only approved public social media image assets should be committed here.

## Golden AI

Golden AI helps small businesses with pages, posts, replies, leads, and workflows.

## Hermes

Hermes is the AI operator helping prepare content and automation under human direction.

## Typical asset path

```text
instagram/YYYY-MM-DD/post-image-name.jpg
```

The raw GitHub URL for an approved image can be used as the public `image_url` for Meta / Instagram publishing.
