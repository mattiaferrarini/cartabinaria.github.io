---
title: "Calendar"
date: 2023-04-05T00:16:04+02:00
---

- [GitHub Repository](https://github.com/cartabinaria/UniboCalendar)
- [Website](https://calendar.students.cs.unibo.it/)

## Description

The application allows obtaining the class schedules of a degree course at the
University of Bologna in ical format. Users can choose from available degree
courses and select which classes to add to their calendar.

The project did not originate within CartaBinaria: it is a Go rewrite of a
[project by Francesco Bonzi](https://github.com/FrancescoBonzi/UniboCalendar).

## Usage

1. Go to the website [https://calendar.students.cs.unibo.it/](https://calendar.students.cs.unibo.it/)
2. Select the desired degree course
3. If you only care about some courses, you may use `Filter`
4. Choose one:
   1. To add the calendar to a generic application, click on `Copy` and the
      paste in your app
   2. To view the calendar online, click `Apri online`
   3. To add the calendar to specific applications, you can use the appropriate
      buttons

{{% callout note %}}
If your device is such that the `webcal://` schema will be managed by a certain
application, the `Apple Calendar` button will use such app.
{{% /callout %}}
