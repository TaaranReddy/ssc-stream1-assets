# IEM Stream 1 — student agenda

A small static page that answers one question: **what is actually due, and where did that claim come from?**

Live: <https://taaranreddy.github.io/ssc-stream1-assets/>

Run by the Stream 1 SSC Chair. **Not an official Imperial College Business School page.** Canvas and the programme team remain the source of truth. If this page and Canvas disagree, Canvas wins — and please tell the Chair so it can be fixed.

## What's on it

- **Next deadline** — the soonest dated item, with a direct link where one exists.
- **This week, day by day** — Monday to Sunday, with previous/next week navigation and a "return to today" link.
- **Coming up** — everything dated beyond this week.
- **Raised with the programme team** — the SSC issue tracker, anonymised.
- A linked archive of every week page that has been generated.

Every single item carries two things: a **source** (which email, which Canvas page) and a **confidence** label.

| Label | Meaning |
|---|---|
| Confirmed in writing | Read from Canvas, or quoted from a programme email |
| Announced, no time given | The date is stated; the time is not |
| Unconfirmed | The Chair's own plan or inference — treat as provisional |

## What it does *not* know

This is the important part.

1. **Timetabled teaching is not here.** Lectures, seminars and room changes live in the College timetable, not in Canvas assignments. They only appear on this page when a programme email has announced them. **An empty day on this page is not evidence of a free day** — check your own timetable.
2. **The Canvas read is a snapshot, not a live feed.** Assessment deadlines are read directly from Canvas at build time and the page states that timestamp. If a tutor moves a deadline afterwards, this page will not know until it is rebuilt.
3. **Only cohort-wide dates are shown.** Items overridden for a specific section or individual are deliberately excluded, because a personal override is not a fact about the cohort.
4. **The page can be stale.** "Page built" and "newest source" are shown separately in the header, on purpose — a recent build does not mean recent information.

## Privacy

- No student names. The issue tracker is maintained privately and anonymised at render time; the source file is never published.
- No personal calendar data. A personal Canvas ICS feed is used only offline, to detect date drift against the published set; its contents are never rendered or committed.
- No analytics, no cookies, no JavaScript, no third-party requests. The page is a single self-contained HTML file with inline CSS.
- The repository publishes only generated HTML and this README.

## Corrections

If something here is wrong, out of date, or shouldn't be public, message the Stream 1 SSC Chair and it will be corrected or removed. Getting a date wrong on this page is worse than not listing it, so mistakes are worth reporting.
