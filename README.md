# Guess the Share

An interactive guessing game about immigration in the United States. Students make five “out of 100” guesses, see each real figure drawn as a grid of 100 people, and compare their guesses with what Americans guessed in a national survey. By Gwen Sharp, as a companion to Chapter 12 (Immigration and Urbanization) of *A Sociology Experiment*.

**Live site:** https://gsharpokie.github.io/immigrantshare/

## What it does

- **Five guesses:** the share of U.S. residents who are immigrants; the shares of immigrants who were born in Mexico, who lack legal authorization, and who are Muslim; and the share of workers who are immigrants.
- **After each guess:** the student’s guess, the actual figure, and (where a survey asked) Americans’ average guess appear side by side as grids of 100 dots.
- **The fuller picture:** nearly everyone overestimates; people overestimate small groups in general; beliefs about who immigrants are matter more than how many there are; and the share is near a historic high but fell in 2025.
- **Discussion questions.**

## For instructors

To show all the answers without playing, add `#answers` to the link: https://gsharpokie.github.io/immigrantshare/#answers

## Data

- **Actual figures:** Pew Research Center, “What the Data Says about Immigrants in the U.S.” (August 21, 2025): 15.4% of U.S. residents and 19% of the labor force in June 2025; 22% of immigrants born in Mexico and 27% unauthorized in 2023. https://www.pewresearch.org/short-reads/2025/08/21/key-findings-about-us-immigrants/
- **What Americans guessed:** Alesina, Alberto, Armando Miano and Stefanie Stantcheva. 2023. “Immigration and Redistribution.” *Review of Economic Studies* 90(1): 1–39. U.S. survey of 4,500 U.S.-born adults, January–February 2018: average guess 36% immigrants (actual 10% legal, 13.5% including unauthorized); average guess 23% of immigrants Muslim (actual about 10%).
- **Why people overestimate small groups:** Landy, David, Brian Guay and Tyler Marghetis. 2018. “Bias and Ignorance in Demographic Perception.” *Psychonomic Bulletin & Review* 25: 1606–1618.
- **Historical shares** (14.8% in 1890, 4.7% in 1970): decennial census.

## Updating it

Pew updates its immigrant fact sheet about once a year. Open `index.html` on GitHub, select the pencil icon, and in `const Q = [` near the top of the `<script>` section change each question’s `actual:` number, its `when:` label, and its `note:` sentence. “The fuller picture” and “About the data” are plain text and need editing by hand.

## Turning on the site (one time)

Go to **Settings → Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose the **main** branch and the **/ (root)** folder, and select **Save**. Keep Issues turned on so the “Suggest a correction” link works.

## Author

Created by Gwen Sharp ([@gsharpokie](https://x.com/gsharpokie)).

## License

© 2026 Gwen Sharp. Licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/): you may share and adapt it for noncommercial purposes with credit. See [LICENSE](LICENSE). The figures belong to their sources; this license covers the page’s design, text, and code.
