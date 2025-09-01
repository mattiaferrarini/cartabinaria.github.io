---
title: "Aggiungere un nuovo insegnamento"
date: 2023-06-06T00:49:44+02:00
---

Aggiungere un nuovo insegnamento è facile, se ti trovi già all'interno
dell'organizzazione [CartaBinaria su GitHub](https://github.com/cartabinaria):

1. su [template-it](https://github.com/cartabinaria/template-it)/[template-en](https://github.com/cartabinaria/template-en),
   usa "Use this template"/"Create a new repository";
2. come nuovo nome, usa `la-convenzione-kebab-case`, `ing-` come eventuale
   prefisso per Ingegneria informatica, `isi-` come eventuale prefisso per
   Ingegneria e scienze informatiche, `ipim-` come eventuale prefisso per Informatica per il management, `dhdk-` come eventuale prefisso per Digital Humanities and Digital Knowledge, (non servono prefissi per distinguere
   triennali da magistrali);
3. come descrizione, usa una frase simile a "Una raccolta di risorse per
   l'insegnamento di Linguaggi di programmazione (04138) del Corso di Laurea in
   Informatica";
4. scegli "Public" e vai su "Create repository from template";
5. abilita GitHub Pages da "Settings" / "Pages" impostando "Source" come
   "GitHub Actions";
6. concedi i diritti "Mantain" ai gruppi interessati. Per esempio, per un
    insegnamento di Ingegneria informatica del secondo anno, andrebbero aggiunti
    i gruppo di Ingegneria informatica del secondo e terzo anno.
    Non è necessario rimuovere sé stessi dal ruolo di Admin;
7. nella pagina principale del nuovo insegnamento su GitHub, clicca
   sull'ingranaggio a fianco di "About";
8. come "Website", usa `https://dynamik.vercel.app/nome-repository`,
   e togli le spunte da "Releases" e "Packages", poi aggiungi "Topics" a piacere
   e clicca su "Save changes";
9. aggiorna il README riempiendo ogni segnaposto;
10. aggiungi eventuali estensioni che vuoi compaiano sul sito risultante
   modificando `.github/workflows/build-and-deploy.yml`;
11. aggiungi il nuovo insegnamento a
    [`degrees.json`](https://github.com/cartabinaria/config/blob/main/degrees.json)
    e
    [`teachings.json`](https://github.com/cartabinaria/config/blob/main/teachings.json)
    della _repository_ `cartabinaria/config`.

Ecco fatto! Se vuoi che l'insegnamento compaia anche negli elenchi di
[Dynamik](https://github.com/cartabinaria/dynamik),
[Informabot](https://github.com/cartabinaria/informabot) o di altri servizi, basta
aggiornare il sottomodulo git di `cartabinaria/config` nelle rispettive
_repository_.
