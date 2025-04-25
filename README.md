# piper-voice-models
Pre-trained and ready to use voice models for Piper TTS. These are all medium quality so they're more useful for local voice assist use.

## Voices

### HAL9000-denoised
Trained using sequences from the movie 2001 with consistent background noise only. A denoise pass was performed prior to training.

### HAL9000-no-denoise
Same as above, but without the denoise pass.

### Picard
Captain Jean Luc Picard from the game "Star Trek Generations".

## Installation

These files need to be copied into `/var/lib/wyoming-piper/data`, or whatever path your installation of Piper uses on your system. A restart of Piper will be needed. If used with Homeassistant, that will also require a restart.

