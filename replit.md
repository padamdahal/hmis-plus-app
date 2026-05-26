# Project Overview

A minimal Bash utility that packages the contents of the `src/` directory into a zip archive at `./build/app.zip`.

## Usage

Run the build script to zip the `src/` folder:

```bash
bash build.sh
```

This will:
1. Create a `./build/` directory if it doesn't exist
2. Zip the contents of `./src/` into `./build/app.zip`

## Project Structure

```
.
├── build.sh     # Build script
├── src/         # Source files to be zipped
└── build/       # Output directory (created on first run)
```

## User Preferences

(None set yet)
