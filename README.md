Hello,

🙋Jan
🏙️Brno
🔞29

<!--START_SECTION:waka-->
<!--END_SECTION:waka-->

name: Waka Readme

on:
  workflow_dispatch:
  schedule:
    # Runs at 12am UTC
    - cron: "0 0 * * *"
  
  
jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: ubuntu-latest
    steps:
      - uses: Vincasmen/Vincasmen@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY}}
          GH_TOKEN: ${{ secrets.GH_TOKEN}}




<!---
Vincasmen/Vincasmen is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
