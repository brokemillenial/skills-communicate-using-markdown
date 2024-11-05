# Activity 2
## It was 10 in the Morning
##### when he started writing, food was on the stove
### 05-11-2024 
#### he did this activiy commited the changes 
#### and food got cooked. 

![Image of Palak Daal](https://www.indianhealthyrecipes.com/wp-content/uploads/2021/09/dal-palak-spinach-dal.webp)

''' 
# Define a class PalakDaalRecipe:
    def __init__(self):
        # Ingredients
        self.ingredients = {
            "spinach": 2,           # cups
            "daal": 1,              # cup
            "water": 3,             # cups
            "turmeric_powder": 0.5, # teaspoon
            "salt": 1,              # teaspoon or to taste
            "oil": 2,               # tablespoons
            "mustard_seeds": 0.5,   # teaspoon
            "cumin_seeds": 0.5,     # teaspoon
            "garlic": 3,            # cloves
            "ginger": 1,            # inch
            "green_chili": 1,       # optional
            "onion": 1,             # medium
            "tomato": 1,            # medium
            "red_chili_powder": 0.5, # teaspoon
            "coriander_powder": 0.5, # teaspoon
            "lemon_juice": 1,       # tablespoon
            "fresh_cilantro": 2     # tablespoons
        }
      self.steps = []  # This will store each cooking step
    
    def add_step(self, step):
        self.steps.append(step)
    
    def prepare_ingredients(self):
        self.add_step("Rinse the daal thoroughly.")
        self.add_step("Chop the spinach, onion, garlic, ginger, green chili, and tomato.")
    
    def cook_daal(self):
        self.add_step("In a pot, combine daal, water, and turmeric powder.")
        self.add_step("Bring to a boil, then simmer for 20-25 minutes until the daal is soft and mushy.")

   
    def add_spinach(self):
        self.add_step("Add the chopped spinach to the pot.")
        self.add_step("Cook for another 5-7 minutes until the spinach wilts and blends well with the daal.")
  
    def make_tadka(self):
        self.add_step("In a small pan, heat oil over medium heat.")
        self.add_step("Add mustard seeds and cumin seeds and let them splutter.")
        
        # Loop to handle multiple ingredients being added to the tadka
        tadka_ingredients = ["garlic", "ginger", "green_chili", "onion", "tomato"]
        for item in tadka_ingredients:
            self.add_step(f"Add {item} and cook until soft and fragrant.")
        
        self.add_step("Add red chili powder and coriander powder to the tadka.")
    
    def combine_daal_and_tadka(self):
        self.add_step("Pour the tadka into the cooked daal and spinach mixture.")
        self.add_step("Add salt to taste and mix well.")
        self.add_step("Simmer for a few more minutes to let the flavors combine.")
    
    def finish_dish(self):
        self.add_step("Turn off the heat and add lemon juice.")
        self.add_step("Garnish with fresh cilantro.")
    
    def cook(self):
        # Method to go through each step
        for index, step in enumerate(self.steps, 1):
            print(f"Step {index}: {step}")
    
# Instantiate and cook
palak_daal = PalakDaalRecipe()
palak_daal.prepare_ingredients()
palak_daal.cook_daal()
palak_daal.add_spinach()
palak_daal.make_tadka()
palak_daal.combine_daal_and_tadka()
palak_daal.finish_dish()

# Print the recipe steps
palak_daal.cook()

'''
