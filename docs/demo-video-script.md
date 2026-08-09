# zFlow Demo Video Script

Target length: 90-120 seconds.

Goal: show that zFlow is a real-shell terminal assistant that learns locally, suggests the next command, and keeps the user in control.

## Structure

### 1. Opening

Visual: terminal window with zFlow starting.

Voiceover:

> zFlow is a local-first terminal assistant. It runs your real bash or zsh session inside a TUI and suggests commands based on your own shell history.

On-screen actions:

```bash
zflow
```

### 2. Real Shell Behavior

Visual: run normal shell commands, change directories, and show that the terminal behaves like a normal shell.

Voiceover:

> It is not a replacement shell. Directory changes, interactive programs, and your usual shell behavior still work as expected.

On-screen actions:

```bash
pwd
ls
cd ~/code
git status
```

### 3. Learning Local History

Visual: exit or use a second terminal, then run the learning command.

Voiceover:

> zFlow can import local bash and zsh history, then rebuild a local recommendation index.

On-screen actions:

```bash
zflow learn
```

### 4. Suggestions

Visual: start zFlow again, type a command prefix, and show suggestions appearing in the candidate area.

Voiceover:

> As you type, zFlow offers command suggestions from your local history and recent workflow. Suggestions are previewed first; by default, selecting one fills the input rather than executing it immediately.

On-screen actions:

```bash
zflow
```

Type a familiar prefix such as:

```bash
git
```

Then select a suggestion using the UI.

### 5. Evaluation

Visual: run the evaluation command.

Voiceover:

> You can also evaluate recommendation quality on your own machine. zFlow compares history-only, retrieval-assisted, and feedback-assisted strategies locally.

On-screen actions:

```bash
zflow eval
```

### 6. Privacy Close

Visual: show the config/data path and return to the product name.

Voiceover:

> zFlow is local-first. Learning data is stored under your home configuration directory, and command history is not uploaded by default.

On-screen text:

```text
~/.config/zflow/
```

Final line:

> Install it with npm and try it in your own terminal workflow.

## Capture Notes

- Record on macOS using a clean terminal profile with readable font size.
- Use a shell history that contains realistic but non-sensitive commands.
- Do not show private repository names, secrets, tokens, customer names, internal hostnames, or personal paths.
- Keep the final video either as a GitHub-uploaded asset or a stable hosted URL.
- Replace the README placeholder image link after the final video is ready.

## Assets Needed

- Final screen recording, ideally MP4 or WebM.
- Video thumbnail image.
- Optional short silent GIF for GitHub README fallback.
