# Privacy policy — BrandSync – Figma to After Effects

Last updated: November 24, 2026.

This policy covers the BrandSync Figma plugin and its local design-transfer workflow with the compatible BrandSync After Effects extension. It does not cover separate third-party account, purchasing or licensing services.

## What data is processed

BrandSync processes selected Figma designs, including layer names, text, geometry, styling and rendered image assets, to prepare them for import. While the plugin is open, it prepares the current selection. Design content is sent to After Effects only when you choose **Send to After Effects**. Alternatively, choose **Download JSON** to export a file locally.

## Local communication

The plugin communicates with the compatible BrandSync After Effects extension at `http://localhost:38471` on the same computer. The connection uses a pairing code and token. Local HTTP is not encrypted. The Figma plugin does not use a developer-hosted backend, require a separate BrandSync account, upload designs to a remote BrandSync server, or use analytics or advertising endpoints.

## Storage and retention

Pairing tokens are stored using Figma clientStorage when available and local settings in the compatible After Effects extension. The companion also stores import preferences. The plugin holds prepared designs in memory while running. Downloaded JSON files are stored in a location you control.

The compatible After Effects extension may retain PNG fallback assets and import-job files under `MotionBrand/FigmaImportAssets` in your user home directory. Imported designs also become part of the After Effects projects you save. These files can remain until you delete them. Deleting assets linked to a project can break its footage links.

## Access, sharing and your choices

The plugin does not transmit your design content to the BrandSync developer. Local files remain accessible according to your computer's access permissions. You can close the plugin, disconnect or re-pair, reset pairing in After Effects, and manage downloaded files and local assets.

If you contact support, the developer receives the email address, message and any files you voluntarily provide to respond to your request. Please avoid sending confidential files unless necessary. Contact support with questions about support correspondence or requests concerning your personal data.

Figma, Adobe and aescripts + aeplugins are independent services with their own terms and privacy practices.

## Contact

For privacy questions, personal data requests or technical support, email **oproiu.ionut@gmail.com**.

## Updates

This policy will be updated if the Figma plugin's data handling changes.
