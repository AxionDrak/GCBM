# GCBM
GameCube Backup Manager - a software to convert ISO files to Nintendont format.

![GitHub License](https://img.shields.io/github/license/AxionDrak/GCBM)
![GitHub Release](https://img.shields.io/github/v/release/AxionDrak/GCBM)
![GitHub Release Date](https://img.shields.io/github/release-date/AxionDrak/GCBM)
![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/AxionDrak/GCBM/total)
![GitHub branch status](https://img.shields.io/github/checks-status/AxionDrak/GCBM/main)
![Docker Image Version](https://img.shields.io/docker/v/AxionDrak/GCBM)

# GameCube Backup Manager
**GCBM (GameCube Backup Manager)** is a program to work with FAT32, exFAT and NTFS drives *(NTFS devices only work as a backup, they don't work on Nintendont)* allowing you to correctly convert ISO files for use on Nintendont.

**THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.**

**Download:**

All Releases: https://github.com/AxionDrak/GCBM/releases

Old version (archived - 100% functional): https://github.com/AxionDrak/GameCube-Backup-Manager/releases

**Features:**
- Individual or batch file transfer *(v2.5.0.0 or higher)*
- Reads ISO / GCM / NKit *(ISO only - not GCZ)*.
- Writes ISO
- Execution of multiple instances of the program.
- Load the 'wiitdb.xml' file in the 'Database' tab and preview its contents *(a good option for discovering new games!)*.
- Automatic update system.
- Proxy system.
- Cover transfer *(WiiFlow, WiiFlow Lite, WiiFlow Fusion)*.
- Cover transfer *(USB Loader GX, USB Loader GX Tab MOD)*.
- Transferring games with the correct nomenclature *(Game Name+ID or ID only)*. ***Available in “Install Game (1:1)” mode using the commercial name via ‘wiitdb.xml’. The “Install Game (Scrub)” mode uses the internal nomenclature provided by the developer, that is, it does not use ‘wiitdb.xml’***.
- Game transfer via XCopy *(1:1 copies - Standard)*.
- Game transfer via Scrub *(GCReEx and DiscEx)*.
- Deleting game files *(Source and Destination)*.
- Display of game information *(region, publisher, genre, etc)*. ***File ‘wiitdb.xml’ required***.
- ESRB ratings display. ***File ‘wiitdb.xml’ required***.
- WiiTDB support for naming. ***File ‘wiitdb.xml’ required***.
- Improved GameCube ISO detection in 'internal' mode *(Standard)*.
- Improved GameCube ISO detection in 'external' mode *(GameTDB)*. ***File ‘wiitdb.xml’ required***.
- Global download of Disc and 3D covers *(for all games listed!)*.
- Individual download of covers for the selected game *(Disc and 3D)*.
- Download the file 'wiitdb.xml' *(GameTDB)*.
- MD5 hash Calculation *(manual option)*.
- SHA-1 Hash Calculation *(manual option)*.
- Automatic creation of 'games' folder *(if it doesn't exist)*.
- LOG system.
- Multiple languages supported:
--- Portuguese (Brazil)
--- English (United States)
--- Spanish (Spain)
--- Others

**Requirements**
- .NET 8
- Microsoft Windows 64-bit ***(32-bit not supported!)***.
