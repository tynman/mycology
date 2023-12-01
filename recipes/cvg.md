# CVG
Coir, Vermiculite, Gypsum

## Ingredients, by weight

- 2 parts coir
- 1 part vermiculite
- 1 part gypsum
- 10 parts water

## Instructions

1. Break up coir brick into small pieces and place in a large bucket.
2. Add vermiculite and gypsum.
3. Heat water to 180°F (82°C) and pour over dry ingredients.
4. Mix well and let sit at least 6 hours.

## Steps

- This recipe is based on the [CVG Tek](https://www.shroomery.org/forums/showflat.php/Number/11916595) from the Shroomery.

```mermaid
gantt
    dateFormat  MM-DD
    title   CVG Tek

    section Start
    Collect ingredients :active start, 01-01, 10m

    section Prep
    Heat water to 180°F (82°C) : wet, after start, 30m
    Add coir, vermiculite, and gypsum to bucket : dry, after start, 10m

    section Sterilize
    Pour water over dry ingredients : mix1, after dry wet, 2m
    Mix well : mix2, after mix1, 5m
    Let sit at least 6 hours : mix3, after mix2, 6h
```



```mermaid
graph TD
    bucket((5 gallon bucket))
    dry[Add coir, vermiculite, and gypsum to bucket] --> bucket
    pot((Large Pot))
    water(water) --> pot
    pot --> heat[Heat water to 180°F]
    heat --> bucket
    bucket --> mix[Let sit at least 6 hours]
    mix --> done[Done]
```