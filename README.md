# adj_name_game
# generate a brand name using and adjective and first name.
print("Welcome to Brand Name Generator!😁")

# Ask the user for their first name and an adjective.
name=input('What is your first name?\n')
adj=input("Which adjective best describe you?\n")

# check that adjective and first name starts with the same letters.ps. all letter casing  is important
word1 = list(name)
#[x.lower() for x in (word1)]
word2 = list(adj)
#[x.lower() for x in (word2)]
if word1[0]== word2[0]:
  print(f"Your Brand Name is {adj} {name}!")
else:
  print("Try again.")
