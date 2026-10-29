---
name: aziral-brand-frontend
description: Design or refine a brand-led frontend with real product content, multilingual layouts, touch interactions, and browser verification. Use for public product pages and branded interfaces; keep narrow component edits within their existing visual system.
---

# AZIRAL Brand Frontend

Turn the product's own material into a coherent interface. This is an original AZIRAL workflow, independent of Leonxlnx's Taste Skill. It can run alone or complement an art-direction skill already available in the environment.

## Establish the brief

Inspect the target route, stack, current design, translations, and available assets. Keep the requested scope. A refinement preserves the established visual identity; a redesign can choose a new direction while preserving product facts and working behavior.

Record the decisions that affect design:

- The audience and the primary action on this surface.
- Verified claims, their source in the project, and facts still awaiting confirmation.
- Existing brand constraints, authentic imagery, and what each asset may represent.
- Required languages and whether translations already exist.
- Interactions that need hover, dragging, touch, keyboard input, or motion.

Use [the brief template](references/brief-template.md) for a new page or substantial redesign. For a narrow edit, keep only the decisions it changes. Do not invent customer quotes, product capabilities, usage figures, or biographical facts to fill a layout.

## Choose a direction that fits the material

State one organizing idea grounded in the product. Explain how that idea determines the composition, typography, image treatment, and primary action. Prefer a small set of reusable tokens over styling each section independently.

When the user has chosen an aesthetic, develop it. When direction is open and meaningful alternatives exist, compare them through the product's content and purpose. Do not make the user choose arbitrary colors before the work can proceed.

Use supplied brand and product assets accurately. A decorative illustration can set a mood; a product screenshot must show the actual product or be labelled as a concept. If external imagery is needed, establish permission and keep its attribution with the asset.

## Design with the real language content

Use actual RU, EN, or KK strings where those languages are requested. Keep verified names and product names consistent. Record draft translations as drafts when a qualified review has not happened.

Let text determine component height. Test the longest real navigation label, action, field error, price label, and card title. Prefer flexible layout and natural wrapping. A language switch should retain the corresponding page when that route exists.

For Kazakh, check the chosen font with `Ә Ғ Қ Ң Ө Ұ Ү Һ І` and lowercase equivalents. Confirm glyph rendering in the browser. Do not hide a missing translation behind a polished screenshot.

## Make actions equivalent across input methods

A hover effect may enrich an interaction; the main action must be available through a visible control, tap, and keyboard where applicable. Use semantic elements, visible focus, meaningful labels, and honest loading and error states.

For an interactive hero, decide what happens on tap, drag, scroll, focus, and cancellation. Keep ordinary page scrolling usable. If dragging owns a gesture, limit that ownership to its actual interaction region and handle pointer cancellation. A decorative mascot should not prevent reaching the content below it.

Treat device tilt as an optional enhancement. A normal tap or button should still perform the meaningful action. Check reduced-motion behavior and keep a readable, useful still state. Animation should not change a control's hit area while a person is trying to use it.

## Verify the delivered interface

Use the browser tools permitted by the host. Start with the actual target page and the requested devices; add a narrow phone, a medium layout, and a desktop view when they expose different behavior. Typical review widths are 390, 768, and 1440 CSS pixels, adjusted to the product.

Review the localized first screen, menu, primary action, forms, and any interaction changed by the work. Include touch or pointer behavior, keyboard focus, and reduced motion when relevant. Save useful screenshots and record which interaction was actually performed. A desktop emulation alone does not establish device-sensor behavior on a physical phone.

Use [the verification template](references/verification-template.md) for the delivery record. Fix blocking interaction and content issues before decorative polish. After a fix, repeat the affected scenario; broaden testing only when the change or evidence warrants it.

Deliver the result, the reason behind the main visual decisions, the checks performed, and material limitations. Separate observed behavior from untested assumptions. A browser review is evidence for the named scenarios, not a blanket accessibility or performance certification.
