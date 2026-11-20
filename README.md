# GTA 6 Clipper Entry

Source: SpeedUniverse (iShowSpeed's own clips channel), “iShowSpeed's First Time PLaying GTA 6!”, https://www.youtube.com/watch?v=kR8bhkVAgBY. Chosen timestamp: 00:00:30–00:00:50, the bright opening GTA 6 reveal sequence with rapid scene changes and the streamer reaction.

Hook: `GTA 6 PERTAMA KALI BIKIN MERINDING`

Pitch: `MAKE CLIPS LIKE THIS WITH AI` / `AND EARN MONEY ON make.fun` / `make.fun/bounty/gta6-clipper-01`

Proposed YouTube title: `GTA 6 PERTAMA KALI BIKIN MERINDING! #GTA6 #Shorts`

The source was downloaded with yt-dlp. I extracted mono 16 kHz audio, computed RMS loudness for every 2-second window with Python and numpy, then checked the loudest candidates with ffmpeg scene detection and signalstats brightness before selecting the opening reveal. The clip is rendered with ffmpeg as a centered 9:16 crop with the original reaction audio, followed by a silent make.fun end card.

VIDEO.json still holds the starter placeholder and gets the real URL in a follow-up turn after the person uploads the clip.

Final clip specs: 25.000 seconds, 720x1280, 3,630,737 bytes, H.264 video and 44.1 kHz stereo AAC audio.
