# Netlib32

VB6 NetAPI32 helper module set (no `.vbp`) for Windows NT domain administration. `netdecs.bas` holds structures and pointer conversion; `netuser.bas` wraps get/set/add/delete user and password reset; `netgroup.bas` manages global groups and memberships; `netsrv.bas` resolves a PDC via `NetGetDCName`; `neterr.bas` maps common NetAPI error codes into readable messages.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** module / sources

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `netdecs.bas` | VB6 | source | NetAPI structures, declares, pointer helpers |
| `netuser.bas` | VB6 | source | Get/set/add/delete user, reset password |
| `netgroup.bas` | VB6 | source | Add/delete groups and memberships, list helpers |
| `netsrv.bas` | VB6 | source | NetGetPDC via NetGetDCName |
| `neterr.bas` | VB6 | source | NetAPI error-message mapper |

## How to open

Open `netdecs.bas` in Visual Basic 6 as a module, or add the `.bas` files to a VB6 project.

## Requirements

- Visual Basic 6.0 IDE
- Windows NT/2000-era NetAPI32 access (typically against a PDC)

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VB/Old/Netlib32`.

## License

MIT (c) 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
