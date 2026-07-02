# PanaSlice — Sample Files

Sample Final Cut Pro FCPXML file for testing **PanaSlice**, a macOS
utility that cuts Final Cut Pro clips at regular time intervals.

## Contents

- `PanaSlice_Sample.fcpxml.zip` — a single plain-text FCPXML file
  (compressed only to ensure a clean download). After unzipping you
  get **one single file**, `PanaSlice_Sample.fcpxml` — it is NOT a
  bundle or folder. The project contains three consecutive clips on
  the primary storyline.

## How to test with PanaSlice

1. Download `PanaSlice_Sample.fcpxml.zip`.
2. Unzip it. You will get one single file: `PanaSlice_Sample.fcpxml`.
3. Open PanaSlice.
4. Drag `PanaSlice_Sample.fcpxml` onto the app window, or use the
   "Apri…" / "Open…" button. (PanaSlice also accepts `.fcpxmld`
   bundles exported from Final Cut Pro.)
5. Set a cut interval in mm:ss format, e.g. `00:05`.
6. The preview shows how many segments will be generated.
7. Click "Elabora" / "Process" and choose where to save the result.
8. PanaSlice generates a new `.fcpxml` with the cuts applied, ready
   to import back into Final Cut Pro.

## Note

The sample references video files that are **not included** — they
are not needed. PanaSlice works purely on the FCPXML project
structure and does not require the actual media to function.

These files are provided for Apple App Review and will remain
available for future reviews.
