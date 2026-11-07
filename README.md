# ⚓ Anchor App

> *Your Academic Anchor at university.*

Anchor represents **stability**. It is a school-university super app: upload your syllabus, and Anchor builds a schedule with all the important dates for you.

We all had that one "Academic Anchor" buddy in college: the person who knew the syllabus by heart and helped everyone with deadlines and formats. Anchor is that buddy, built into an app.

---

## Table of Contents

- [What and Why?](#what-and-why)
- [Who Is It For?](#who-is-it-for)
- [How It Works](#how-it-works)
- [Scope](#scope)

---

## What and Why?

### What we want to build

A **full stack mobile app** that turns a syllabus into a usable schedule and to-do list. It is also a practical way to apply what we already know and to learn a lot more during the semester.

### The problem

Many students never actually read their syllabi, because:

1. **Scattered platforms:** some professors use tools other than the university's standard platform.
2. **Length:** syllabi are long, and some courses have more than one.
3. **Attention span:** in the short-attention-span era, nobody wants to dig through 20 pages for a deadline.

Syllabus week is overwhelming, with many different apps for many different tasks. What students really want is **one simple to-do list and calendar**.

### Why it matters

Missed deadlines and misunderstood assignment formats are avoidable. Anchor gives students an **ultimate calendar** with every important date, assignment, and format in one place, plus a weekly to-do list for assignments, readings, and upcoming quizzes.

---

## Who Is It For?

| User | Details |
|---|---|
| **University students** | Primary users |
| **School students** | Potential users, if their school provides a syllabus |

### Free vs. Pro

| Feature | Free | Pro |
|---|:---:|:---:|
| Course creation and syllabus upload | ✅ | ✅ |
| AI-extracted events and assignments | ✅ | ✅ |
| Dashboard, Calendar, Courses pages | ✅ | ✅ |
| Google Calendar sync | ✅ | ✅ |
| **Weekly to-do list** (assignments, readings, quizzes) | ❌ | ✅ |

---

## How It Works

From the end-user's perspective:

1. **Create a course** by adding its information manually and uploading the syllabus.
2. **AI reads the syllabus** and adds all the important events and assignments.
3. **Review and edit.** If the AI made a mistake, you can fix it.
4. **Stay on track** using the three main pages below.
5. **Sync** everything with your Google Calendar through the Google API.

### Main pages

| Page | What it shows |
|---|---|
| **Dashboard** | A short digest of upcoming events and what needs to be done this week |
| **Calendar** | A calendar of all important events across every course |
| **Courses** | Every course you take, with its list of assignments and key syllabus details (added by you or by the AI) |

---

## Scope

> *Draft justification for a team of about 4-6 programmers over one semester.*

**Not too easy.** The project combines several non-trivial parts:

- A full stack mobile app (front end, back end, database, user accounts)
- AI-based extraction of dates, assignments, and formats from unstructured syllabus files
- A review-and-edit flow so users can correct AI mistakes
- Google Calendar integration through an external API
- A free/pro feature split

**Not too ambitious.** The scope is deliberately limited:

- The core loop (upload, extract, review, view, sync) is well defined and can be split across team members (mobile UI, back end, AI pipeline, integrations, testing).
- Integrations with university-specific platforms are **out of scope**; users upload the syllabus themselves.
- School-student support relies on the same syllabus-upload flow, so it needs no separate system.
- The weekly to-do list is built on top of data already extracted for the calendar, which keeps the pro tier manageable.

