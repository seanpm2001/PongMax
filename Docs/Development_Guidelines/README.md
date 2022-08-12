
***

# PongMax Docs

## Developer/development guidelines

### Language usage

Depending on what language you write the game in, the functions and variables will be defined differently. The following variables must be included:

- Score `score` - For storing the current score
- High score `highScore` - For storing the high score
- Player1 `PLAYER` - For the first player
- Player2 `CPU` - For the second player

The following functions also must be included:

- Left paddle `leftPaddle` - For configuring the left paddle
- Right paddle `rightPaddle` - For configuring the right paddle
- Ball `ball` - For configuring the ball

### File usage

The game must consist of only a single program file. If the programming language you use strictly requires a secondary file, with absolutely no workaround, then a second file can be included. However, graphics can be included separately if graphics can't be embedded via SVG, binary, or other methods.

### Libraries

Each Pong variant must include a comment at the top of the file regarding what library is in use.

### Shebang

If the programming language in use supports shebangs, please use one.

### Complexity

We don't want a complex game of Pong here. There should only be the 4 variables. The game should be 3D, and only consist of the colors black and white.

We also want each individual variation to be too large. Please keep your program file under 4 kilobytes if possible, and under 100 kilobytes always, and try to use only 100 lines of code or less, unless this is impossible in the programming language you are using.

### Document your source code

Make sure to add comments to your source code, so that others can better understand it.

### Keep your source code moral

Even if you are writing in `BrainF*ck`, please avoid using swears, slurs, epiphets, and other inappropriate words in your variable names and comments, and everywhere in your program. Keep it friendly.

### Differentiating between platform and language

How to differentiate between platform and language:

A language variant is executed solely through the languages interpreter. A platform variant can contain more than 1 language, but is dependant on a package format (such as `APK` for Android, `DEB` for Debian, `SNAP` for Snapcraft, `IPA` for iOS, `APP` for MacOS, `UWP` for Windows universal platform, `EXE` and `MSI` for Windows programs, etc.)

### Don't be malicious

Do not:

- make the program proprietary
- Require encryption
- Prevent use when not connected to the Internet
- apply forkbombs to the user session, 
- Add DRM
- Display advertisements
- Include trackers of any kind
- Include or activate other malware/ransomware/spyware
- Set time limits
- Install other programs
- Change the system time
- Do anything that isn't listed here that is deemed malicious

### License disclaimer

The variants of PongMax are by default licensed under the GNU General Public License V3.0. If you prefer the `Unlicense` you can request a license change for your programmed variant to use it. No other software licenses are allowed here.

***

### File info

<details open><summary><p lang="en"><b><u>Click/tap here to expand/collapse this section</u></b></p></summary>

**File type:** `Markdown (*.md *.mkd *.mdown *.markdown)`

**File version:** `1 (2022, Thursday, August 11th at 8:55 pm PST)`

**Line count (including blank lines and compiler line):** `132`

**Current article language:** `English (EN_USA)` / `Markdown (CommonMark)` / `HTML5 (HyperText Markup Language 5.3)`

**Encoding:** `UTF-8 (Emoji 12.0 or higher recommended)`

**All times are UTC-7 (PDT/Pacific Time)** `(Please also account for DST (Daylight Savings Time) for older/newer entries up until it is abolished/no longer followed)`

_Note that on 2022, Sunday, March 13th at 2:00 am PST, the time jumped ahead 1 hour to 3:00 am._

**You may need special rendering support for the `<details>` HTML tag being used in this document**

</details>

***

## File history

<details><summary><p lang="en"><b>Click/tap here to expand/collapse the file history section for this project</b></p></summary>

<details><summary><p lang="en"><b>Version 1 (2022, Thursday, August 11th at 8:55 pm PST)</b></p></summary>

**This version was made by:** [`@seanpm2001`](https://github.com/seanpm2001/)

> Changes:

- [x] Started the file
- [x] Added the title section
- [x] Added the `language usage` section
- [x] Added the `file usage` section
- [x] Added the `libraries` section
- [x] Added the `shebang` section
- [x] Added the `Document your source code` section
- [x] Added the `Keep your source code moral` section
- [x] Added the `Differentiating between platform and language` section
- [x] Added the `Don't be malicious` section
- [x] Added the `License disclaimer` section
- [x] Added the `file info` section
- [x] Added the `file history` section
- [ ] No other changes in version 1

</details>

</details>

***
