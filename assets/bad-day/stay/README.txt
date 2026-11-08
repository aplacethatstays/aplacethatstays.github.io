Put ONE large image or looping video here for "Just stay here".

Supported formats: .jpg .jpeg .png .webp .mp4 .webm

Then open src/config.ts, find badDayMedia.stay, and add an entry like:

  { kind: 'image', src: 'calm.jpg' }
  { kind: 'video', src: 'rain.mp4' }

If you add a video it loops silently as the background. The first item
is the one used as the big background. Only write the filename — the
folder path is added for you.
