---
title: "Calendario"
date: 2023-04-05T00:16:04+02:00
---

- [Repository GitHub](https://github.com/cartabinaria/unibocalendar)
- [Sito web](https://calendar.students.cs.unibo.it/)

## Descrizione

L'applicazione consente di ottenere in formato ical gli orari delle lezioni di
un corso di laurea dell'Università di Bologna. L'utente può scegliere tra i
corsi di laurea disponibili e scegliere quali lezioni aggiungere al proprio
calendario.

Il progetto non nasce in seno a CartaBinaria: è una riscrittura in Go di un
[progetto di Francesco Bonzi](https://github.com/FrancescoBonzi/UniboCalendar).

## Utilizzo

1. Accedere al sito web [https://calendar.students.cs.unibo.it/](https://calendar.students.cs.unibo.it/)
2. Selezionare il corso di laurea di interesse
3. Se solo alcuni insegnamenti sono rilevanti, usare `Filter`
4. Scegli:
   1. Per aggiungere il calendario a un'applicazione generica, cliccare su `Copy`
      e poi incollare il link nella propria applicazione
   2. Per visualizzare il calendario dal proprio browser, cliccare su `Apri
      online`
   3. Per applicazioni di calendario specifiche, cliccare sui relativi pulsanti

{{% callout note %}}
Se i propri browser e dispositivo sono configurati per aprire con una certa
applicazione di calendario gli indirizzi con lo schema `webcal://`, il pulsante
`Apple Calendar` funzionerà con tale applicazione.
{{% /callout %}}
