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
- Use American English spelling for consistency
- Capitalize the first letter of each tag
- Categories to consider including:
  - Meal type (Breakfast, Lunch, Dinner, Snack)
  - Cuisine (Italian, Mexican, Japanese, etc.)
  - Dietary (Vegan, Vegetarian, Gluten-Free, etc.)
  - Main ingredient (Chicken, Beef, Tofu, etc.)
  - Cooking method (BBQ, Roasted, Slow-Cooker, etc.)

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
tags: ["Potato", "Side", "Vegetarian", "Roasted", "Garlic"]
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
