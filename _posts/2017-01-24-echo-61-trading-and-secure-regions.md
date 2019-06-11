---
layout: post
title: "Echo #61: Trading and secure regions"
date: 2017-01-24
---

This week I have started working on secure regions and item trading!

It's really exciting to work on such impactful features, even if there's a lot of problems I'll have to solve.

Making item trading is rather easy - I have made trading systems several times in my other games, so I know what to do.
I just need to make interfaces, slightly adjust inventory code and it's done!

The hard part is making secure regions where item trading places - cities - will be located.

It wouldn't be hard if I just removed enemies from a normal region and call it secure region, but that's not what I want!

Cities hanging in interplanetary clouds, heavy traffic, lights, stations, statues, advertisement boards - that's what I want to see in secure regions.

That means a lot of objects, a lot of collisions and collisions is Sector Six weakness.
I'll have to figure out how to place objects in secure regions, how to approach movement, how will player access city interfaces and so on.

Right now I have almost finished making item trading and made a city sprite for the trading interface.

That's how trading works:

1. The player completes several missions in a region and it becomes secure.

2. The player enters the secure region from the map - the same way region missions are started.

3. The player goes to a city in a secure region. Not all regions will have them.

4. As the player approaches the city, the trading interface appears, which contains player's and city's inventories.

5. Dragging and dropping the part from the player's inventory to city's will sell that part for a certain amount of currency.

6. Dragging and dropping the part from the city's inventory to player's inventory, will buy that part if the player has enough currency.

Should be pleasantly simple!

That's all news I got for now, so until next time!

![](https://i.imgur.com/Da9ZajG.png)
