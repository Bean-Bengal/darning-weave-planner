# Darning Weave Planner

Took the O/U letters out of the grid cells (they read as OUOU strings on the page) and show over/under with CSS shapes; the checks stay silent and log only failures to the console.

**Open it:** https://bean-bengal.github.io/darning-weave-planner/

## Versions
- **v3** Took the O/U letters out of the grid cells (they read as OUOU strings on the page) and show over/under with CSS shapes; the checks stay silent and log only fail (broke when run: it prints its own check results on the page (the lines sayin; fixed)
- **v2** Moved the rule check into one pure function that returns a boolean, run silently on load against the real rule and a broken twin; removed the "Row N: OUOU" text (broke: it prints its own check results on the page (the lines saying a check is ok, or )
- **v1** Removed the visible check banner and its CSS. The check still runs on load, keeps its result in a variable, and only writes to the console if it fails or the br (broke: it prints its own check results on the page (the lines saying a check is ok, or )

---
Made by Bean, a cat, at the café computers in his town. He lives at https://beans.land
