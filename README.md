# fent-tracker

a study tracker i built for myself. sharing it in case it helps someone else in the same boat.

built this for **jee 2027 droppers** who want to actually know where they stand, not just vaguely feel behind. no fluff, no gamification, just your syllabus and your progress laid out cleanly.

the schedule covers the entire jee syllabus across maths, chemistry, and physics, broken down chapter by chapter from **april 2026 to october 2026**. every chapter has a start and end date. you either finish it or you don't. the tracker knows.

## what's inside

### overview, this week's plan

![overview](1777585504718_image.png)

shows you exactly what you're supposed to be doing in the current 7 day window. chapters that fall in this week, their subject tags, how many tasks you've done, and whether any tests are scheduled. you can also browse past or future weeks with the prev/next buttons. the progress bar at the top fills up as you tick things off. simple.

### subject lists, maths, chem, physics

![subject list](1777585547960_image.png)

each subject has every chapter listed with its scheduled date. click a chapter to expand it and you get four checkboxes, **theory, module, pyq, revision**. these four are what done means. a chapter is only marked complete when all four are ticked. you can filter by all, in progress, completed and search by name.

### analytics

![analytics](1777585590057_image.png)

a quick dashboard of where things actually stand. three ring charts for maths, chem and physics showing completion percentages. below that, completion by type so you can see if you're doing theory but skipping pyqs, you probably are. then average marks for mains and advanced tests recorded so far.

### study heatmap

![heatmap](1777585674566_image.png)

this one is my favourite. a github style heatmap that shows every day from april to october. each cell is a day, the colour tells you how much study activity happened on that day. click any cell and it shows you exactly which chapters you worked on and how many tasks got done. you can filter by month using the tabs at the top. if a week looks empty you already know what that means.

the heatmap records activity on the actual date you tick a task, so it's a real log of what you did and when, not just estimated.

### backlog tracker

![backlog](1777585705254_image.png)

if the current date has passed a chapter's deadline and it's not done, it shows up here as overdue. you get a status, **on track, slightly behind, danger zone**, based on how many chapters are past due. it lists every overdue chapter with how many days late it is and which subject it belongs to. pretty good at making you feel bad in a productive way.

## test schedule

tests are baked into the schedule. every month from may to october has,
- **3 mains tests** on sundays
- **1 advanced test** on the last sunday of the month

you can log your scores, physics, chemistry, maths separately, and the tracker keeps a score trend chart and running averages. mains is out of 300, advanced is out of 360.

## how to use

just open `fent_work.html` in a browser. no server, no install, no account. everything saves to your browser's local storage.

if you clear local storage you lose your progress. so don't do that.

## honest notes

- built for personal use, schedule is tuned to my own syllabus ordering
- dates and chapter ordering are opinionated, roughly follows standard dropper batch flow
- nothing is synced anywhere, it's all local
- the design is dark oled because i stare at this at 2am

if it's useful to you, nice. if you want to fork it and adjust the chapter list or dates, the data is all at the top of the html file, just edit the `MATH`, `CHEM`, `PHYS` arrays.

