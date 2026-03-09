# Axiom Build Considerations

## Product Considerations
- Define one primary conversion goal for each page (demo booking).
- Align section copy with ICP pain points: slow ops, missed leads, manual workflows.
- Ensure value proposition is specific to measurable business outcomes.

## UX Considerations
- Keep navigation simple and stable with clear anchors.
- Ensure CTA stays visible on mobile and desktop.
- Maintain clear reading flow from hero -> process -> services -> contact.

## Accessibility Considerations
- Validate color contrast for text over dark/glass surfaces.
- Preserve focus styles and keyboard navigation for all interactive elements.
- Avoid motion that may trigger vestibular issues; respect reduced-motion preferences.

## Engineering Considerations
- Prefer reusable components for cards, service rows, and section headers.
- Keep styling tokens centralized (colors, spacing, radius, shadows).
- Use Tailwind utilities with minimal custom CSS for unique effects only.

## Performance Considerations
- Minimize heavy visual effects on low-end devices.
- Avoid large media payloads unless optimized and lazy-loaded.
- Keep layout stable to reduce cumulative layout shift.

## Content Considerations
- Keep headline and sub-headline outcome-focused.
- Use plain language for process steps and service descriptions.
- Avoid claims that cannot be validated operationally.
