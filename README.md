# piper-voice-models
Pre-trained and ready to use voice models for Piper TTS. These are all medium quality so they're more useful for local voice assist use.

## Voices

### HAL9000-denoised
Trained using sequences from the movie 2001 with consistent background noise only. A denoise pass was performed prior to training.


https://github.com/user-attachments/assets/3bc713d2-04da-453e-8ad2-6280d7a66d91


### HAL9000-no-denoise
Same as above, but without the denoise pass.


https://github.com/user-attachments/assets/32a30006-dfe5-4627-a94c-ada532a8f2e7


### Picard
Captain Jean Luc Picard from the game "Star Trek Generations".


https://github.com/user-attachments/assets/33e555ad-27ee-439b-aae7-924617948a6b


### Data
Commander Data from the game "Star Trek Generations".


https://github.com/user-attachments/assets/6541980f-5a5a-44be-a8b9-0b1312bc3df0


## Installation

These files need to be copied into `/var/lib/wyoming-piper/data`, or whatever path your installation of Piper uses on your system. A restart of Piper will be needed. If used with Homeassistant, that will also require a restart.

