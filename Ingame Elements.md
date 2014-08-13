# Elements of the game
that will be displayed to the player

## Population
Total planet population. If it exceeds a certain limit (depending on planet size and race size), a war will start. If it becomes 0, game over. Depends on birth and death rates, which can be changed through tech advancements. The number of people in each aging category is estimated with a stochastic model.
 
## Food (subcategorised):
### Meat, fish, crops, fruit, dairy
If total falls below a certain limit (depending on population) famine starts
If a particular category falls under limit, malnutrition starts
Both can lead to war
Consumption relevant to population and race size

## Wealth
Total amount of money available on the planet
Increases with production through taxes during peace. 
During war, no wealth is produced.

## Energy (subcategorised)
### wood, coal, oil, water, air, solar, nuclear, 
availability of types depends on age
if it falls below the required amount, there is a blackout risk
All power plants have an accident risk, and constant pollution rate

## Comfort
A measure of prosperity. Increases with technological advancement, increases in production of any field (especially services), aboundance of energy (not too much). Decreases with pollution, taxation, unemployment, malnutrition, famine, and war.

## Production(subcategorised)
### Food, Energy, Weapons, Construction, Services, Protection
All production is taxed to generate wealth, outside war. 
During war, no wealth is produced.
Player can set production allocation, up to a total depending on population, race strength, and age
Certain elements can limit, up or down, the allocation
 Food: determines the increase rate in food. The allocation between categories is determined by the number of buildings by type. Certain types of food (like corps) increase only once or twice a year (harvest periods).
 Energy: how much energy (and pollution) is produced
 Weapons: One of the limits that determines the abilities of your army (the other is population). They are lost 5 years after creation, if not used up during war before that (at the end of the war all weapons are lost)
 Construction: The constuction of new buildings by the player. Building analysis external. The income is generated at the start of the next year. All buildings add comfort when their construction starts and when it ends, but only services buildings generate comfort. Allocation of workers decides how quickly the construction will end (typically from 3 months to 2 years). It is possible for more that one building to be constructed at the same time, but that reduces the workers available for each and increases the construction time. Be careful for sudden increases in unemployment when construction of a building ends.
 Services: Continuously generate comfort and some income.
 Protection: Reduction of the death rate
 
#### Production Allocation and Unemployment
 The total of allocation available to the production of certain type is equal to the total allocation capacity of all the buildings of this type in the city in the city (see Buildings)
 Only adults are concidered workers (see race creation). These become available for allocation. Every 20 workers create 1 allocation point. Rounding is always down. Allocation points count to city, but you can order transportation of workers by creating citizent units, each consisting of 1000 citizens -> 300 workers -> 15 allocation points.
 Those workers that cannot be allocated to one of the production categories (analysed above) are unemployed.
 
## Incidents

Blackout: comfort drops tremendously, production stops, research decreases
Accident: The exact type of the accident depends on the production plant type and level, but it always increases pollution tremenously
Malnutrition: Production decreases, research decreases, comfort drops
Famine: Production stops, research stops, comfort zeros out
War: Production decreases (weapons increase), research decreases, population decreases, comfort zeroes out, ongoing research zeroes out (the research points accumulated). It stops when the conditions that started it end. It will stop immediately if population falls by more than 30%, but it may restart within the next 6 months.

tremendously: a lot of points, and a part of the loss is permanent (does not return when conditions end)
zeroes out: becomes zero, and half the loss is permanent.

## Time control: How much time will pass every second:
 1 day (war, incident)
 1 week
 15 days
 1 month (peace)
 3 months
 6 months (very fast)
Time always stops completely for player decisions.








