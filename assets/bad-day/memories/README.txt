Put your MEMORY photos and videos here for "Remind me of us".

Supported formats: .jpg .jpeg .png .webp .mp4 .webm

Then open src/config.ts, find badDayMedia.memories, and add an entry like:

  { kind: 'image', src: 'photo.jpg', caption: 'that evening at the park' }
  { kind: 'video', src: 'clip.mp4', caption: 'the walk we never filmed enough of' }

Only write the filename — the folder path is added for you.
