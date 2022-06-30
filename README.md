MP4 → text

# Method #1 - Best way

Target: from Video File(MP4) → Audio File(MP3) → text file/subtitles(txt)

- Divide and Conquer
  - Todos
    - #1 Code up the MP3 to text
      - This way we can easily convert the MP3 file to text. This will make the process of converting a MP4 to text much more easier
    - #2 Code up the MP4 to MP3 converter - FFMPEG
      - FFMPEG is a awesome dependency to convert our MP4 to MP3 format. To make the file explorer more cleaner, we can have a dedicated folder to store the converted MP3 files and another to trash the MP4 files.
    - Combine - #1 + #2
      - We can first run through the MP4 to MP3 (#2) function. It should be stored in the dedicated folder for converted MP3 then we can use the MP3 to text (#1) to convert to text.
