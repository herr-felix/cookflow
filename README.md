# Cook Flow, a declarative language to generate recipes flowcharts


## Example: Adapdation of https://www.eatingbirdfood.com/vegan-power-bowl

```
Veggies:
	Preheat oven to 400F.
	
	Peel and chop 1lb of sweet potato.
	
	Chop 3oz of curly kale.

	Dice 1/4 cup of red onion.

	Spread on a baking sheet:
	- the sweet potatoes.
	- the red onion.
	- 1 tbsp of olive oil.
	- 1/2 tsp of salt.
	- 1/4 tsp of pepper.
	- 1/4 tsp of ground cumin.

	Roast for 10 minutes.

	Flip.

	Add on the baking sheet:
	- the curly kale.
	- 2 tsp of olive oil
	- a pinch of salt

	Roast for 10 minutes.

Seasoned_chickpeas:
	Mix in a bowl:
	- 3/4 cup of chickpeas
	- 1/2 tsp of chili powder
	- 1/4 tsp of salt
	- a pinch of pepper

Cooked_chickpeas: Seasoned_chickpeas
	Preheat a skillet to medium

	Add in hot skillet:
	- 1 tbsp of olive oil.

	Wait for the oil to simmer

	Add in hot skillet:
	- Seasoned_chickpeas

Dressing:
	Add in a blender:
	- 3/4 cup of cannellini beans
	- 2 tbsp of warm water
	- 1 tbsp of apple cider vinegar
	- 1 tbsp of olive oil
	- 1/2 tsp of salt
	- 1/4 tsp of pepper
	- a pinch of ground cumin (if desired)

	Blend until smooth and creamy

	(Add more water if necessary for a thinner dressing.)

Serve: Dressing, Cooked_chickpeas, Veggies
	Put in plates:
	- Veggies
	- Cooked_chickpeas
	- Dressing (or on the side)	
```
