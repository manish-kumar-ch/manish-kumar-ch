# Install

Copy README.md and all SVGs to the root of the public `manish-kumar-ch/manish-kumar-ch` repository. Copy `github-snake.yml` to `.github/workflows/github-snake.yml` (the ZIP already includes this location). Commit to your default branch, then run **Actions → Generate contribution snake → Run workflow**. The daily schedule is 00:17 UTC / 05:47 IST. GitHub scheduled runs may be delayed. The first successful run creates `output` and resolves the README's snake images. The workflow has not been run or deployed by this delivery.

No image hosting is needed for the banners or cards. The transparent PNG is embedded into both banners; the original face is embedded and circularly cropped in the badge. `character.png` is included as a reusable source asset but does not need uploading for SVG rendering. All local README image references include `?v=1`; increment the value after replacing an asset.

# Verified data and sources

Snapshot: 11 October 2026. Sources: https://api.github.com/users/manish-kumar-ch ; https://api.github.com/users/manish-kumar-ch/repos?per_page=100 ; each repository's `/languages` API endpoint; https://github.com/users/manish-kumar-ch/contributions . Raw responses are in `verification/`.

Public account name: `manish-kumar`; 4 public repositories, 0 followers, 0 received repository stars. Portfolio description mentions computational biology, machine learning and deep learning. The public profile has no bio, affiliation or email. Display name, PhD affiliation, research description, skills, email and tagline were supplied by the user and were not independently verified. No campus, degree date, awards or research project claims were invented.

Language bytes: Python 30623; CSS 12472; HTML 11151; JavaScript 7547; Dockerfile 330. Cards and activity calendar are local dated snapshots, not automatically refreshed. Custom BUILDER tier and milestone trophies are not GitHub rankings. The snake alone refreshes daily.

# Rendering

All delivered SVG animations use CSS or SMIL, with no JavaScript or external fonts. Name glyphs are vector outlines from local Brush Script. PNG data URIs use the SVG 1.1 `xlink:href` attribute for older browser compatibility. Typing clips are 100–110 SVG units tall. Background alpha is preserved; white clothing remains visible.

SVG hover effects work when opened directly or embedded inline; GitHub's image embedding does not expose internal hover interaction. Animation playback and restart timing depend on the browser and GitHub image caching. CSS motion respects reduced-motion preferences; SMIL remains active. The README uses a white-page light banner and a dark banner via `picture`. Other cards intentionally retain their dark glass appearance on either theme.

Connect badge images (Shields.io) and the view counter (Komarev) are external services as requested; the stat cards and activity calendar do not depend on third-party card services. Counter values reflect that service's requests, not unique verified visitors.

Snake configuration follows https://github.com/Platane/snk . Only the generated images are published to `output`. Workflow permissions must be allowed by repository/organization settings.

# Portrait processing

Built-in imagegen was used for background extraction. Prompt: “Remove only the white background to actual transparency. Preserve the same man, exact facial identity, sunglasses, hair, white hoodie, yellow shirt, jeans, chair, laptop, books, plant and table, same composition and illustration style. Preserve white clothing as opaque. Clean cutout alpha edges, no new objects, no text changes. Save transparent PNG for embedding in SVG.” AI extraction can introduce small visual differences; the lanyard face uses the original attachment.

# Light-blue design update

Banners, lanyard, local cards, badges and snake workflow now use a coordinated sky-blue/cyan palette. Dark mode uses navy glass; light mode uses ice-blue surfaces with deeper blue lettering for readability. Animations and portrait artwork are preserved. All local README references retain the requested `?v=1`.

# Unified brand color

The primary accent is now exactly `#00B4D8` across both banners, the ID badge, all local cards, the activity calendar, preview headings, README connect badges, view counter, and both snake variants. Neutral text and surfaces remain for readability. Snake contribution cells retain cyan intensity shades to distinguish contribution levels. Embedded portrait colors remain original.

Python and Java were added to the user-supplied skills in both banner toolkits and the README. Repository language statistics continue to reflect verified repository bytes.
