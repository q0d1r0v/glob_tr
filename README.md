# Glob_tr - CLI Translation Tool

Glob_tr is a simple command-line tool for translating text from one language to another using translate.
"af", "sq", "am", "ar", "hy", "az", "eu", "be", "bn", "bs", "bg", "ca", "ceb", "zh-CN", "zh-TW",
"co", "hr", "cs", "da", "nl", "en", "eo", "et", "fi", "fr", "fy", "gl", "ka", "de", "el", "gu",
"ht", "ha", "haw", "he", "hi", "hmn", "hu", "is", "ig", "id", "ga", "it", "ja", "jv", "kn", "kk",
"km", "rw", "ko", "ku", "ky", "lo", "la", "lv", "lt", "lb", "mk", "mg", "ms", "ml", "mt", "mi",
"mr", "mn", "my", "ne", "no", "ny", "or", "ps", "fa", "pl", "pt", "pa", "ro", "ru", "sm", "gd",
"sr", "st", "sn", "sd", "si", "sk", "sl", "so", "es", "su", "sw", "sv", "tl", "tg", "ta", "tt",
"te", "th", "tr", "tk", "uk", "ur", "ug", "uz", "vi", "cy", "xh", "yi", "yo", "zu",

## Installation

### 1. Download the binary

You can download the latest release of the `glob_tr` binary from the [Releases] section of this GitHub repository.

Choose the appropriate binary for your system and download it. For example, for Linux, you can download the `glob_tr` binary directly.

### 2. Install the binary globally

Once the binary file is downloaded, follow the steps below to make it globally accessible on your system.

#### For Linux/macOS:

1. Open a terminal.
2. Copy the binary to a system-wide executable directory, for example `/usr/local/bin`:

   ```bash
   sudo cp glob_tr /usr/local/bin/
   sudo chmod +x /usr/local/bin/glob_tr

   glob_tr translate --from="eng" --to="uz" --text="Say HI from BEKO!"
   ```
