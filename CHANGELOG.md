# Changelog

## 1.7 — 2026-03-01
- Auto-hibernation — idle services hibernate after 5 minutes of inactivity, freeing RAM. They wake instantly on the next connection.
- Qdrant — vector database for AI/ML workloads (versions 1.15, 1.16, 1.17).
- MySQL — updated to 8.4 LTS and 9.
- Fixed MongoDB reliability issues. MongoDB now supports hibernation.
- Localization fixes.

## 1.6 — 2026-02-03
- New database versions: PostgreSQL 18, Redis 8, and MySQL 9 are now the defaults for new services.
- MongoDB — document-oriented NoSQL database (versions 7.0, 8.0).
- MinIO — S3-compatible object storage for local development.
- Fixed clock skew issue that could cause incorrect service uptime display.
- Improved service running time display.

## 1.5 — 2026-01-04
- Zoebox now speaks your language! Full localization in 8 languages: English, German, Spanish, French, Japanese, Ukrainian, Russian, and Chinese (Simplified)
- Minor bug fixes and stability improvements

## 1.4 — 2025-12-30
- Fixed crash when rapidly connecting/disconnecting to services

## 1.3 — 2025-12-29
- Fixed menu bar interaction issues
- Minor UI polish

## 1.2 — 2025-12-29
- Improved DMG installer appearance

## 1.1 — 2025-12-29
- Instant service startup via VM hibernation (~0.5s restart)
- Fixed "Run at Login" setting
- Improved OCI layer download reliability
- Various stability improvements

## 1.0 — 2025-12-29
- Initial release
- PostgreSQL 14, 15, 16, 17
- MySQL 5.7, 8, 9
- Redis 6, 7
- Redpanda 24, 25 (Kafka-compatible)
- Menubar app with one-click service management
- Automatic updates via Sparkle
