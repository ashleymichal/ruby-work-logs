# Project Journal

## Basic idea:

The Novelist's Bullet Journal tracks "meta-text", specifically "canon" and
"process" meta-text. Canon meta-text is writing about your writing; they are
ideas that have solidified into decisions. Process metatext is about how you
write. Usually in the form of a session log tracking tasks and notes. There
are three parts to the journal: the index, which shows the location of various
collections; session logs, which are created during each "session" of work and
document that day's tasks and canon decisions; and collections, which are
larger pieces of canon metatext.

Similarly, the engineer's work log tracks meta-data relevant to the execution
of a project. From Scott Bellware's instructions:

> At a minimum, record decisions made, directions taken, plans made, plans
> changed or re-assessed, setbacks, work preempted or missed, problems faced,
> realizations had, learnings, conflicts, resolutions, and generally, notes of
> things you want to remember or remark upon.

A markdown file is generally sufficient for all of this. Some notes are not
worth revisiting. Thatbeing said, I find the concept of a Collection very
useful, especially for long term projects. Being able to browse the log for
Collections or Tags is useful.

As an exercise, I will write a companion app for a project journal, which will
provide an interface for navigating it.

Users should be able to:

- View logs in the UI as individual pages (parse and write static pages)
- Paginate logs in the UI
- View logs in the UI as a continuous scroll (v. React-based)
- Insert logs either manually or via CLI
- Mark tasks as completed (x bullet) or unnecessary (strike through)
- View an index of collections and navigate to a specific collection
    - could be achieved with a TOC generator and static site generator
- View an index of tags and navigate to a view which aggregates them by date
    - could be achieved by parsing markdown into sqlite db and generating pages
      from that
- Use a date-picker to navigate to the logs for a specific day
    - could use react to highlight days with logs
- [Big feature] be able to add to a collection or session log from the UI

