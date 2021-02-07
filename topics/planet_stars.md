---
layout: template_generalFiles
title: Planets and stars
---

# {{page.title}}

The word planet owes its origin to the Greek word planētēs, which means wanderer. Planets wander all over space, as opposed to stars, which do not seem to do so. Stars emit starlight; planets bask in the glory of their stars.

Earth is a planet, which wanders around its star, which is called Sun. A star, oftentimes, has several planets that keep circling it. Sun has nine or ten or eleven such planets, all spaced out in space, all spinning like a top and, simultaneously, circling Sun.

One can hop from planet to planet. All it takes is a rocket and a space suit, and plenty of time. The reason why you need to hop planets is that all planets are ephemeral.

> 
> "But what does that mean - ephemeral?" repeated the little prince, who never in his life had let go of a question, once he had asked it.
>
> "It means that which is in danger of speedy disappearance."
>
> "Is my planet in danger of speedy disappearance?"
>
> "Certainly it is."

## Distances

The distance between any two objects in space can be calculated by the following formula:

```python
with open('static/vs.json', encoding='utf-8') as f:
  vs = json.load(f)

@app.route('/', methods=['GET'])
def home():
    return render_template('vs.html')

```

## Satellites

Satellites are objects that circle planets (or land on them). For example, these are satellites (a check mark indicates a successful mission)

- [x] Aryabhat 1975
- [x] Bhaskara I 1979
- [x] Bhaskara II 1981
- [x] Chandrayan I 2009
- [ ] Chandrayan II 2019


## See also

-  [Time and distance](time_distance.md)
-  [Travelling on a rocket](rockets_travelling.md)

