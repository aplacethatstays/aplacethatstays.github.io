Put your DISTRACT-ME photos and videos here for "Distract me".

Supported formats: .jpg .jpeg .png .webp .mp4 .webm

Then open src/config.ts, find badDayMedia.distract, and add an entry like:

  { kind: 'image', src: 'photo.jpg', caption: '[Add a caption]' }
  { kind: 'video', src: 'clip.mp4', caption: '[Add a caption]' }

Only write the filename — the folder path is added for you.
