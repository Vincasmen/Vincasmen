Hello,

🙋Jan
🏙️Brno
🔞29

<!--START_SECTION:waka-->

name: Waka Readme

on:
  schedule:
    # Runs at 12am IST
    - cron: '30 18 * * *'
  workflow_dispatch:
jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: ubuntu-latest
    steps:
      - uses: anmol098/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY=<1a1b6dd4-40b1-4566-a959-07c023f1bca5> }}
          GH_TOKEN: ${{ secrets.GH_TOKEN=<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> }}

<!--END_SECTION:waka-->


<!---
Vincasmen/Vincasmen is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
