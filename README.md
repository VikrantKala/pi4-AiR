# Pi Voice Reminders

Send a Telegram voice note → transcribed locally (whisper.cpp) → reminder extracted locally (Ollama) → fired back on time. Runs fully offline on a Raspberry Pi 4 (4 GB).

## Hardware & OS
| Item | Value |
|---|---|
| Board | Raspberry Pi 4 Model B, 4 GB |
| OS | Raspberry Pi OS Lite 64-bit (Debian 13 trixie), kernel 6.18 |
| Python | 3.13 |
| Storage | 16 GB microSD (9.6 GB free after install) |
| Idle RAM | 185 MB used |

## Progress
- [x] 0. OS installed (64-bit)
- [ ] 1. Transcription (whisper.cpp base.en)
- [ ] 2. Intent extraction (Ollama)
- [ ] 3. Telegram bot skeleton
- [ ] 4. Full pipeline + SQLite
- [ ] 4b. Reminders mirrored as Markdown notes, synced to PC with Syncthing
- [ ] 5. Scheduler survives reboot
- [ ] 6. Audio upload to Drive
- [ ] 7. Edge cases handled
- [ ] 8. Runs as a systemd service
