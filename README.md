# Scripts

_To change stuff in [Scrap Mechanic](https://store.steampowered.com/app/387990/Scrap_Mechanic/)_

One day I might make a full blown mod out of these (once I figure out how to do this correctly. Right now I'm just collecting scripts so I can reapply them if and when the game scripts change.

**Content:**

- [Gasohol](#gasohol)
    - [Gasohol Tier 2](#gasohol-tier-2)
    - [Potato Gasohol](#potato-gasohol)

<hr/>

# Gasohol

Based on [this mod](https://www.reddit.com/r/ScrapMechanic/comments/gj4b3g/mod_simple_quality_of_life_edit/) I added two more gasohol variants so all seeds are useful. (I'm clearly not at the point yet where I have last tier seeds.)

## Gasohol Tier 2

<img align="left" src="readme/gasohol_2.png" />

**Apply to:** _Survival/CraftingRecipes/craftbot.json_

**Changes:** Adds recipe to craft gasoline from tier 2 seeds.

**Script:**

```lua
	{	// Gasohol Tier 2
		"itemId": "d4d68946-aa03-4b8f-b1af-96b81ad4e305",
		"quantity": 5,
		"craftTime": 14,
		"ingredientList": [
			{	// Banana Seed
				"quantity": 1,
				"itemId": "22beade5-38ca-47b4-a2ee-32403f58a862"
			},
			{	// Blueberry Seed
				"quantity": 1,
				"itemId": "4b6d2bee-d0f1-4e56-96f0-d2596388cad2"
			},
			{	// Orange Seed
				"quantity": 1,
				"itemId": "bee966b0-b5e5-41da-b992-5d363ab85ae4"
			},
			{	// Gas
				"quantity": 1,
				"itemId": "d4d68946-aa03-4b8f-b1af-96b81ad4e305"
			}
		]
	},
``` 


## Potato Gasohol

<img align="left" src="readme/gasohol_potato.png" />

**Apply to:** _Survival/CraftingRecipes/craftbot.json_

**Changes:** Adds recipe to craft gasoline from potato seeds.

**Script:**

```lua
	{	// Potato Gasohol
		"itemId": "d4d68946-aa03-4b8f-b1af-96b81ad4e305",
		"quantity": 5,
		"craftTime": 14,
		"ingredientList": [
			{	// Potato Seed
				"quantity": 3,
				"itemId": "eb1ef696-5c05-4662-9e47-fe1e0875ff84"
			},
			{	// Gas
				"quantity": 1,
				"itemId": "d4d68946-aa03-4b8f-b1af-96b81ad4e305"
			}
		]
	},
``` 

**Note:** To be more fair, I'm thinking about changing the quantity of potato seeds needed to 5. Maybe you want to do this, too. :)
