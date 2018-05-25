---
lang:   FR
title:  Méthodes à la chaîne
answer: ^J'avais encore plus (.+)
load:   prev
ok:     Bravo, l'ami ! La méthode join a pris l'array de lignes et les as assemblé en un string.
error:
---

Alors qu'est-ce que tu vois ? Qu'est-ce qu'il s'est passé ?
Tu as tappé __poem.lines.reverse__ et que ce que ça a donné ?

Il s'est passé deux choses. Tu as transformé le poème en une liste
en utilisant lines.
La méthode lines decide la façon dont le string est découpé et le convertit en
un Array.

Ensuite, tu as inversé cette liste. Tu avais chaque ligne. Tu les as inversées.
C'est tout.

Ajoutons une dernière méthode au bout ici :

    puts poem.lines.reverse.join

Combiner plusieurs méthodes comme ça est appellé un _chaînage de méthodes_.
