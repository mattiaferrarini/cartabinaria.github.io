---
title: "Adding a New Course"
date: 2023-06-06T00:49:44+02:00
---

Adding a new course is easy if you are already within the [CartaBinaria organization on GitHub](https://github.com/cartabinaria):

1. On [template-it](https://github.com/cartabinaria/template-it)/[template-en](https://github.com/cartabinaria/template-en), use "Use this template"/"Create a new repository";
2. As the new name, use `the-kebab-case-convention`, `ing-` as a possible prefix for Computer Engineering, `isi-` as a possible prefix for Computer Science and Engineering, or `ipim-` as a possible prefix for Information Science for Management (no prefixes are needed to distinguish between bachelor's and master's courses);
3. As the description, use a phrase similar to "A collection of resources for the Programming Languages course (04138) of the Bachelor's Degree in Computer Science";
4. Choose "Public" and proceed to "Create repository from template";
5. Enable GitHub Pages from "Settings" / "Pages" setting "Source" to "GitHub Actions";
6. Grant "Maintain" rights to the relevant groups. For example, for a second-year Computer Engineering course, the Computer Engineering second and third-year groups should be added. It is not necessary to remove oneself from the Admin role;
7. On the main page of the new course on GitHub, click on the gear next to "About";
8. As "Website", use `https://dynamik.vercel.app/repository-name`, and uncheck "Releases" and "Packages", then add "Topics" as desired and click "Save changes";
9. Update the README filling in every placeholder;
10. Add any extensions you want to appear on the resulting website by modifying `.github/workflows/build-and-deploy.yml`;
11. Add the new course to [`degrees.json`](https://github.com/cartabinaria/config/blob/main/degrees.json) and [`teachings.json`](https://github.com/cartabinaria/config/blob/main/teachings.json) in the `cartabinaria/config` repository.

That's it! If you want the course to also appear in the lists of [Dynamik](https://github.com/cartabinaria/dynamik), [Informabot](https://github.com/cartabinaria/informabot), or other services, simply update the git submodule of `cartabinaria/config` in the respective repositories.
