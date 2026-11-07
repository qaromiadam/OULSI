https://private-user-images.githubusercontent.com/224674987/698147904-93e74653-1f6c-4ade-923e-b835a16b9982.jpg?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3OTQwNTMxOTUsIm5iZiI6MTc5NDA1Mjg5NSwicGF0aCI6Ii8yMjQ2NzQ5ODcvNjk4MTQ3OTA0LTkzZTc0NjUzLTFmNmMtNGFkZS05MjNlLWI4MzVhMTZiOTk4Mi5qcGc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYxMTA3JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MTEwN1QxMjAxMzVaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1kOTY4NWU5NDZjMmQzN2EwMDBkZDM3ZDY4MGI4NTQ5YTY1NzM2YzJlMTFjZTMxMWQwMWYxYzk5ZTcxMWMyOWIxJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZyZXNwb25zZS1jb250ZW50LXR5cGU9aW1hZ2UlMkZqcGVnIn0.2z4FkSV8mMQozoXiYAYVfkBluLA3OW9ahE9g7njBhl4


# 🐍 Oulsi v5.6: A Programming Language That Reads Like Plain English

Oulsi makes coding as natural as writing a simple sentence.

It is written in Python and uses clear commands such as `set`, `say`, `add`, `if`, `repeat`, and `move`.

Commands and variable names are not case-sensitive, so `SAY`, `Say`, and `say` all work. ✨

## 💡 Quick example

```
set price to 20
set count to 3
calculate total = price * count
say "Total to pay:" total

if total is greater than 50:
    say "You get a discount!" 🎉
else
    say "No discount this time"
end
```

## 🚀 Features

**🧠 Language core:** variables, math, text joining, `if`/`else`, `elif` and `else if`, `and`/`or`, grouping conditions with brackets, `repeat`, `for each` loops, lists (including lists inside lists), custom functions, true and false values, `ask` for typing answers, and `pause`/`wait` in seconds ⏱️.

**🎨 Graphics engine:** windows, boxes, circles, text, moving objects, turning boxes and buttons 🔄, and changing colors 🌈.

**🕹️ Interactiveness engine:** keyboard keys ⌨️, clickable buttons 🖱️, mouse position, and mouse clicks.

**🎮 Game engine:** collision detection, for example `if ball touches paddle` 🏓.

**🎬 Media engine:** pictures (`show`, `make picture`, `resize`) 🖼️, videos (`play`, `pause video`) 📹, and sounds (`play`, `stop sound`) 🔊.

Typed file names such as `play «clip.mp4»` work too.

**📂 Running other files:** `start «other.oul»` runs another Oulsi file.

**🔍 Clear error messages:** each error shows the file, line number, command, problem, and a suggested fix when brackets are missing 🛠️.

**📚 Documentation:** complete guides, HOW TO USE OULSI and HOW TO BUILD OULSI, in English 🇬🇧 and French 🇫🇷.

## 📦 What's in the zip

🐍 `oulsi.py` and the `oulsi_*.py` modules

🗂️ `examples/`: hello, features, v5_features, counting_demo, ask_demo, game, media_demo, typed_media, video_example, video_formats, jpg_demo, main, other

🎞️ `examples/media/`: sample sound, picture, photo, and five versions of a short video with sound (MP4, AVI, MOV, MKV, WebM)

📖 The HOW TO USE and HOW TO BUILD guides in English and French

## ⚙️ Requirements

**Required:** Python 3.8 or newer 🐍

**Windows and games:** tkinter (included with Python on Windows and macOS; on Linux, `sudo apt install python3-tk`) 🪟

**Optional extras:** Pillow, OpenCV, and FFmpeg. Oulsi runs without them, but some features need them: JPG pictures and resizing (Pillow), videos (OpenCV), and video sound and mp3 files (FFmpeg).

📘 For step-by-step install instructions for Windows, macOS, and Linux, open **BUILD_OULSI_GUIDE_ENGLISH.txt** (or **BUILD_OULSI_GUIDE_FRANÇAIS.txt** for French) and read **STEP 1B: OPTIONAL EXTRAS**.

## ▶️ Getting started

1. 📥 Unzip the archive and open a terminal in the `oulsi` folder.

2. 🏁 Run an example:

   Linux / macOS: `python3 oulsi.py examples/hello.oul`

   Windows: `py oulsi.py examples/hello.oul`

3. 📘 Read HOW TO BUILD OULSI for setup, or HOW TO USE OULSI for the language reference.
