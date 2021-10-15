### Hi there 👋
 
 ## I'm a full stack developer who graduated from App Academy in Aug 2021.
 
 ## I have experience working with both solo projects as well as paired programming formats.
 
 <!--START_SECTION:waka-->
 name: Work Stats Readme

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
 <!--END_SECTION:waka-->
  
 For more information, as well as recent projects, please visit: https://msineath.github.io/

<!--
**msineath/msineath** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
