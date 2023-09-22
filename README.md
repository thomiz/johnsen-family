Prøve andre plugins?
* https://github.com/quantorconsulting/mkdocs_build_plantuml
* Direkte integrasjon i markdown
  * [stackoverflow](https://stackoverflow.com/questions/32203610/how-to-integrate-uml-diagrams-into-gitlab-or-github)

## Test

## Johnsen trunk tree

```puml
@startmindmap
* Margrethe Johnsen og Johannes Johnsen
** Randi Wiese
** Ågot Gjersøe
** Marga Schøyen
** Sigrid Fischer
** Birgit Hatlehol
** Bjarne Johnsen
@endmindmap
```

The Johnsen trunk tree.

![Johnsen trunk tree](http://www.plantuml.com/plantuml/svg/FSuz3i8m30NWFQVmd5DK382GMEZ0R3LMugfraEs50t2dxhaOIldPx4-otnlCKNrbIIi-GeGhQbRoGd2fHOm4QkuZYf3zBCG8DvJ4S6SowcjxvUfmcacjRLtsJmZZLDhs_9oCd9KJ7DccGjhbm9hPuOo-KAdBJZEg_DF3G9A-xTu0)

## direct integration test

### Mindmap Wiese
![Wiese grenen](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/thomiz/johnsen-family/master/input/images-source/wiese-grenen-mind.puml)

### class diagram Wiese

![Wiese grenen](http://www.plantuml.com/plantuml/svg/1S7B4G8n203GkrLe0LdkTeCH4nmW6JwpezNlUm-sBlMcShdFp1rFWC4vwtNqfP1pAV_XkwO5MVkWilp0yGJ5I79WsvN0YeEYnIhl12TJK1jEHdPiGSjIkLq0)

Proxy må ta utgangspunkt i en enkel plantuml med include av kildekoden til diagrammet du vil vise 
'''puml
!include https://raw.githubusercontent.com/thomiz/johnsen-family/master/input/images-source/wiese-grenen-mind.puml
'''

#### Source

https://github.com/thomiz/johnsen-family/blob/master/input/images-source/wiese-grenen.plantuml

