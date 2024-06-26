# Teriyaki

My nephew posted a story with a delicious teriyaki.
He sent me a recipe from a cookbook by Williene Klinck.
I simplified it a lot, and here it is!

![The finished dish](/assets/img/teriyaki_dish.jpg)

## Ingredients

As always, the ingredients are for 1 person so you can multiply them easily!

- 130g beef chunks
- 100g mushrooms
- Some spring onions
- 100g snow peas
- Half an onion
- 100g rice

Spices and stuff:

- 2 tablespoons of soy sauce
- A splash of honey
- Ginger
- Paprika powder
- (Yellow) curry powder
- Garlic

Other stuff:

- A plate or bowl for the marinated beef

## How to make

1. Mix 1 tablespoon of soy sauce with a splash of honey.
2. Add some ginger and paprika powder and a little bit of curry powder.
3. Mix the beef chunks with the sauce and let it marinate for a while.
4. Cook the rice and let it sit.
5. In the meantime, cut the onion, spring onions and mushrooms.
6. After half an hour, fry the beef chunks in a pan.
7. Quickly add the onion, spring onions, snow peas and mushrooms.
8. Add the other tablespoon of soy sauce along with some garlic.
9. Add some water to make a sauce.
10. Serve with the rice.

```nomnoml
[🔪 onion,;spring onions,;mushrooms] ->
[<class id=fry> 🍳 onion,;spring onions,;snow peas,;mushrooms] ->
[🥣 tbsp. soy sauce,;garlic] ->
[🥣 water;to make a sauce] ->
[<class id=combine> 🍽️ with the rice]

[🥘 rice] ->
[combine]

[🥣 tbsp. of soy sauce,;splash of honey] ->
[🥣 some ginger,;paprika powder,;littlebit of  curry powder] ->
[🥣 beef chunks,;sauce] ->
[🥩 let marinate] ->
[🍳 beef chunks] ->
[fry]
```
