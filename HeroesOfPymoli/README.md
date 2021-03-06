# Pandas Challenge

## Conclusions

#### Three observations from Heroes Of Pymoli

1. User Data - The vast majority of players of Heroes Of Pymoli identfy as Males (84%).  While Females represent a smaller group (14%) they are very important to the game as their average purchase price is the highest for items in the game at $3.21, 6% higher than Males at $3.01. It is also intersting that the un-identified group has the highest average purchase price at $3.35, but is a significantly smaller group at $50.19 in total purchases. 


2. Age Data - 63% of players fall between the 15-24 age range. Heroes of Pymoli appears to be most popular with the 20-24 age group which represents 45% of total players and 47% of total purchases. Heroes of Pymoli does not have very many players above 40 years old. The 40+ group is also the least active when it comes to making item purchases.


3. Item Data - It appears that higher priced items perform better than lower priced items in driving total revenue for the company.  The majority of users are purchasing items that are $3+ with the top 5 item revenue drivers all being above $4.  The most popular item below $3 is the "Pursuit, Cudgel of Necromancy" that sold for 8 units for $1.02 each, only driving $8.16 of revenue.  This could mean that players do not see signifiant benefits from lower priced items and prefer items priced over $4. 


4. I noticed a few discrepencies with item data that may be relevant to the developers behind the game. There are 4 items that have duplicate names, but different item id's. The four items are Final Critic, Persuasion, Crucifer and Stormcaller. I'm thinking they may be upgradable items? My question to the developer would be if we want to define items by 'ItemId' or by 'Item Name'. The data that I've pulled here is using the 'ItemID' field and keeps items separated that have the same item name, but different IDs. If items were defined by Name I would need to go back through the data and sum together the two itemid data sets.
