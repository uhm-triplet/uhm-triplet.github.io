---
layout: post
title: Multiplay Prototype
subtitle: Combat part of the multiplayer game
cover-img: /assets/img/yongu/multiplay/gameScene.png
thumbnail-img: /assets/img/yongu/multiplay/gameScene.png
share-img: /assets/img/yongu/multiplay/gameScene.png
tags: [Beats Bang, Multi Play, Lobby, Server, Relay]
---

## Used Skills
- Netcode for GameObjects
- Unity Services
- * Lobby
- * Relay

## Multiplayer prototype
From the main screen, click the Multiplayer button
![Main](../assets/img/yongu/multiplay/mainScreen.PNG)

Then, Host and Join buttons will be shown.
![HostJoin](../assets/img/yongu/multiplay/HostJoin.PNG)

Select Host to create a lobby. When entering the lobby, the room code will be shown, and the host is available to select the map(song).
![Lobby](../assets/img/yongu/multiplay/Lobby.PNG)

When another player clicks the Join Button, an input for code will be shown.
![JoinCode](../assets/img/yongu/multiplay/JoinCode.PNG)

Enter the same code from the host's lobby (this is a sample image and the code are not the same for the below image)
![JoinCode2](../assets/img/yongu/multiplay/joincode2.png)

When both players are ready, the host can click the start button to start the game
![Ready](../assets/img/yongu/multiplay/Ready.PNG)

Both players are in the game, their movement, animation, and variables are synchronized.
![GameScene](../assets/img/yongu/multiplay/gameScene.png)
![GameSync](../assets/img/yongu/multiplay/gameSync.png)


