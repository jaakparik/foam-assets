# Foam Assets

A comprehensive asset library for the Foam platform, containing brand assets, icons, avatars, photos, videos, and creator metadata for development, testing, and production use.

## What is this?

This repository contains all static assets and metadata used by the Foam platform—a talent and creator management system. It includes everything from brand logos and UI icons to creator profiles and sample media content.

## Who is this for?

- **Developers** building features that need assets, icons, or sample data
- **Designers** creating mockups and prototypes
- **QA Engineers** testing with realistic creator profiles and media
- **Product Teams** demonstrating features with sample content

## What's included?

### 🎨 **Brand Assets**
- Foam brand logos (light/dark variants, filled/outline styles)
- Corporate logos for major brands (Nike, Apple, Google, etc.)

### 🖼️ **Icons**
- **Color icons**: Platform icons (Instagram, TikTok, YouTube, etc.) and feature icons
- **Regular icons**: Monochrome UI icons for general interface use

### 👤 **Avatars**
- Animal avatars (33 unique illustrations)
- Male avatars (28 photos)
- Female avatars (16 photos)

### 📸 **Photos & Videos**
- Editorial photos (3:4 and 4:3 aspect ratios)
- Coffee-themed content (images, logos, videos)
- Nike-branded images
- Social media video clips (portrait and landscape)

### 📊 **Metadata**
- **45 creator profiles** with bios, social handles, follower counts, and links
- **CSV dataset** with 100+ rows of analytics data including:
  - Demographic breakdowns
  - Engagement metrics
  - Platform-specific statistics
  - Performance analytics

### 🔤 **Fonts**
- Founders Grotesk font family (all weights and styles)

## Quick Start

All assets are hosted at: `https://proto.dev.foam.io/assets/`

### Example Usage

```html
<!-- Brand logo -->
<img src="https://proto.dev.foam.io/assets/brand/foam_logo_filled_text_light.svg" alt="Foam Logo" />

<!-- Avatar -->
<img src="https://proto.dev.foam.io/assets/avatars/female/female_young_adult_fashion_influencer.jpeg" alt="Creator Avatar" />

<!-- Icon -->
<img src="https://proto.dev.foam.io/assets/icons/color/Instagram.svg" alt="Instagram" />
```

## Documentation

- **[ASSETS_README.md](./ASSETS_README.md)** - Complete asset catalog with URLs and usage guidelines
- **[METADATA_README.md](./METADATA_README.md)** - Detailed creator profiles and metadata

## Repository Structure

```
assets/
├── avatars/          # Profile images (animals, male, female)
├── brand/            # Foam brand logos
├── icons/            # UI and platform icons
├── logos/            # Corporate brand logos
├── photos/           # Editorial and marketing photos
├── videos/           # Video content
├── fonts/            # Font files
├── talents.ts        # TypeScript talent data with Instagram metrics
├── fake_talent_dataset_100.csv  # Analytics dataset
└── ASSETS_README.md  # Detailed asset documentation
```

## Usage Guidelines

- **Avatars**: Use for profile images, not for general photos
- **Photos**: Maintain original aspect ratios (3:4 or 4:3)
- **Icons**: Standard size is 16x16px, can scale up to 32px
- **Brand logos**: Use light variants on dark backgrounds, dark variants on light backgrounds
- **Videos**: Portrait for TikTok/Instagram Stories, landscape for YouTube

## Contributing

This is a curated asset library. For additions or modifications, please follow the existing naming conventions and update the relevant README files.

## License

See repository license file for details.

---

**Base URL:** `https://proto.dev.foam.io/assets/`
