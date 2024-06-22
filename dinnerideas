import random

# List of dinner ideas
dinner_ideas = [
    "Japanese Soba with Tempura",
    "Vegan Caesar Salad",
    "Grilled Salmon with Vegetables",
    "Beyond Meat Tacos",
    "Pizza and Tots",
    "Chicken Nuggets and Fries",
    "Goldfish Crackers",
    "Sushi",
    "Beef Noodle Soup",
    "Sweet and Sour Fish",
    "Grilled Cheese and Tomato Soup",
    "Shrimp Scampi",
    "Eggplant Parmesan",
    "Pho",
]
# Function to suggest a dinner idea
def suggest_dinner(ideas):
    return random.choice(ideas)

# Function to get see if kids will impact user's choice :P
def filter_kids(ideas):
    print("Do you have small kids? (yes/no)")
    kids = input().strip().lower()
    if kids == 'yes':
        # Create a list of child-friendly options
        kid_friendly_options = ["Pizza and Tots", "Chicken Nuggets and Fries", "Goldfish Crackers"]
        return kid_friendly_options
    else: 
        return ideas

# Remove child-friendly options from the main list
        non_kid_friendly = [idea for idea in ideas if idea not in child_friendly_options]
        return non_kid_friendly  

# Return the remaining options
# Main function
def main():
    print("Welcome to Dinner Suggestions")
    filtered_ideas = filter_kids(dinner_ideas)  # Use the new filter function
    suggestion = suggest_dinner(filtered_ideas)
    print(f"How about having '{suggestion}' for dinner tonight?")
if __name__ == "__main__":
    main()
