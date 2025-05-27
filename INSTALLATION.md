# راهنمای نصب فرهنگ انگلیسی-فارسی / Installation Guide for Persian-English Dictionary

این راهنما دستورالعمل‌های مفصل گام به گام برای نصب فرهنگ انگلیسی-فارسی روی دستگاه کوبو شما ارائه می‌دهد.

This guide provides detailed step-by-step instructions for installing the Persian-English dictionary on your Kobo eReader.

## Prerequisites

- A Kobo eReader device
- USB cable for connecting to computer
- Computer with file manager access

## Step-by-Step Installation

### Step 1: Download the Dictionary

1. Go to the [Releases](../../releases) page of this repository
2. Download the latest `dicthtml-eng-fas.zip` file
3. Save it to a location you can easily find (e.g., Desktop or Downloads folder)

### Step 2: Connect Your Kobo

1. Turn on your Kobo eReader
2. Connect it to your computer using the USB cable
3. Your Kobo should appear as a removable drive on your computer
4. Wait for the connection to be fully established

### Step 3: Navigate to Dictionary Folder

1. Open your file manager (Windows Explorer, macOS Finder, etc.)
2. Navigate to your Kobo device
3. Look for the `.kobo` folder (it may be hidden)
   - **Windows**: Enable "Show hidden files" in View options
   - **macOS**: Press `Cmd + Shift + .` to show hidden files
   - **Linux**: Press `Ctrl + H` to show hidden files
4. Open the `.kobo` folder
5. Open the `dict` folder inside `.kobo`

### Step 4: Copy the Dictionary

1. Copy the downloaded `dicthtml-eng-fas.zip` file
2. Paste it into the `.kobo/dict/` folder on your Kobo

### Step 5: Choose Installation Method

You have two options:

#### Option A: Use as Additional Dictionary (Recommended)

- Keep the filename as `dicthtml-eng-fas.zip`
- This may work on newer Kobo firmware versions

#### Option B: Replace Existing Dictionary

- Rename `dicthtml-eng-fas.zip` to one of these official names:
  - `dicthtml-pt-en.zip` (replaces Portuguese → English)
  - `dicthtml-es-en.zip` (replaces Spanish → English)
  - `dicthtml-fr-en.zip` (replaces French → English)
  - `dicthtml-it-en.zip` (replaces Italian → English)
  - `dicthtml-de-en.zip` (replaces German → English)

**Note**: Choose a dictionary you don't use. You'll lose access to the original dictionary.

### Step 6: Enable Dictionary (for Option B)

If you renamed the file in Step 5:

1. On your Kobo, go to **Settings**
2. Navigate to **Reading Settings**
3. Find **Dictionary** settings
4. Enable the dictionary language you replaced (e.g., Portuguese if you used `dicthtml-pt-en.zip`)

### Step 7: Safely Disconnect

1. Safely eject your Kobo from your computer
2. Disconnect the USB cable
3. Restart your Kobo device (hold power button for 10 seconds, then turn on)

### Step 8: Test the Dictionary

1. Open any English book on your Kobo
2. Tap and hold on an English word
3. You should see the Persian translation appear in a popup
4. If it doesn't work, try the troubleshooting steps below

## Troubleshooting

### Dictionary Not Appearing

1. **Check file location**: Ensure the file is in `.kobo/dict/` folder
2. **Check filename**: Make sure it matches exactly (case-sensitive)
3. **Restart device**: Hold power button for 10 seconds, then restart
4. **Check book language**: Ensure your book is marked as English language

### Wrong Dictionary Showing

1. Go to Kobo **Settings** → **Reading Settings** → **Dictionary**
2. Change the dictionary priority or selection
3. Make sure the correct language is enabled

### Dictionary Popup Not Working

1. Try tapping and holding the word longer
2. Make sure you're selecting single words, not phrases
3. Check that the book format supports dictionary lookup (EPUB works best)

### File Transfer Issues

1. Try a different USB cable
2. Restart both your computer and Kobo
3. Check that your Kobo has enough storage space
4. Ensure the ZIP file isn't corrupted (try downloading again)

## Advanced Tips

### Multiple Dictionaries

- You can install multiple custom dictionaries by replacing different language slots
- Keep track of which dictionaries you've replaced
- Consider keeping backups of original dictionaries

### Firmware Updates

- Kobo firmware updates may overwrite custom dictionaries
- Always keep a backup of your custom dictionary files
- Reinstall after firmware updates if necessary

### Book Language Settings

- Make sure your English books have proper language metadata
- Use Calibre or similar tools to set book language if needed
- Books without proper language tags may not trigger the dictionary

## Backup and Restore

### Creating Backups

Before installing custom dictionaries:

1. Navigate to `.kobo/dict/` on your device
2. Copy all existing `.zip` files to your computer
3. Store them in a safe location labeled with your Kobo firmware version

### Restoring Original Dictionaries

To restore original dictionaries:

1. Delete the custom dictionary file from `.kobo/dict/`
2. Copy the original dictionary file back
3. Restart your Kobo

## Support

If you encounter issues:

1. Check this troubleshooting guide first
2. Search existing [Issues](../../issues) on GitHub
3. Create a new issue with:
   - Your Kobo model
   - Firmware version
   - Detailed description of the problem
   - Steps you've already tried
