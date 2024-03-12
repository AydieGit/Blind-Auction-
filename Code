from replit import clear
bidders = []
game_status = True
higest_bid = 0
print(art.logo)
def adding_to_a_list():
  name = input("What is your name?:  ")
  bid = int(input("What is your bid?: ? "))
  
  bidders2 = {}
  bidders2["name"] = name
  bidders2["bid"] = bid
  bidders.append(bidders2)
  
while game_status:
  adding_to_a_list()
  other_bidders = input("Are there any other bidders? Type 'yes or no'. ")
  clear()
  if other_bidders == "yes":
    continue
  else:
    game_status = False



for i in bidders:
  bid = int(i["bid"])
  name = i["name"]
  if bid > higest_bid:
    higest_bid = bid

print(f"Auction wins {name}, with {higest_bid} bid!")
