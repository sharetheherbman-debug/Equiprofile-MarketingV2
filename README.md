# EquiProfile MarketingV2 — LEGACY DUPLICATE (DO NOT DEPLOY)

This repository is an obsolete EquiProfile-era duplicate and is **not** part of the current production source of truth.

## Canonical EquiProfile Core

Use:

`sharetheherbman-debug/Equiprofile-Marketing`

Despite its historical repository name, that repository is the authoritative EquiProfile Core containing Management, Academy, Shop Coming Soon, authentication, entitlements and the Core-side Marketing connector.

## Canonical Marketing engine

Use:

`sharetheherbman-debug/Amarktai-MarketingV21`

That is the single reusable Marketing engine. EquiProfile connects to it through the signed Application Connector and uses the embedded SSO deployment profile.

## Do not deploy this repository

This legacy tree contains older EquiProfile implementation and documentation, including superseded deployment instructions and obsolete domain references. It must not be used to build, deploy, migrate, restore, or create a second EquiProfile/Marketing production stack.

The repository remains only as historical source until final repository archival/retention work is completed.

## Current canonical domains

- EquiProfile Management: `https://equiprofile.online`
- EquiProfile Academy: `https://academy.equiprofile.online`
- EquiProfile Shop: `https://shop.equiprofile.online`
- EquiProfile Marketing: `https://marketing.equiprofile.online`
- AmarktAI Network: `https://amarktai.co.za`

Never introduce `amarktai.com` into current production.
