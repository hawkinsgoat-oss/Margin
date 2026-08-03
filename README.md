# Margin

**Make room for what matters.**

A customizable, all-in-one life management platform — daily planning, tasks,
projects, goals, habits, time tracking, health, nutrition, finance, journaling,
family, and achievements. Every category is optional and user-defined.

Margin measures what other planners don't:

| Metric | Meaning |
|---|---|
| **Margin** | Awake hours minus everything booked — the room left for living |
| **Alignment** | Share of completed work in the categories you starred as priorities |
| **Presence** | How intentional the day felt, logged in the evening reflection |

## Stack

- Single-file vanilla JS app (no build step)
- Supabase — Postgres, auth, row-level security
- Installable PWA (offline-capable, add to home screen)

## Deploy

Static site. No build command. Output directory: `/`

## Local preview

```
python3 -m http.server 8080
```
Then open http://localhost:8080

## Philosophy

Don't optimize your life. Tend to it.
