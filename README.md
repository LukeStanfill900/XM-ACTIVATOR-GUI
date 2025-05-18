# SiriusXM Activator GUI (EXE)

A lightweight Windows application that reproduces the activation / refresh
sequence from the official **SiriusXM Dealer** app, letting you trigger a
3-month trial on a compatible radio with a single click.

---

## ▶️ Quick Start

1. Download **`SiriusXMActivator.exe`** from the latest release.
2. Double-click the EXE.  
3. Enter your Radio ID (find it under *Menu → Options → Sirius ID* on most
   head-units).  
4. Click **Run Sequence** and watch the on-screen log.  
5. When **CreateAccount** and **update_2** show `SUCCESS`, the radio should
   activate within a few minutes.

---

## ✨ Features

| | |
|---|---|
| **One-file EXE** | Built with PyInstaller – no Python install needed |
| **Modern GUI**   | Tkinter interface with log viewer and status tags |
| **Background threading** | UI stays responsive during network calls |
| **No installer required** | Just copy/run the EXE |

---

## How It Works (Technical)

The app sends the same HTTPS requests the SiriusXM Dealer iOS app (v 3.1.0)
performs:

