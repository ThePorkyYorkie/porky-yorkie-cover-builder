# Porky Yorkie Cover Builder maintenance

Live site: https://theporkyyorkie.github.io/porky-yorkie-cover-builder/
Backup before title counter and logo update: backup/before-title-counter-and-official-logo (71eb7b3ff1772f60220dde6d5493e65cca3f3970).

Item Name uses a fixed 37px, weight 500 Arial font. ITEM_TITLE defines its canvas geometry and font for preview, width counter and PNG export. The counter is immediately beneath Item Name, measures actual text width in the current browser, and reports characters, percentage, remaining similar-width characters, and fit state. There is no single universal character limit. Overlong drafts are clipped to the title row with an explicit shorten-title warning; never shrink the title automatically.

logo-official-white.png is the approved sunglasses Yorkie badge adapted from the exact official logo in the measurement builder, with the cream background changed to white using image editing. Preserve its lettering and dog. The old logo.png remains only for historical recovery; the app loads the new versioned filename.

Preserve existing photo picker, crop frame, dragging/pinching, centering, scale, and square 1600x1600 PNG export. Crop and zoom preferences remain local browser settings. This update does not add synchronization or modify the separate measurement builder.

Before future functional changes inspect current main and make a backup. Test title fit/overflow/different letter widths, unchanged title size, logo loading and the complete saved PNG.
