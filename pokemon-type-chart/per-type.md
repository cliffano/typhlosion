# Pokémon Type Chart / Per Type

## Bug

```mermaid
  graph TD;
      FIRE-->BUG;
      FLYING-->BUG;
      ROCK-->BUG;
      BUG-->GRASS;
      BUG-->PSYCHIC;
      BUG-->DARK;
```
## Dark

```mermaid
  graph TD;
      FIGHT-->DARK;
      BUG-->DARK;
      FAIRY-->DARK;
      DARK-->PSYCHIC;
      DARK-->GHOST;
```
## Dragon

```mermaid
  graph TD;
      ICE-->DRAGON;
      DRAGON-->DRAGON;
      FAIRY-->DRAGON;
      DRAGON-->DRAGON;
```
## Electric

```mermaid
  graph TD;
      GROUND-->ELECTRIC;
      ELECTRIC-->WATER;
      ELECTRIC-->FLYING;
```
## Fairy

```mermaid
  graph TD;
      POISON-->FAIRY;
      STEEL-->FAIRY;
      FAIRY-->FIGHT;
      FAIRY-->DRAGON;
      FAIRY-->DARK;
```
## Fight

```mermaid
  graph TD;
      FLYING-->FIGHT;
      PSYCHIC-->FIGHT;
      FAIRY-->FIGHT;
      FIGHT-->NORMAL;
      FIGHT-->ICE;
      FIGHT-->ROCK;
      FIGHT-->DARK;
      FIGHT-->STEEL;
```
## Fire

```mermaid
  graph TD;
      WATER-->FIRE;
      GROUND-->FIRE;
      ROCK-->FIRE;
      FIRE-->GRASS;
      FIRE-->ICE;
      FIRE-->BUG;
      FIRE-->STEEL;
```
## Flying

```mermaid
  graph TD;
      ELECTRIC-->FLYING;
      ICE-->FLYING;
      ROCK-->FLYING;
      FLYING-->GRASS;
      FLYING-->FIGHT;
      FLYING-->BUG;
```
## Ghost

```mermaid
  graph TD;
      GHOST-->GHOST;
      DARK-->GHOST;
      GHOST-->PSYCHIC;
      GHOST-->GHOST;
```
## Grass

```mermaid
  graph TD;
      FIRE-->GRASS;
      ICE-->GRASS;
      POISON-->GRASS;
      FLYING-->GRASS;
      BUG-->GRASS;
      GRASS-->WATER;
      GRASS-->GROUND;
      GRASS-->ROCK;
```
## Ground

```mermaid
  graph TD;
      WATER-->GROUND;
      GRASS-->GROUND;
      ICE-->GROUND;
      GROUND-->FIRE;
      GROUND-->ELECTRIC;
      GROUND-->POISON;
      GROUND-->ROCK;
      GROUND-->STEEL;
```
## Ice

```mermaid
  graph TD;
      FIRE-->ICE;
      FIGHT-->ICE;
      ROCK-->ICE;
      STEEL-->ICE;
      ICE-->GRASS;
      ICE-->GROUND;
      ICE-->FLYING;
      ICE-->DRAGON;
```
## Normal

```mermaid
  graph TD;
      FIGHT-->NORMAL;
```
## Poison

```mermaid
  graph TD;
      GROUND-->POISON;
      PSYCHIC-->POISON;
      POISON-->GRASS;
      POISON-->FAIRY;
```
## Psychic

```mermaid
  graph TD;
      BUG-->PSYCHIC;
      GHOST-->PSYCHIC;
      DARK-->PSYCHIC;
      PSYCHIC-->FIGHT;
      PSYCHIC-->POISON;
```
## Rock

```mermaid
  graph TD;
      WATER-->ROCK;
      GRASS-->ROCK;
      FIGHT-->ROCK;
      GROUND-->ROCK;
      STEEL-->ROCK;
      ROCK-->FIRE;
      ROCK-->ICE;
      ROCK-->FLYING;
      ROCK-->BUG;
```
## Steel

```mermaid
  graph TD;
      FIRE-->STEEL;
      FIGHT-->STEEL;
      GROUND-->STEEL;
      STEEL-->ICE;
      STEEL-->ROCK;
      STEEL-->FAIRY;
```
## Water

```mermaid
  graph TD;
      ELECTRIC-->WATER;
      GRASS-->WATER;
      WATER-->FIRE;
      WATER-->GROUND;
      WATER-->ROCK;
```
