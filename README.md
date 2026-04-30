# fent.

a study tracker i had built for myself. sharing it in case it helps someone else in the same boat.

built this for **jee 2027 droppers** who want to actually know where they stand, not just vaguely feel behind. no fluff, no gamification, just your syllabus and your progress laid out cleanly.

the schedule covers the entire jee syllabus across maths, chemistry, and physics, broken down chapter by chapter from **april 2026 to october 2026**. every chapter has a start and end date. you either finish it or you don't. the tracker knows.

## what's inside

### overview, this week's plan

<img width="1079" height="1120" alt="1" src="https://github.com/user-attachments/assets/3612ea0c-4260-4f1f-9ae9-67eec0b49f8c" />


shows you exactly what you're supposed to be doing in the current 7 day window. chapters that fall in this week, their subject tags, how many tasks you've done, and whether any tests are scheduled. you can also browse past or future weeks with the prev/next buttons. the progress bar at the top fills up as you tick things off. simple.

### subject lists, maths, chem, physics

<img width="1148" height="1051" alt="2" src="https://github.com/user-attachments/assets/1c9a5c92-ebc1-4773-a754-3f59fe58cc48" />


each subject has every chapter listed with its scheduled date. click a chapter to expand it and you get four checkboxes, **theory, module, pyq, revision**. these four are what done means. a chapter is only marked complete when all four are ticked. you can filter by all, in progress, completed and search by name.

### analytics

<img width="1064" height="1131" alt="3" src="https://github.com/user-attachments/assets/7633fe9a-cdda-4581-9d5a-cd30262eab12" />


a quick dashboard of where things actually stand. three ring charts for maths, chem and physics showing completion percentages. below that, completion by type so you can see if you're doing theory but skipping pyqs, you probably are. then average marks for mains and advanced tests recorded so far.

### study heatmap

<img width="1400" height="848" alt="4" src="https://github.com/user-attachments/assets/3e7ea00a-c1b0-45da-a2c5-585493cb27c7" />


this one is my favourite. a github style heatmap that shows every day from april to october. each cell is a day, the colour tells you how much study activity happened on that day. click any cell and it shows you exactly which chapters you worked on and how many tasks got done. you can filter by month using the tabs at the top. if a week looks empty you already know what that means.

the heatmap records activity on the actual date you tick a task, so it's a real log of what you did and when, not just estimated.

### backlog tracker

<img width="1221" height="980" alt="5" src="https://github.com/user-attachments/assets/a55e6950-7b69-42cc-b47e-59a1e40e0779" />


if the current date has passed a chapter's deadline and it's not done, it shows up here as overdue. you get a status, **on track, slightly behind, danger zone**, based on how many chapters are past due. it lists every overdue chapter with how many days late it is and which subject it belongs to. pretty good at making you feel bad in a productive way.

## test schedule

tests are baked into the schedule. every month from may to october has,
- **3 mains tests** on sundays
- **1 advanced test** on the last sunday of the month

you can log your scores, physics, chemistry, maths separately, and the tracker keeps a score trend chart and running averages. mains is out of 300, advanced is out of 360.

## how to use

just open `https://fent-nu.vercel.app/` in a browse


## honest notes

- built for personal use, schedule is tuned to my own syllabus ordering
- dates and chapter ordering are opinionated, roughly follows standard dropper batch flow
- nothing is synced anywhere, it's all local
- the design is dark oled because i prefer that

if it's useful to you, nice. if you want to fork it and adjust the chapter list or dates, the data is all at the top of the html file, just edit the `MATH`, `CHEM`, `PHYS` arrays.

