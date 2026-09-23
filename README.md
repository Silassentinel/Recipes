# Recipe Documentation Standards

## Filename Standards
- Use Title-Case for all words (e.g., `Sweet-Potato-Soup.md`)
- Use hyphens (`-`) to separate words
- Don't use underscores or spaces
- Be descriptive but concise
- Follow English spelling

## Frontmatter Standards

### Required Fields
```yaml
---
layout: ../../layout/Post/MarkdownPostLayout.astro
title: 'Recipe Title'
pubDate: 'YYYY-MM-DD'
description: 'Brief description of the recipe'
author: 'Author Name'
image:
    url: 'image-url-if-available'
    alt: 'Image alternative text'
tags: ["Tag1", "Tag2", "Tag3"]
---
```

### Tag Guidelines
- Use double quotes for all tags
- Separate tags with commas and a space: `["Tag1", "Tag2"]`
- No trailing comma after the last tag
- Use American English spelling for consistency (`Yogurt`, not `Yoghurt`)
- Use Title Case: capitalize every word (`Olive Oil`, `Dry Rub`)
- Only letters, digits, spaces, hyphens and underscores — the site build
  rejects a recipe with any other character in a tag
- List descriptive tags first, then ingredient tags
- Categories to include:
  - Meal type / dish (Lunch, Snack, Soup, Salad, Sauce, Main Dish)
  - Cuisine, as an adjective (Belgian, American, Chinese, Italian — not `BE`, `USA`, `CN`)
  - Dietary (Vegan, Vegetarian, Healthy, etc.)
  - Cooking method (BBQ, Smoked, Grilled, Fried, etc.)
  - **Every ingredient** (see below)

### Ingredient Tags
Every ingredient gets a tag. The site's seasonal calendar
(`/seizoenskalender`) links its vegetables and fruit to these tags, so
consistent names are what make that linkage work.
- **Singular**: `Carrot`, `Mushroom`, `Egg`, `Tomato` (mass nouns and herbs
  that are naturally plural stay plural: `Chives`, `Nuts`, `Ribs`)
- **Base ingredient, not the variety**: cherry tomatoes / San Marzano →
  `Tomato`; red, yellow or silver onion → `Onion`; lemon basil → `Basil`;
  chili flakes / chili pepper → `Chili`; paprika powder → `Paprika`.
  Keep a separate tag only when it is genuinely a different vegetable:
  `Bell Pepper`, `Butternut Squash`, `Chinese Cabbage`, `Sweet Potato`,
  `Spring Onion`, `Shallot`
- **Sub-recipes by their recipe's tag**, so dishes link to them: `Chimichurri`,
  `Dry Rub`, `BBQ Sauce`, `Fish Broth`, `Lemon Sauce`, `Chinese Marinade`
- **Skip** salt, black pepper and water — they are in nearly every recipe

## Content Structure

### Recipe Format
```markdown
# Recipe Title

## Ingredients:
- Ingredient 1
- Ingredient 2
- Ingredient 3

## Instructions:
1. First step
2. Second step
3. Third step

## Notes (optional):
- Any additional notes or tips
```

### Content Guidelines
- Use bullet points for ingredients
- Use numbered steps for instructions
- Be specific with measurements and quantities
- Include cooking times and temperatures
- Add helpful notes or variations when applicable

## Example Recipe
```markdown
---
layout: ../../layout/Post/MarkdownPostLayout.astro
title: 'Garlic Roasted Potatoes'
pubDate: '2025-05-15'
description: 'Crispy garlic roasted potatoes with herbs'
author: 'Benjamin Degryse'
image:
    url: ''
    alt: 'Garlic roasted potatoes on a plate'
tags: ["Side", "Vegetarian", "Roasted", "Potato", "Garlic", "Olive Oil", "Rosemary", "Thyme"]
---

# Garlic Roasted Potatoes

## Ingredients:
- 2 lbs (900g) small potatoes, halved
- 4 garlic cloves, minced
- 3 tbsp olive oil
- 1 tbsp fresh rosemary, chopped
- 1 tbsp fresh thyme, chopped
- 1 tsp salt
- 1/2 tsp black pepper

## Instructions:
1. Preheat oven to 425°F (220°C).
2. In a large bowl, toss potatoes with olive oil, garlic, herbs, salt, and pepper.
3. Spread potatoes on a baking sheet in a single layer.
4. Roast for 25-30 minutes, turning halfway through, until golden and crispy.
5. Serve hot as a side dish.

## Notes:
- For extra crispiness, parboil the potatoes for 5 minutes before roasting.
- Can be made ahead and reheated in a hot oven for 10 minutes.
```
