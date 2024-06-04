class PythonQuest:
    def __init__(self):
        self.level = 1
        self.run_game()

    def run_game(self):
        while self.level <= 5:
            if self.level == 1:
                self.level_one()
            elif self.level == 2:
                self.level_two()
            elif self.level == 3:
                self.level_three()
            elif self.level == 4:
                self.level_four()
            elif self.level == 5:
                self.level_five()
            self.level += 1
        print("Congratulations! You've completed the Python Quest!")

    def level_one(self):
        print("Level 1: Introduction to Variables and Data Types")
        ingredient1 = "unicorn hair"
        ingredient2 = "dragon scale"
        potion = ingredient1 + " and " + ingredient2
        print("Potion contains:", potion)
        input("Press Enter to continue...")

    def level_two(self):
        print("Level 2: Conditional Statements")
        key_color = "red"
        if key_color == "red":
            print("The door opens!")
        else:
            print("The key doesn't fit.")
        input("Press Enter to continue...")

    def level_three(self):
        print("Level 3: Loops")
        stones = ["stone1", "stone2", "stone3"]
        for stone in stones:
            print(stone, "is now glowing!")
        input("Press Enter to continue...")

    def level_four(self):
        print("Level 4: Functions")
        def cast_spell(spell_name):
            print("Casting", spell_name)
        cast_spell("Invisibility")
        input("Press Enter to continue...")

    def level_five(self):
        print("Level 5: Basic Data Structures")
        artifacts = {
            "wand": "
