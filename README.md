# Aisle Five

Aisle Five is a public website where you can find safety and efficacy information for common over-the-counter medicications. **[aislefive.netlify.app](https://aislefive.netlify.app)**.

On the site, there are over 200 medications, all commonly available at pharmacies across the USA. These include pain relievers, cold medicines, allergy drugs, antacids, sleep aids, eye drops and a whole lot more. Each entry has safety, efficacy, and overall scores out of 10, the brand and generic name, a short note on what it's for, a few things to look out for, and two sources you can click through to.

The medications are split into eight categories. Those are Pain & Fever, Cold & Cough, Allergy, Stomach & Gut, Sleep & Motion, Skin & Hair, Eyes, Ears & Mouth, and Other.

## The scores

Efficacy is how well the medicine does what it's sold for, based on the clinical evidence. Safety is how risky it is to take.

The overall score is based on both safety and efficacy together. However, the average score isn't always just the average of the two, an example of this is Sudafed PE. It's fairly safe (7), but the pill version barely works (2), so it only gets a 3/10 overall. Benadryl does work for allergies (efficacy of 6), but its safety score is a 1, so it ends up with a 2/10.

The score rings are green for 8 to 10, yellow for 6 or 7, and red for 5 and under. At the moment Narcan, Tums and Pedialyte are the only ones with a 10 overall.

## Sources

Every entry links to two sources. One is the StatPearls chapter for that drug on the NCBI Bookshelf, and the other is a study from PubMed.

This isn't medical advice. The scores I put on the site are my interpretation of published evidence, and that data is always subject to change. Before making any medical decision, you should always check the label and ask a pharmacist if you're not sure.

## Using the site

You can search by brand name or generic name, filter by category, and sort by any of the three scores, high to low or low to high. Tap a card to open the full entry. From there you can go to the next or previous medicine with the arrows (or the arrow keys on your computer). Every entry has its own link, like [aislefive.netlify.app/#advil](https://aislefive.netlify.app/#advil), so if you'd like, you can share a direct link to an entry.

On the site, I've added background music to add to the store theme. You can turn it off with the button in the corner. Tapping cards also makes small sound effects.

(SONG CREDIT: "Hold on a Minute - Silent Partner")

## What's in here

`index.html` is the entire site. There's nothing you need to install. It's a little over 2 MB because of the sound files.

`data/medicines.csv` is every entry in one table, with the scores, notes and source links. GitHub shows it as a table you can search. It's copied from the list inside `index.html`, so if the two ever don't match, go with `index.html`.

## Running it yourself

Download `index.html` and open it in a browser. You'll need internet for the fonts and the source links, but everything else is in the file. To host your own copy, upload that one file to any host.

## AI disclosure

In making this project, I used Claude, an AI tool created by Anthropic, for parts of it. I came up with the idea, made all of the design choices, decided on every feature, did all of the research to come up with safety and efficacy information, created the safety, efficacy, and overall scores, and wrote the GitHub page you're reading right now! Claude was the tool I used to turn all of that into a working website.
