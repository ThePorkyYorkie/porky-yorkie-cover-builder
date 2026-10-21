# Porky Yorkie Cover Builder maintenance

Live site: https://theporkyyorkie.github.io/porky-yorkie-cover-builder/
Backup before title counter and logo update: backup/before-title-counter-and-official-logo (71eb7b3ff1772f60220dde6d5493e65cca3f3970).

Item Name starts at 37px, weight 500 Arial. At the user's request, it now shrinks proportionally only after exhausting full-size title space, down to a 20px minimum. The counter stays immediately beneath Item Name, showing character count and percentage of FULL-SIZE space. Auto-fit messages show the rendered font percentage. Width depends on actual letters, not a strict 36-character cap. measureItemTitle supplies the same font size for preview and PNG export. Shortening a title restores 37px automatically. Drafts that still exceed the line at the 20px minimum show a shorten-title warning and remain clipped to the title row.

logo-official-white.png is the approved sunglasses Yorkie badge adapted from the exact official logo in the measurement builder, with the cream background changed to white using image editing. Preserve its lettering and dog. The old logo.png remains only for historical recovery; the app loads the new versioned filename.

Preserve existing photo picker, crop frame, dragging/pinching, centering, scale, and square 1600x1600 PNG export. Crop and zoom preferences remain local browser settings. This update does not add synchronization or modify the separate measurement builder.

Before future functional changes inspect current main and make a backup. Test title fit/overflow/different letter widths, full-size to auto-fit transition and restored full size, logo loading and the complete saved PNG.
