# game_jolt.py
Web-API for [gamejolt.com](https://gamejolt.com/game-api) website game-api with that you can add trophies, leaderboards, cloud data storage, and sessions to your games to get players

## Example
```python
import game_jolt
game_jolt = game_jolt.GameJolt(
	game_id="",
	username="",
	user_token="",
	private_key="")
user = game_jolt.get_user()
print(user)
```
