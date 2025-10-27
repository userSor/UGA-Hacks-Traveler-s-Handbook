# The Traveler's Handbook (UGAHacks 8)

A 48-hour hackathon project built by a 9-person team for **UGAHacks 8 (Feb 2023)**.

The Traveler's Handbook is a dynamic website designed to help users research travel by consolidating flight data, cultural information, and language basics for any country.

* **Devpost:** [View the original Devpost submission](https://devpost.com/software/the-traveler-s-handbook)
* **Original Codebase:** [View the team's GitHub repository](https://github.com/KevintrDo/UGAHacks)

**Note:** _This repository is a portfolio `README.md` created to detail my specific contributions to the team project. The complete source code is hosted on the original team repo linked above._



## Tech Stack

* **Languages:** HTML, CSS, JavaScript, Python
* **Frameworks/Tools:** Flask, Node.js, Maven
* **APIs & Data:** RapidAPI (Flight Radar API), Google Translate API, JSON
* **Version Control:** Git & GitHub



## My Role & Contributions

As a developer on a 9-person team, my primary responsibility was building the **critical link between the user's search and the data display**.

I personally designed and wrote the core **JavaScript** logic that made the site dynamic:

1.  Captured the user's search query (e.g., "USA") from the HTML input form on the homepage.
2.  Dynamically constructed a new URL, passing the user's query as a **URL parameter** (e.g., `.../Website.html?country=USA`).
3.  On the `Website.html` page, I wrote the client-side script to read this URL parameter.
4.  This script then used the extracted country name to make a live call to the **Flight Radar API**, fetch the correct flight data, and populate the page.

In short, I owned the **front-end to back-end integration**, turning our static HTML pages into a data-driven application.
