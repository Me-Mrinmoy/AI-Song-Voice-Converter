# 🎵 AI Song Voice Converter

Transform any song into a new experience by converting it into another singer's voice using cutting-edge AI voice conversion.

---

## 🚀 Project Description

This AI-powered app allows users to say or type a song name and specify another singer they'd like to hear it in. For example:

> 🎙️ "Play 'Muskurane Ki Wajah Tum Ho' in Vishal Mishra's voice"

The app will:
1. Fetch the original song
2. Separate vocals and instrumental tracks
3. Convert the original singer's vocals to the target singer's voice using an AI voice model
4. Merge the new vocals with the original instrumental
5. Play or return the final output

---

## 🧠 Technologies Used

| Task                         | Tech / Library              |
|------------------------------|-----------------------------|
| Voice Input & Parsing        | Whisper (or Google STT)     |
| Song Download                | yt-dlp                      |
| Vocal Separation             | Spleeter                    |
| Voice Conversion             | So-VITS-SVC / Diff-SVC      |
| Backend                      | FastAPI / Flask             |
| Audio Processing             | ffmpeg-python               |
| Optional Frontend            | Flutter / React             |

---

