# Awesome Immich [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome Immich plugins, tools, and community projects

[Immich](https://immich.app/) is a self-hosted photo and video management solution with a web interface and mobile apps.

## Contents

- [CLI Tools](#cli-tools)
- [Import/Export Tools](#importexport-tools)
- [Media Management](#media-management)
- [Slideshow & Display](#slideshow--display)
- [Optimization](#optimization)
- [Sharing](#sharing)
- [Distribution](#distribution)
- [Home Automation](#home-automation)
- [Guides](#guides)
  
## CLI Tools

- [immich-go](https://github.com/simulot/immich-go) - Alternative CLI tool that doesn't depend on Node.js, specializes in importing Google Photos Takeout archives.
- [Powershell Module PSImmich](https://github.com/hanpq/PSImmich) - PowerShell module for the Immich API.

## Import/Export Tools

- [Lightroom Publisher: mi.Immich.Publisher](https://github.com/midzelis/mi.Immich.Publisher) - Lightroom plugin to publish photos from Lightroom collections to Immich albums.
- [Lightroom Immich Plugin: lrc-immich-plugin](https://github.com/bmachek/lrc-immich-plugin) - Lightroom plugin to publish and export photos from Lightroom to Immich. Import from Immich to Lightroom is also supported.
- [Obsidian Immich Picker](https://github.com/eikowagenknecht/obsidian-immich-picker) - Obsidian plugin to browse and insert photos from your Immich library into notes.
- [Immich Shuttle](https://github.com/enieuwy/immich-shuttle) - Cross-platform desktop app to import photos and videos into Immich from folders or removable media (SD cards, USB drives) with a point-and-click UI, album selection, and live import progress.
- [Immich Face Export](https://github.com/laszabine/immich-face-export) - A Python tool to export face recognition data from Immich photo management system to DigiKam-compatible XMP format files.

## Media Management

- [Immich Power Tools](https://github.com/varun-raj/immich-power-tools) - Power tools for organizing your Immich library.
- [Immich Atlas](https://github.com/GuiMartins/immich-atlas) - Read-only storage & library analytics dashboard: disk usage by folder, album/people sizes, largest videos, growth over time, all auto-refreshing.
- [Immich Face To Album](https://github.com/romainrbr/immich-face-to-album) - Sync all photos belonging to one or more detected faces into an existing Immich album
- [Immich MediaKit](https://github.com/RazgrizHsu/immich-mediakit) - Extension toolkit enabling advanced management capabilities through AI-powered similarity detection and duplicate management.
- [Immich Auto Stack](https://github.com/tenekev/immich-auto-stack) - Python script that automatically stacks together photos based on configurable criteria like filename and capture time.
- [immich-photo-manager](https://github.com/drolosoft/immich-photo-manager) - MCP server and Claude Code plugin that manages your Immich library through conversation: natural language and OCR search, geographic albums from GPS data, duplicates with perceptual hashing, people and faces, metadata repair, video frames and PDF photobooks. 94 tools and 13 skills, tested live on Immich 2.x and 3.x, also available with uvx or as a Docker image.
- [Immich Trip Albummer](https://github.com/sophie4869/immich-trip-albums) - Python CLI that clusters photos and videos taken away from home into one album per trip. Deterministic, dry-run by default, and idempotent on re-runs.
- [camie-immich-tagger](https://github.com/PlanetMeow/camie-immich-tagger) - Local anime/illustration auto-tagging (camie-tagger-v2) that writes hierarchical XMP sidecar tags for browsing and search in Immich, with optional SauceNAO reverse-search backfill.
- [Immich Geotag](https://github.com/pennico/immich-geotag) - Fill in missing GPS coordinates by recognizing landmarks (Google Cloud Vision, with optional Lens, Gemini, and visual-similarity passes). Add-only and idempotent: photos that already have a location are never touched.
- [Immich Relocator](https://github.com/bihius/immich-relocator) - Relocate pics & videos from Immich internal folder to one or more External Libraries, while updating the Immich db accordingly, so that you never lose track of albums, stacks, faces, tags, etc.
- [motion-photo-bridge](https://github.com/duruonanni/motion-photo-bridge) - Merges dual-file live photos (the same-stem `JPG` + `MP4` pairs that vivo and iQOO phones produce) into standard Motion Photo JPEGs, links them in Immich, and can convert pairs that are already in the library in place.

## Slideshow & Display

- [ImmichFrame](https://github.com/3rob3/ImmichFrame) - Run an Immich slideshow in a photo frame.
- [Immich Kiosk](https://github.com/damongolding/immich-kiosk) - Lightweight slideshow to run on kiosk devices and browsers.
- [Slyde](https://github.com/SlyWombat/slyde) - Pushes Immich photos to digital photo frames — incl. reviving the discontinued Memento Smart Frame over a reverse-engineered LAN protocol, no cloud.
- [Immich Android TV](https://github.com/giejay/Immich-Android-TV) - Unofficial Immich Android TV app.
- [Immich Gallery](https://github.com/mensadilabs/Immich-Gallery) - Native Apple TV app with grid view, people recognition, albums, slideshow mode, and multi-user support.
- [Immuch360](https://github.com/freeKC/Immuch360) - Fork of the Immich mobile app with 360° photos and videos, 3D and VR180, a Meta Quest 3 immersive view, a mode without a server and SMB/WebDAV shares.
- [Immich Wear](https://github.com/nikosavola/immich-wear) - Unofficial Immich client for Wear OS to browse recent photos, albums, favorites and memories from your wrist.
- [Immich Memories](https://github.com/sam-dumont/immich-memories) - Generate memory films from Immich photos, videos and Live Photos, with titles, music, a web editor and automatic scheduling.

## Optimization

- [Immich Upload Optimizer](https://github.com/miguelangel-nubla/immich-upload-optimizer) - Automatically optimize files uploaded to Immich in order to save storage space.
- [Immich Machine Learning Load Balancer](https://github.com/apetersson/immich_ml_balancer) - Speed up your machine learning by load balancing your requests to multiple computers

## Sharing

- [Immich Public Proxy](https://github.com/alangrainger/immich-public-proxy) - Share your Immich photos and albums in a safe way without exposing your Immich instance to the public.
- [Immich Drop Uploader](https://github.com/Nasogaa/immich-drop) - A tiny, zero-login web app for collecting photos/videos from anyone into your Immich server.
- [Immich Book](https://github.com/ch1bo/immich-book) - Create beautiful photo books from your Immich albums.
- [Darkroom Log](https://github.com/jaapjan14/darkroom-log) - Browse, sort, and share your Immich albums and library as branded public galleries, with sort-by-date inside albums (missing from Immich's native UI) and a Ken Burns slideshow with music.
  
## Distribution

- [Immich Distribution](https://github.com/nsg/immich-distribution) - Snap package for easy install and zero-care auto updates of Immich.
- [Immich in LXC](https://github.com/loeeeee/immich-in-lxc) - Install Immich in LXC with optional CUDA support for hardware acceleration.

## Home Automation

- [Immich Home Assistant](https://github.com/outadoc/immich-home-assistant) - Home Assistant component to display random pictures from your Immich library on dashboards and smart displays.


## Guides

- [How to Self-Host Immich with Docker Compose](https://selfhosting.sh/apps/immich/) - Complete setup guide covering installation, configuration, and external library management.
- [Immich vs PhotoPrism](https://selfhosting.sh/compare/immich-vs-photoprism/) - Detailed comparison of features, performance, and use cases.
- [Immich vs Google Photos](https://selfhosting.sh/compare/immich-vs-google-photos/) - Side-by-side comparison for users considering migrating from Google Photos.

## Contributing

Contributions are welcome!
