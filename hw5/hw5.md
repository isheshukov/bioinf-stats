---
title: "R Notebook"
output: html_notebook
---

Задание 5 (на 27.04)

Прочитать и осознать Главу 12

Выполнить задания (рассказать суть задачи, рассказать подход, показать результаты): 11E3, 11E4

* 11E3. When count data are zero-inflated, using a model that ignores zero-inflation will tend to in-
duce which kind of inferential error?


* 11E4. Over-dispersion is common in count data. Give an example of a natural process that might
produce over-dispersed counts. Can you also give an example of a process that might produce under-
dispersed counts?

* 11H6. The data in data(Fish) are records of visits to a national park. See ?Fish for details. The
question of interest is how many fish an average visitor takes per hour, when fishing. The problem is
that not everyone tried to fish, so the fish_caught numbers are zero-inflated. As with the monks
example in the chapter, there is a process that determines who is fishing (working) and another pro-
cess that determines fish per hour (manuscripts per day), conditional on fishing (working). We want
to model both. Otherwise we’ll end up with an underestimate of rate of fish extraction from the park.
You will model these data using zero-inflated Poisson GLMs. Predict fish_caught as a function
of any of the other variables you think are relevant. One thing you must do, however, is use a proper
Poisson offset/exposure in the Poisson portion of the zero-inflated model. Then use the hours vari-
able to construct the offset. This will adjust the model for the differing amount of time individuals
spent in the park.

```{r}

```