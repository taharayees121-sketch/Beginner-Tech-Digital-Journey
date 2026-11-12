
## Linux Learning Progress — October 29, 2026

### Environment Setup
- [x] Installed and opened Ubuntu using WSL on Windows.
- [x] Checked Ubuntu version using `lsb_release -a`.
- [x] Updated package information using `sudo apt update`.

### Linux Commands Learned
- [x] `pwd` — display the current working directory.
- [x] `ls` — list files and folders.
- [x] `whoami` — display the current username.
- [x] `mkdir` — create a directory.
- [x] `cd` — change the current directory.
- [x] `touch` — create an empty file.
- [x] `echo` — display text.
- [x] `>` — write text to a file, replacing existing contents.
- [x] `>>` — append text to a file.
- [x] `cat` — display file contents.
- [x] `ls -l` — display detailed file information.

### Hands-on Practice
- [x] Created the directory `day3-practice`.
- [x] Navigated into the directory using `cd`.
- [x] Verified the current path using `pwd`.
- [x] Created `notes.txt` using `touch`.
- [x] Saved text into `notes.txt` using `echo` and `>`.
- [x] Verified saved text using `cat`.
- [x] Inspected file details using `ls -l`.

### Concepts Understood
- Linux is an operating system.
- Ubuntu is a Linux distribution.
- WSL allows Linux to run within Windows.
- The terminal accepts commands to interact with Linux.
- `/home/tahar/day3-practice` is my practice directory.
- `notes.txt` is a file inside that directory.
- A filename is not automatically a terminal command.
- `>` replaces file contents, while `>>` appends text.

### Next Linux Topics
- [ ] Learn Linux directory navigation in more detail.
- [ ] Learn to copy, move, rename, and delete files safely.
- [ ] Understand Linux file permissions.
- [ ] Learn basic networking commands.
- [ ] Practise Linux troubleshooting.

### Learning Evidence
Practice directory: `/home/tahar/day3-practice`

Practice file: `notes.txt`

Verified file content:
`Day 3: I created my first Linux file.`

**Status:** Linux fundamentals — beginner practice in progress.

## Linux Commands – File Management (Day 4)

### 1. cp – Copy a file
Copies a file from one name to another.

```bash
cp a.txt b.txt
```

### 2. mv – Move a file
Moves a file into another directory.

```bash
mv a.txt Documents/
```

### 3. rm – Delete a file
Deletes a file.

```bash
rm a.txt
```

### 4. rmdir – Delete an empty folder
Removes an empty directory.

```bash
rmdir test
```

### 5. head – Display first 10 lines
Shows the first 10 lines of a file.

```bash
head notes.txt
```

### 6. tail – Display last 10 lines
Shows the last 10 lines of a file.

```bash
tail notes.txt
```

### 7. less – Read long files
Opens a file for scrolling and reading.

```bash
less notes.txt
```

**Important:** Press `q` to exit `less`.

### Learning Summary
- Learned file copying and moving.
- Learned file and empty-folder deletion.
- Learned how to read the beginning and end of files.
- Learned how to view long text files.

**Status:** Commands studied and understood. Practical execution not yet confirmed.
## Linux Learning Progress — November 12, 2026

### Linux Filesystem and Navigation
- `/` — Root directory.
- `/home/tahar` — My home directory.
- `~` — Shortcut for my home directory.
- `.` — Current directory.
- `..` — Parent directory.
- `cd` — Change directory.
- `ls` — List files and folders.
- Located my GitHub repository at `~/Beginner-Tech-Digital-Journey`.
- Located my existing Linux notes at `linux/linux-Notes.md`.

### Linux File Permissions
- `r` — Read (4).
- `w` — Write (2).
- `x` — Execute (1).
- `u` — Owner.
- `g` — Group.
- `o` — Others.

Permission number examples:
- `7` = Read + Write + Execute.
- `6` = Read + Write.
- `5` = Read + Execute.
- `4` = Read only.
- `644` = `rw-r--r--`.
- `755` = `rwxr-xr-x`.

### Commands Learned
- `chmod` — Change file permissions.
- `chown` — Change file ownership.
- `stat` — Display detailed file information.
- `sudo` — Run authorised commands with administrator privileges.
- `whoami` — Display current username.
- `id` — Display user ID and group information.
- `sudo apt update` — Refresh Ubuntu package information.

### Practical Exercises Completed
- [x] Checked my home directory using `pwd`.
- [x] Listed files using `ls`.
- [x] Located my existing GitHub repository.
- [x] Inspected my existing Linux folder.
- [x] Read my Linux notes using `cat`.
- [x] Successfully executed `sudo apt update`.
- [x] Checked my username using `whoami`.
- [x] Checked UID, GID and group memberships using `id`.

### My Ubuntu User Information
- Username: `tahar`.
- UID: `1000`.
- Primary GID: `1000`.
- Member of the `sudo` group.
- 54 packages were reported as available for upgrade.

### Next Topics
- [ ] Practise inspecting permissions with `ls -l`.
- [ ] Learn file ownership with `stat`.
- [ ] Practise safe permission changes.
- [ ] Continue Linux troubleshooting.

**Status:** Linux filesystem navigation, permissions, user identity and administrator commands studied. Practical permission changes and ownership changes still need practice.
