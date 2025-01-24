# show-haughey
# Dakotah Haughey
### Fajitas
I couldn't choose a favorite food, but this one is definetly up there. I **really** enjoy sauteed onions and peppers and I like **tacos**.

---
### Places to get fajitas
1. El Maguey
2. Hyvee
    1. Buying the ingredients and making it myself
3. My mom's house

### Side dishes
* rice
* beans
* corn

[MyMovie](MyMovie.md)

---
### Favorite Quotes
> "There is grace in being willing to know and hear others."
>> *Michelle Obama*

> "The universe is under no obligation to make sense to you."
>> *Neil deGrasse Tyson*

---
### Code
This snip of code is allowing determined controls to move a character in a game accordingly.
```
func _process(delta: float) -> void:
	var velocity = Vector2.ZERO
	if Input.is_action_pressed("move_right"):
		velocity.x += 1
	if Input.is_action_pressed("move_left"):
		velocity.x -= 1
	if Input.is_action_pressed("move_down"):
		velocity.y += 1
	if Input.is_action_pressed("move_up"):
		velocity.y -= 1
```
[game code](github.com)