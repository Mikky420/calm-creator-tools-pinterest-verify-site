# Calm Creator Tools Pinterest Verify Guide

Pinterest verification method: Add HTML tag
Pinterest meta tag status: PRESENT
Expected live URL after GitHub Pages deployment: https://mikky420.github.io/calm-creator-tools-pinterest-verify-site/

## Critical rule

Do not click Verify in Pinterest until this exact tag is visible in the live deployed page source inside <head>:

<meta name="p:domain_verify" content="9d72db2b5462c34f8758221d9567aeed"/>

## Verify flow

1. Create or open the GitHub repository.
2. Upload or push the full website package folder to the repository root.
3. Enable GitHub Pages from main branch, /root folder.
4. Wait for deployment to finish.
5. Open https://mikky420.github.io/calm-creator-tools-pinterest-verify-site/
6. View page source and confirm the tag appears exactly once before </head>.
7. Return to Pinterest Business settings and click Verify manually.
