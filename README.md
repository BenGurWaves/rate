# RATE — Precision Drift Calculator

A high-precision drift calculator designed for horologists and watchmakers to instantly determine the daily rate (seconds per day) of mechanical movements based on short-term observational variances.

## Concept

**Radical Metaphor:** The interface is a precision instrument—a single obsidian block housing a mechanical movement. The user is the watchmaker, adjusting regulation screws (the click-to-adjust inputs) to observe the balance wheel's response (the real-time rate calculation).

**Spatial Grammar:** Grid-locked precision. Every element aligns to a strict mathematical grid, like a watch face. The cursor becomes a loupe—magnifying focus on active elements. Transitions mimic the crisp mechanical click of a column-wheel chronograph.

## Features

- **Real-time Calculation:** Instant daily rate (s/d) computation using the formula: `(drift / duration) * 24`
- **Click-to-Adjust Inputs:** Precision controls mimicking watch crown operation
- **Visual Gauge:** COSC tolerance indicator (-4s to +6s) with color-coded precision feedback
- **Calculation Log:** Tracks last 5 regulation attempts for comparison
- **Living Texture:** Organic particle system creating depth in the obsidian chassis
- **Custom Cursor:** Bespoke loupe-style cursor that reacts to interactive elements
- **Elegant Loader:** Mechanical gear animation setting the precision tone
- **Keyboard Support:** Arrow keys for rapid adjustment (Shift for 1.0 steps)

## Palette

- **Obsidian Black (#080808):** Primary chassis—matte enamel watch dial finish
- **Titanium Satin (#A0A0A0):** Indices, rules, input boundaries—satin, not shiny
- **Optical White (#FFFFFF):** Data readouts—maximum readability against obsidian

## Typography

**Space Grotesk** (serving as Akzidenz-Grotesk proxy)—the gold standard for watchmaking: neutral, timeless, perfectly balanced. Tight tracking, laser-etched appearance.

## Usage

1. **Adjust Time Drift:** Use +/- buttons or arrow keys (up/down) to set observed gain/loss in seconds
2. **Set Duration:** Use +/- buttons or arrow keys (left/right) to set observation period in hours
3. **Read Result:** Daily rate (s/d) displays instantly with COSC gauge feedback
4. **Compare:** Check the log window to track multiple regulation attempts
5. **Reset:** Clear all data to start fresh

## Technical Stack

- Single-file HTML/CSS/JS
- No build process required
- Vanilla JavaScript (no frameworks)
- Google Fonts (Space Grotesk)
- Canvas API for living texture

## Deployment

### Cloudflare Pages

**Build Settings:**
- **Framework preset:** None
- **Build command:** (leave empty)
- **Build output directory:** `/` (root)
- **Root directory:** `/` (root)

**Environment Variables:** None required

**Custom Domain:** Configure after deployment via Cloudflare dashboard

## License

Made by Velocity — velocity.calyvent.com
