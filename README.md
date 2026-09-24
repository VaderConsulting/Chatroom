# Chatroom

CTR Business Systems VB6 chat sample with a client ActiveX Document EXE (`chat_client.exe`) and The Collective server (`The_Collective_SV.vbp`); Winsock helpers may be redacted to `*.example`. Open either `.vbp` under `Client/` or `Server/` in the VB6 IDE.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `chat_client` (`Client/chat_client.vbp`) | VB6 | WinForms exe | Chat client ActiveX Document EXE |
| `The_Collective_SV` (`Server/The_Collective_SV.vbp`) | VB6 | WinForms exe | Chat server (users/rooms collections) |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Client/chat_client.vbp`
- `Server/The_Collective_SV.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Registered OCX/DLL dependencies referenced by the `.vbp` (may need to be installed separately):
  - `MSWINSCK.OCX`
  - `Msinet.OCX`
  - `shdocvw.dll`

## Attribution and provenance

Working copy from my Historical Dev folder `VB/Old/Chatroom`.
Company names in project files: CTR Business Systems. Inc.
Third-party attribution: CTR Business Systems. Inc. See `THIRD_PARTY_NOTICES.md`.

## License

Third-party code remains under its original terms (or none, where none were supplied). See `THIRD_PARTY_NOTICES.md`. Do not treat this tree as VaderConsulting original MIT-licensed work.
