# Design System: Cupcode Hockey Management (Spanish Edition)

## 1. Visual Theme & Atmosphere
A high-performance, premium athletic interface for a Hockey Management platform. The aesthetic is "Elite Dark Mode" — professional, focused, and powerful. 
**Language: STRICTOR Spanish (Español) for all UI text.**

- **Density:** 6
- **Variance:** 7
- **Motion:** 6
- **Atmosphere:** Dark, Premium, Locker Room Elite.

## 2. Color Palette & Roles
- **Base Background:** #141726 (Deep void)
- **Panel Surface:** #1E2235 (Charcoal navy for cards/panels)
- **Primary Accent:** #E63428 (Intense Red from the logo)
- **Primary Text:** #FFFFFF (Elite White)
- **Secondary Text:** #8B92A9 (Steel Mist)
- **Subtle Borders:** #2A3050 (Deep structural lines)

## 3. Typography Rules
- **Display/Titles:** "Barlow Condensed Bold" (All-caps, tight tracking for impact).
- **Body/Labels:** "DM Sans" (Clean, high legibility).
- **Banned:** Inter, generic serifs.

## 4. Layout Principles (Desktop)
- **Split Screen:** 40% Left Panel (Form) / 60% Right Panel (Hero).
- **Left Panel:** Background #1E2235.
- **Right Panel:** Grayscale hockey hero image with a low-opacity red overlay. Dark gradient transition from the left panel. Dark vignette.
- **Divider:** 2px vertical line, gradient from Primary Accent (#E63428) to transparent.

## 5. Components & Copy (Spanish)
- **Logo Area:** Light logo over dark surface. Subtitle: "GESTIÓN DE LIGA HOCKEY" (Uppercase, light, wide spacing).
- **Form Heading:** "Iniciar Sesión" with a 32px x 3px red装饰 line.
- **Inputs:** 
  - Label above: "Usuario" / "Contraseña".
  - Placeholders: "Ingresa tu usuario" / "Ingresa tu contraseña".
  - Icons: User icon (right) and Eye-toggle (right of password).
  - Shape: 4px corners. Focus: Red border + Red glow.
- **Buttons:** 
  - Primary: "INICIAR SESIÓN" (Red fill, White bold caps, 52px height).
  - Secondary: "Recuperar Contraseña" (Ghost style, subtle border, gray text). Hover: Red border.
- **Badge:** "🔒 Acceso Seguro"
- **Footer:** "© Cupcode 2025"

## 6. Mobile Layout (< 768px)
- Hide right hero panel.
- Background: Hockey image with 85% dark overlay.
- Centered vertical layout for logo and form.

## 7. Interaction States
1. **DEFAULT:** Initial empty state.
2. **FOCUS:** Active "Usuario" field with #E63428 border and glow.
3. **ERROR:** Inline message: "Usuario o contraseña incorrectos".
4. **HOVER:** Primary button with active hover effect (shimmer or brightness shift).
