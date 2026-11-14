# Guess the Share

An interactive guessing game about immigration in the United States. Students make seven “out of 100” guesses about today and the past, see each real figure drawn as a grid of 100 people, and compare their guesses with what Americans guessed in a national survey. By Gwen Sharp.

**Live site:** https://gsharpokie.github.io/immigrantshare/

## What it does

- **Seven guesses:** the share of U.S. residents who are immigrants; the shares of immigrants who were born in Mexico, who lack legal authorization, and who are Muslim; the share of workers who are immigrants; the immigrant share in 1970; and the share of today’s immigrants born in Europe (75 in 100 in 1960).
- **Then and now:** a line chart of the immigrant share of the population from 1850 to 2024, and bars comparing where immigrants were born in 1960 and 2024.
- **After each guess:** the student’s guess, the actual figure, and (where a survey asked) Americans’ average guess appear side by side as grids of 100 dots.
- **The fuller picture:** nearly everyone overestimates; people overestimate small groups in general; beliefs about who immigrants are matter more than how many there are; and the share is near a historic high but fell in 2025.
- **Discussion questions.**

## For instructors

To show all the answers without playing, add `#answers` to the link: https://gsharpokie.github.io/immigrantshare/#answers (this also shows the then-and-now charts)

## Data

- **Actual figures:** Pew Research Center, “What the Data Says about Immigrants in the U.S.” (August 21, 2025): 15.4% of U.S. residents and 19% of the labor force in June 2025; 22% of immigrants born in Mexico and 27% unauthorized in 2023. https://www.pewresearch.org/short-reads/2025/08/21/key-findings-about-us-immigrants/
- **What Americans guessed:** Alesina, Alberto, Armando Miano and Stefanie Stantcheva. 2023. “Immigration and Redistribution.” *Review of Economic Studies* 90(1): 1–39. U.S. survey of 4,500 U.S.-born adults, January–February 2018: average guess 36% immigrants (actual 10% legal, 13.5% including unauthorized); average guess 23% of immigrants Muslim (actual about 10%).
- **Why people overestimate small groups:** Landy, David, Brian Guay and Tyler Marghetis. 2018. “Bias and Ignorance in Demographic Perception.” *Psychonomic Bulletin & Review* 25: 1606–1618.
- **Immigrant share of the population, 1850–2010:** 9.7, 13.2, 14.4, 13.3, 14.8, 13.6, 14.7, 13.2, 11.6, 8.8, 6.9, 5.4, 4.7, 6.2, 7.9, 11.1, 12.9 (each census 1850–2000; 2010 American Community Survey). U.S. Census Bureau, “America’s Foreign Born in the Last 50 Years” (2013), https://www.census.gov/content/dam/Census/library/visualizations/2013/comm/foreign-born.pdf, and Gibson and Jung (2006), Census Working Paper 81.
- **2024 share (14.8%), 2024 regions of birth (Latin America 51.4%, Asia 30.8%, Europe 9.7%, Africa 5.9%), and 1850 Europe share (92.2%):** Gryn and Smith, “Foreign-Born Population in the United States Changed Significantly in Both Numbers and Countries of Origin,” U.S. Census Bureau, July 21, 2026. The 2024 “Other” value (2.2%) is the remainder.
- **1960 regions of birth** (Europe 75%, Northern America 10%, Latin America 9%, Asia 5%, other 1%) **and top countries** (Italy, Germany, Canada, United Kingdom, Poland): the 2013 Census infographic above.
- **Italy 13% of immigrants in 1960; Mexico 22% in 2024:** Migration Policy Institute, “Frequently Requested Statistics on Immigrants and Immigration in the United States” (2026).
- **From general knowledge, not checked against a source:** the description of the 1920s national-origin quotas and their end in 1965.

## Updating it

Pew updates its immigrant fact sheet about once a year. Open `index.html` on GitHub, select the pencil icon, and in `const Q = [` near the top of the `<script>` section change each question’s `actual:` number, its `when:` label, and its `note:` sentence. “The fuller picture” and “About the data” are plain text and need editing by hand.

## Turning on the site (one time)

Go to **Settings → Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose the **main** branch and the **/ (root)** folder, and select **Save**. Keep Issues turned on so the “Suggest a correction” link works.

## Author

Created by Gwen Sharp ([@gsharpokie](https://x.com/gsharpokie)).

## License

© 2026 Gwen Sharp. Licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/): you may share and adapt it for noncommercial purposes with credit. See [LICENSE](LICENSE). The figures belong to their sources; this license covers the page’s design, text, and code.
