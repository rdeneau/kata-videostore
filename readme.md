# Clean Code - Kata Video Store en C# et TypeScript

Code associé à la _(future)_ série d’articles sur le blog de Soat :

- [Partie 1](http://blog.soat.fr/2018/04/cleancode-videostore-cs-ts-part1/)
- [Partie 2](http://blog.soat.fr/2018/04/cleancode-videostore-cs-ts-part2/)
- [Partie 3](http://blog.soat.fr/2018/04/cleancode-videostore-cs-ts-part3/)

## Objectif des articles

Parler de clean code :

- à partir du fameux kata VideoStore de Martin Fowler repris par Robert "Oncle Bob" Martin en particulier dans sa vidéo [Clean Code #3 - Functions](https://cleancoders.com/episode/clean-code-episode-3/show).
- en C# et surtout en TypeScript

## Organisation du code

- `Soat.CleanCoders.VideoStore.sln` : solution Visual Studio générale
- `1_Original/` : version originale
- `2_Uncle_Bob/` : version d’oncle Bob
- `3_Outside_In/` : version refaite en TDD outside-in

Les versions sont structurées de la même façon :

- `Soat.CleanCode.VideoStore.Xxx/` : contient le projet C# du code de production
- `Soat.CleanCode.VideoStore.Xxx.Tests/` : contient le projet C# des tests
- `Soat.CleanCode.VideoStore.Xxx.Typescript/` : contient le code en TypeScript

Les versions C# et TypeScript divergent légèrement dans l’optique de trouver le design le plus élégant en fonction du langage.

Les versions 1 et 2 sources en Java peuvent être consultées sur le [GitHub d’Uncle Bob](https://github.com/unclebob/videostore).

## Installation

- Pour le C#, il suffit de lancer le `.sln` et de builder. Les packages NuGet seront alors récupérés.
- Pour le code TypeScript, l’installation se résume à celle des packages npm : la commande `yarn` (ou son équivalent `npm init`) fait l’affaire. Elle est à lancer pour chaque dossier `*.TypeScript`.
