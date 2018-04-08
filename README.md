# parenting-now-grizzley-bears

![Parenting Now](https://parentingnow.org/wp-content/uploads/2014/10/parentingnowlogo_header.png)

## Introduction

Hi! My name is Jeremy Sher and I'm a senior engineer at [Knack](https://www.knack.com/), an online database and application building platform, where I mostly write JavaScript. I haven't really spent a lot of time using the system as an end user, though, so I decided to use Hack for a Cause as an opportunity to take a deep dive into building apps on the platform I spend my time working on. For my solution to Parenting Now's requirements, I used the Knack platform to create a secure online portal where Parenting Now's educators can manage attendance reports, snack assignments, summary reports, and other data that is currently being managed on paper using paper forms.

## Live Demo

[Login](https://jeremydev.knack.com/parenting-now#groups2/)
email: `test@test.com`
password: `test`

## Where's the Code?

There isn't any! While my original project idea was going to use Knack just as a data provider and talk to it over via API, I decided to challenge myself to only use the visual application builder tools to create this solution. This was both a personal challenge and a way of ensuring that the solution, if handed off to the organization, could be continued to be maintained by people of differing technical abilities.

## Features

- Secure login with multiple user roles (educators, administrators)
- Group management dashboard for parenting educators
  - Add and update families (with associated parents, children, and roles for client and partner)
  - Manage sessions per group, including attendance tracking and snack assigments
  - Display session schedule in calendar format with more info per session
- All groups overview for administrators
- Migrate paper forms to online forms
  - Attendance reports by family and session
  - Summaries for sessions and groups
  - Snack assignments by session
- Export of email list in Access-friendly format (csv with columns matching example xls)
- Logo integration and custom colors to match existing web site

## A Note on Knack

Knack is a paid service, and while it aims to be an affordable platform (plans start at $39/mo with significant discounts for charitable organizations), not everyone has a technical budget. In the spirit of Hack for a Cause, Knack will provide a one-year non-profit starter plan subscription for this solution should it be selected.

## Screenshots

### Parenting Educator Dashboard

![Rendered page](https://i.imgur.com/5oUmRyy.png)

### Connections for Formatted Export

![Setting up connections for export](https://i.imgur.com/88lnGtB.gif)

### Page layout and hierarchy

![Page builder](https://i.imgur.com/KVPDrFH.png)
