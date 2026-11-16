# Change log

## Public V10.8 — 2026-11-16

- Started from **user-confirmed working ESPHome V10.8 YAML**, unchanged in IR, PMIC and climate logic.
- Replaced the embedded ESPHome API encryption key with `!secret api_encryption_key`.
- Replaced the embedded fallback Wi-Fi AP password with `!secret fallback_ap_password`.
- Existing `!secret wifi_ssid` / `!secret wifi_password` references retained.
- Added `secrets.yaml.example` with only placeholders.
- Added `.gitignore` to exclude secrets, private archives and build artifacts.
- Added English README explaining device setup, display/timer functions and limitations.
- **Not included:** past ZIP backups, raw captures, historical personal project data, screenshots with addresses, live credentials.
- No separate compilation or field test of this credential-sanitized copy has been performed; live V10.8 functionality is user-confirmed.
