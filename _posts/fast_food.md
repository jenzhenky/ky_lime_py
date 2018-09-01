---
title: Fast Food Showdown
---

I try to not indulge too often, but I love fast food. I love the convenience, the consistency, and I even find the promotional gimmicks charming. McDonald's is my favorite chain and I'd argue they've really turned things around in the last few years with a revamp in quality and image. I would even dare say that the quality of some of their items rivals fast casual chains that are considered a tier above - have you tried their fresh beef quarter pounders? 

It got me thinking: how do the fast food chains actually compare with each other? It's a broad question so I've decided to dedicate this post to nutrition. Now, I'm not advocating for fast food as a staple of a balanced diet, but I think we all partake on occasion and if we're indulging we might as well make educated decisions.

### Judge by Nutrition

To balance out my Python journey I've also started getting more active and lifting weights (small weights, but still weights). With protein on my mind, I decided to bring some of that gym rat wisdom to my fast food project. I set nutritional goals for this analysis based on four different calorie per day scenarios: 1,500, 2,000, 2,500, and 3,000. I referred to the government's [*Dietary Guidelines for Americans*](https://health.gov/dietaryguidelines/2015/guidelines/appendix-7/) recommendations for daily macronutrient intake to set daily nutritional goals for each scenario. My analysis assumes that this meal will represent 40% of each daily goal and I examine various types of meal for each calorie scenario: entrée only; entrée and side; and entrée, side, and desert.

Note: Though protein receives a lot of attention from bodybuilders and dieters alike, I did not include protein in these goals as protein intake is more dependent on body weight than caloric intake. As a rough rule of thumb, 0.4 grams of protein for pound of body weight for sedentary adults and 1 gram per pound for active adults.

|Scenario | Calories | Carbs, g | Sugar, g| Fat, g | Example
|--|--|--|--|--|--|
| 0 | 1,500 | 225 | 19 | 50 | Female cutting weight |
| 1 | 2,000 | 300 | 25 | 67 | Average female; male cutting weight |
| 2 | 2,500 | 375 | 31 | 83 | Active or bulking female; average male |
| 3 | 3,000 | 450 | 38 | 100 | Active or bulking male |

### The Contestants & Process

For this showdown, I picked four of the largest fast food chains in the country: : McDonald's, Wendy's, Burger King, and Taco Bell. I scraped nutritional data through [Nutritionix's](https://www.nutritionix.com/) API, which also included some regional or seasonal items and did not always include newly released items, but I decided to leave the data as is because all the core menu items were covered.

To perform a meal-based nutritional analysis, I had to figure out how to create meal combinations for each chain, so I categorized each item by keywords in the item name as: entrée, side, drink, and dessert. Next, I created every combination of each meal type for each chain: entrée only; entrée and side; and entrée, side, and desert. I narrowed down these combinations with nutritional goals for each calorie scenario.

### Which chain offers the most nutritious items?

See the radial charts below. [analysis of charts)

[radial charts of average items]

### Which chain has the most options?

And the winner is: McDonald's! In the majority of calorie scenarios and meal types, McDonald's had the most meal options. [more commentary, perhaps a graphic?]

Interestingly, Taco Bell tended to have the most meal options in lower calorie scenarios. However, there is a caveat for Taco Bell: many of their entrée options are smaller-portioned and people tend to order multiple in a sitting. This is great for flexibility in constructing a meal, but can be it can be dangerously easy to overdo it. 

| Meal Type              | Brand Name  | Scenario 0 | Scenario 1 | Scenario 2 | Scenario 3 |
|------------------------|-------------|------------|------------|------------|------------|
| Entrée Only            | Burger King | 18         | 29         | 36         | 40         |
|                        | McDonald's  | 41         | 78         | 121        | 143        |
|                        | Taco Bell   | 65         | 75         | 91         | 97         |
|                        | Wendy's     | 22         | 31         | 40         | 42         |
| Entrée & Side          | Burger King | 11         | 57         | 193        | 352        |
|                        | McDonald's  | 130        | 416        | 1025       | 1693       |
|                        | Taco Bell   | 457        | 904        | 1215       | 1468       |
|                        | Wendy's     | 70         | 147        | 285        | 395        |
| Entrée, Side & Dessert | Burger King | 3          | 24         | 100        | 335        |
|                        | McDonald's  | 117        | 622        | 2325       | 6347       |
|                        | Taco Bell   | 0          | 0          | 346        | 1411       |
|                        | Wendy's     | 0          | 0          | 0          | 11         |

### The Verdict: McDonald's!
As expected, McDonald's won out on [individual nutritious items] and quantity of meal options. As part of the company's turnaround, McDonald's has been targeting a younger, healthier customer group and the data shows it hasn't just been a marketing effort - they truly do have more nutritious options.

[![Nutritionix API](nutritionix_api_image.png)](http://www.nutritionix.com/api)