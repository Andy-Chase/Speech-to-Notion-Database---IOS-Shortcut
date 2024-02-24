# Voice Note to Notion Shortcut

## Overview

This iOS Shortcut  real game-changer for recording voice notes, transcribing them into text using OpenAI's Whisper API, and then neatly tucking them away in your Notion database. It's all about boosting your productivity and making note-taking as hassle-free as can be, letting you categorise your notes for better organisation right from the get-go.

This iOS Shortcut provides a seamless method for recording voice notes, transcribing them into text using OpenAI's Whisper API, and storing the transcribed notes in a Notion database. It's designed to enhance productivity and note-taking efficiency, allowing users to categorise their notes for better organisation directly through the Shortcut.

## Features

- **Voice Note Recording:** Quick start to recording voice notes through this Shortcut.
- **Automatic Transcription:** Leverages OpenAI's Whisper API for spot-on transcriptions.
- **Notion Database Integration:** Effortlessly sends your transcribed notes to the specified Notion database.
- **Note Categorisation:** Lets you categorise your notes by fetching database details straight through the Shortcut.

## Requirements

- An iOS device with the Shortcuts app installed.
- An OpenAI API key for Whisper API access.
- A Notion account with an API key.
- A Notion database set up and ready to collect and categorise your notes.

## Setup Instructions

### Step 1: Duplicating the Notion Database Template

1. Head over to the provided Notion database template link: [Voice Note Database Template](https://andymorgan.notion.site/7e5e64e45e04431bbe4c29cab92fc9a9?v=bad92a5de8da45e0a5caec04861dffc1&pvs=4).
2. In the top-right corner of the page, hit the "Duplicate" button to add the template to your Notion workspace.
3. Feel free to tweak the duplicated database as needed to fit your note-taking style.

### Step 2: Configuring OpenAI API Access

1. Bag yourself an OpenAI API key by signing up at [OpenAI](https://openai.com/).
2. Keep your API key safe and sound, 'cause you'll need to pop it into the Shortcut.

### Step 3: Setting Up Notion Integration

1. Whip up an integration API key (aka the Internal Integration Token) from Notion by following the [Notion API documentation](https://developers.notion.com/).
2. Jot down your database ID - you'll find it in the database URL after you've got your template all set up.

### Step 4: Download and Configure the Shortcut

1. Download the Voice Note to Notion Shortcut onto your iOS device [Shortcut](https://www.icloud.com/shortcuts/542bb96ceb3448929717cd2fd9f34c71).
2. Open the Shortcut and when prompted, enter your OpenAI API key, Notion API key, and database ID.
3. Tailor the categories for your notes according to your Notion database schema.

### Step 5: Using the Shortcut

1. Trigger the Shortcut to kick off a voice note recording.
2. Once you've finished recording, you'll get to choose a category for your note if needed.
3. The Shortcut then does its magic, transcribing the note and whisking it off to your Notion database.

## Troubleshooting

- Make sure all API keys and the database ID are correctly entered.
- Check that your Notion database is all set to welcome entries from your integration.
- If the transcription or database entry seems to be playing up, checking your internet connection might do the trick.

## Support

If you have any issues, the OpenAI documentation's your go-to for transcription troubles, and the Notion API documentation's for any database integration headaches.
