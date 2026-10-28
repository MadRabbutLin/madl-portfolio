# FRAME / React portfolio

## North Star
A restrained cinematic visual archive for a photographer/editor. Brand register, Simplified Chinese audience. A full-width mountain frame and outlined Chinese headline form the signature; cool graphite, pale metallic text and quiet metadata supply technical character without neon or dashboard furniture.

## Palette and ownership
`src/style.css :root` owns runtime tokens: background #0c0e10, panel #171a1d, text #ededeb, muted #999fa4, border #2b3034, accent #bdcbd4, scrollbar thumb #535e66 and track #121518. System Segoe UI / Microsoft YaHei body and restrained Consolas utility labels avoid external font dependencies.

## Layout
1700px maximum content width, 50px desktop gutters; 28px intermediate and 18px mobile gutters. Hero showreel, four-category project archive, personal introduction and contact. Compact three-column project grid becomes two columns at 1000px and one column at 600px; covers retain a 1.8 aspect ratio. No invented clients, credentials, or outcomes.

## Interaction
React category buttons expose aria-pressed. Native dialog handles modal isolation, Escape and focus restoration. Video uses native controls, inline playback, error fallback and local file preview. Local video object URLs are released on replacement/unmount, never uploaded or persisted. Samples are explicitly marked; contact is a placeholder pending owner details. Visible keyboard focus, reserved image ratios, reduced-motion support and global scrollbars are mandatory.

## Assets
Unsplash demonstration covers require internet; local MDN CC0 flower sample video verifies playback and is not the owner's work. Source: https://interactive-examples.mdn.mozilla.net/media/cc0-videos/flower.mp4 . Replace assets with supplied portfolio before publication.
