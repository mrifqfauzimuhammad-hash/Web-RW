---
name: Warga & Tata Kelola Digital
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2fd'
  on-surface: '#131b2e'
  on-surface-variant: '#414750'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#717881'
  outline-variant: '#c0c7d1'
  surface-tint: '#05639b'
  primary: '#004974'
  on-primary: '#ffffff'
  primary-container: '#006199'
  on-primary-container: '#b7d9ff'
  inverse-primary: '#97cbff'
  secondary: '#0b658a'
  on-secondary: '#ffffff'
  secondary-container: '#8fd4fe'
  on-secondary-container: '#005d7f'
  tertiary: '#735c00'
  on-tertiary: '#ffffff'
  tertiary-container: '#cea710'
  on-tertiary-container: '#4e3e00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#cee5ff'
  primary-fixed-dim: '#97cbff'
  on-primary-fixed: '#001d33'
  on-primary-fixed-variant: '#004a77'
  secondary-fixed: '#c4e7ff'
  secondary-fixed-dim: '#8acff8'
  on-secondary-fixed: '#001e2d'
  on-secondary-fixed-variant: '#004c69'
  tertiary-fixed: '#ffe086'
  tertiary-fixed-dim: '#ecc232'
  on-tertiary-fixed: '#231b00'
  on-tertiary-fixed-variant: '#574500'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system establishes a civic-tech experience engineered specifically for neighborhood governance (*Rukun Tetangga / RT*). It bridges two distinct user cohorts: community administrators (Ketua RT, sekretaris, and bendahara) who require dense data management, and everyday citizens across diverse age groups who need instantaneous access to services, announcements, and emergency workflows.

The visual style embraces **Corporate / Modern Civic Precision** with human warmth. It avoids cold bureaucratic stiffness in favor of institutional trustworthiness, neighborhood hospitality (*gotong royong*), and unyielding functional clarity. 

Key attributes include:
- **Trustworthy & Authoritative:** High-contrast structure, crisp administrative containers, and structured hierarchy reassure residents regarding their official identity records and community finances (*kas warga*).
- **Accessible & Calming:** Clean, airy surfaces counter the administrative complexity of civil registry forms (*Kartu Keluarga*, *surat pengantar*).
- **Action-Oriented Vigilance:** Deliberate, high-visibility contrast nodes designate urgent actions such as emergency broadcast alerts (*tombol panik/siskamling*).

## Colors

The palette balances institutional integrity with high-visibility civic signaling:

- **Deep Ocean Blue (`#006199`):** The primary anchor. Applied to top navigation chrome, administrative sidebars, primary interactive controls, and authoritative headline typography. It conveys institutional legitimacy and official endorsement.
- **Sky Soft Blue (`#8ACFF8`):** The functional secondary tone. Deployed as subtle boundary tints, selected state backdrops, informational badges, and auxiliary graphs within census analytics.
- **Sunlight Yellow (`#F4EB6C`):** The operational accent. Dedicated to pending approval workflows, in-progress document generation notices, and transitional resident verification notices.
- **Amber Gold (`#FFD444`):** The alert and treasury accent. Used for high-priority citizen alerts, security panic triggers, prominent call-to-actions, and financial balance highlights (*iuran RT*).
- **Neutrals & Surfaces:**
  - Base Canvas: `#F8FAFC` (Clean warm slate tint providing glare-free reading for long administrative sessions).
  - Surface Card: `#FFFFFF`.
  - Border Slate: `#E2E8F0` for structural gridlines and divider borders.
  - Text Slate: `#0F172A` for primary headlines and data values; `#334155` for descriptive copy and table metadata; `#64748B` for placeholders and tertiary notes.

## Typography

The typography pairings unify identity with operational density:

- **Plus Jakarta Sans** is designated for headlines, metrics counters, and document title banners. Developed with Indonesian contemporary typography heritage in mind, it provides clean, geometric presence and warmth.
- **Inter** handles data tables, forms, citizen census lists, and long administrative instructions. Its robust x-height, contextual alternates, and tabular figures ensure that national identification numbers (*NIK*), family card numbers (*No. KK*), and currency amounts (*Rp*) remain legible without optical misalignment.

### Usage Standards
- Enable `tnum` (tabular numbers) globally on all numerical data cells, financial records, and citizen census counters.
- Set uppercase tracking (`letter-spacing: 0.05em`) strictly on small metadata labels and system status markers.

## Layout & Spacing

The system implements a flexible responsive grid system:

- **Desktop (1024px+):** 12-column layout with 24px (`1.5rem`) gutters and a permanent 260px administrative navigation sidebar. The content canvas is capped at a maximum width of 1440px to retain table scanability.
- **Tablet (768px - 1023px):** 8-column layout with 20px gutters. The primary navigation condenses to an icon-rail or sticky top app-bar.
- **Mobile (< 768px):** 4-column layout with 16px (`1rem`) gutters and 16px page margins. Bottom navigation bar replaces sidebars for resident workflows.

Spatial cadence relies strictly on multiples of 4px/8px:
- Dense table rows and data cells utilize `space-xs` and `space-sm` for horizontal and vertical padding.
- Card interiors and modal document surfaces standardize on `space-lg` (`1.5rem`) desktop and `space-md` (`1rem`) mobile.

## Elevation & Depth

To preserve the utility and speed of an administrative system, visual depth relies on **crisp structural boundaries combined with soft, low-contrast ambient drops**. Heavy, blurry drops are avoided to maintain data clarity.

- **Level 0 (Flat Base):** Background canvas (`#F8FAFC`).
- **Level 1 (Card & Module Surfaces):** Surface `#FFFFFF` encased in a 1px border of `#E2E8F0`, paired with an ambient shadow: `0 1px 3px 0 rgba(15, 23, 42, 0.04), 0 1px 2px -1px rgba(15, 23, 42, 0.03)`. Used for metric cards, table containers, and census directory lists.
- **Level 2 (Interactive Floating & Menus):** Surface `#FFFFFF` surrounded by `0 4px 6px -1px rgba(0, 97, 153, 0.06), 0 2px 4px -2px rgba(15, 23, 42, 0.05)`. Used for dropdown filter menus, date pickers, and hovering action toolbars.
- **Level 3 (Modals & Overlays):** Surface `#FFFFFF` with `0 20px 25px -5px rgba(15, 23, 42, 0.1), 0 8px 10px -6px rgba(15, 23, 42, 0.04)` over a backdrop tint of `#0F172A` at 40% opacity. Used for the official Surat Pengantar generator modal and citizen identity verification screens.
- **Urgent / Panic Elevation:** Specific to emergency modules. Accompanied by a 2px outward amber glow: `0 0 0 4px rgba(255, 212, 68, 0.35)`.

## Shapes

The design system adopts a balanced **Rounded (`roundedness: 2`)** geometry. This introduces modern ergonomics without eroding the gravitas of legal and community administration documents.

- **Base Radius (`0.5rem` / 8px):** Standard interactive elements including input fields, standard buttons, select pickers, and filter pills.
- **Large Radius (`rounded-lg` / `1rem` / 16px):** Metric widgets, citizen profile summary cards, data grid containers, and popovers.
- **Extra-Large Radius (`rounded-xl` / `1.5rem` / 24px):** Dialog modals, document preview sheets, and the citizen mobile quick-action dock.
- **Full Radius (`pill` / 9999px):** Status badges (*Aktif*, *Pindah*, *Meninggal*), citizen avatar badges, and emergency panic buttons.

## Components

### Buttons
- **Primary:** Background `#006199`, text `#FFFFFF`, radius `0.5rem`, font `label-lg`. Hover: `#004e7c`. Focused with `2px` offset outline in `#8ACFF8`.
- **Secondary / Accent (Financial / Export):** Background `#FFD444`, text `#0F172A`, font weight 600. Ideal for prominent calls-to-action like "Bayar Iuran" or "Buat Surat".
- **Outline / Ghost:** Border `1px solid #E2E8F0`, surface `#FFFFFF`, text `#334155`. Hover: background `#F8FAFC`.

### Chips & Status Badges
- **Verified / Aktif:** Background `rgba(0, 97, 153, 0.1)`, text `#006199`, border `1px solid rgba(0, 97, 153, 0.2)`.
- **Pending / Diproses:** Background `#F4EB6C` at 35% opacity, text `#785900`, border `1px solid #F4EB6C`.
- **Alert / Tunggakan / Darurat:** Background `rgba(255, 212, 68, 0.25)`, text `#8A5800`, border `1px solid #FFD444`.

### Input Fields & Filter Bars
- Neutral input container with `#FFFFFF` background, `1px solid #CBD5E1` border, 8px radius, height 40px (desktop) or 44px (mobile).
- Focused state transitions border to `#006199` with a subtle box-shadow ring `0 0 0 3px rgba(138, 207, 248, 0.35)`.
- Integrated search bar features prefixed icon slots and trailing quick-clear buttons specifically sized for scanning NIK, Nama Warga, or No. Rumah.

### Data Tables
- Clean zebra-free layout on `#FFFFFF`.
- Table header features `#F8FAFC` background, uppercase tracking in `label-sm`, text color `#64748B`, with 1px border bottom `#E2E8F0`.
- Data rows have minimum height of 48px with numeric tabular font alignment and right-aligned administrative action triggers.

### Citizen Profile Cards
- Compound card with `#FFFFFF` base, `1rem` radius, and 1px `#E2E8F0` border.
- Features a header block accented by `#8ACFF8` tint, a circular avatar photo frame, house number tag (`Blok A / No. 12`), and citizen status pill.

### Emergency Panic Alert Banner (Siskamling / Keamanan)
- Full-width callout using `#FFD444` background with a strong `#0F172A` text contrast.
- Includes a pulsing icon indicator, immediate timestamp, house address link, and an assertive single-click confirmation trigger.

### Document Generator Modal (Surat Pengantar RT)
- Centered overlay modal with a simulated A4 preview paper pane (`#FFFFFF` with inset shadow) on the right and an intuitive form generator on the left.
- Completed with one-click official digital signature (*Tanda Tangan Digital / QR Code*) and print-ready PDF export options.