### Hi there 👋

#### I'm a Freelancer.

##### NOW

- ✨ Crafted last [Shopping App](https://github.com/vincedaniel08/TechwareMobileApp) Mobile App;


##### BIO

- 🏢 I'm currently studying at **Bulacan State University**
- ⚙️ I use daily: `.php`, `.js`, `.html`, `.css`, `.java`, `.psd`, `.prpproj`
- 🌍 I'm mostly active within the **React Community**
- 🌱 Learning all about **Open Source**
- 💬 Ping me about **design**, **branding**, **logical**, **development**, **design thinking**
- ⚡️ Fun fact: I'm a huge fan of One Piece

name: Waka Readme

on:
  workflow_dispatch:
  schedule:
    # Runs every 2 hours
    - cron: "0 */2 * * *"

jobs:
  update-readme:
    name: Update this repo's README
    runs-on: ubuntu-latest
    steps:
      - uses: athul/waka-readme@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
