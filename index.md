# Activity 2
## It was 10 in the Morning
##### when he started writing, food was on the stove
### 05-11-2024 
#### by the time he did this activiy commited the changes 
#### the food got cooked. 

![Image of Palak Daal](https://www.indianhealthyrecipes.com/wp-content/uploads/2021/09/dal-palak-spinach-dal.webp)

''' 

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
'''
