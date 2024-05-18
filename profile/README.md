# Hard Brain

![image](https://github.com/hard-brain/.github/assets/101812777/855b0890-518d-47b3-89ea-00ac8cbb0cb5)

## Introduction  

Hard Brain is an application which provides a Discord bot for running music quizzes for Beatmania IIDX songs. It currently contains all songs from every IIDX AC release (1st style - Resident) and CS release (1st style - EMPRESS + PREMIUM BEST, and Infinitas (2023)). Slash commands can be used to start a quiz, provided that the user is connected to a voice channel.  

When a game is running, the bot will join the voice channel and play a song from IIDX. Users can then type the name of the song to try and win points.

![image](https://github.com/hard-brain/.github/assets/101812777/8dfccf55-990a-4981-ba20-94ad7828b5cd)

## Commands  

All commands in Hard Brain are slash commands, except for answering songs (for which you just type the name).

- `start_quiz`: Starts a music quiz in the current channel, given that the user is connected to a voice channel. Also optionally supports values for number of rounds (1-100) and a time limit (5-60 seconds).
- `current_scores`: Shows the scores for players in the current game
- `end_quiz`: Ends the game currently in progress
- `skip_round`: Skips the current round
- `suggest`: Suggest an alternative title for a song. Suggestions are sent directly to the Hard Brain development server, but have to be manually added.

## Adding Hard Brain to your server  

As of May 2024, Hard Brain is still in early development, so if you are interested in adding it to your server, please reach out to @corndogit on Github and the invite link can be provided.

## Contribution guidelines  

You can use the [Discussions page](https://github.com/orgs/hard-brain/discussions) for reporting bugs or giving feedback.  

Source code is not ready for public release, but may happen in the future.
