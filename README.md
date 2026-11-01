# UIW CSEC Interactive Course Planner

Interactive course planner for the B.S. in Cyber Security (CSEC) at the University of the Incarnate Word.

**Live site:** https://csecplanner.netlify.app/

Students mark their completed, enrolled and planned courses. The planner checks prerequisites and Spring/Fall availability, builds a semester-by-semester plan to graduation, and emails the plan to their advisor with **✉ Email Plan**.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole planner: a single page with the course data built in. It uses D3 from cdnjs. |

## Deploy

Upload `index.html` to the Netlify site (drag and drop the folder in Netlify, or connect this repository).

## Updates

Make changes on a branch and open a pull request against `main`. Each release changes course availability, substitutions or advising notes for the next registration term.

This repository contains only the public planner. Advising records, rosters and analysis data are kept elsewhere and are never committed here.
