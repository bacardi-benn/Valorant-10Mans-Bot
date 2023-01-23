# Valorant 10Mans Bot
The official bot for the [Valorant 10Mans server](https://discord.gg/A4tGeWhQC3). Contact benn#9833 on Discord for more information.

The Valorant 10Mans Bot manages concurrent queues for custom 5v5 Valorant games. 

## Bot Commands
</br> Command  &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; </br> | Description
| - | - |
| !queue  </br> or </br>  !q | starts queue if current queue is empty |
| !leave </br> or </br> !l | removes you from current queue if you are queued |
| !report *lobby_number* </br> or </br> !r *lobby_number* | reports command user as the team that won |
| !status </br> or </br> !s | to see the current queue's status |
| !info </br> or </br> !i | to see server elo stats |
| !register "*name#tag*" </br> or </br> !reg "*name#tag*" | register with server to get roles and permissions, **must include quotes** (for new players only) |
| !cancel *lobby_number* </br> or </br> !c *lobby_number* | cancels lobby match without calculating match results or elo; use in situations where a player disconnects, can't finish the game (must be urgent) | 
| !updateid "*name#tag*" </br> or </br> !uid "*name#tag*" | Update name#tag to what is used in-game |

## Gameplay Flow

The bot randomly selects two captains and has the captain of the team that's defending first have first pick. After which captains take turns selecting 2 players until all have been chosen.

