### Notes
---
- CVars are:
	- `scarcity_percentage_min`: Min amount for scarcity.
	- `scarcity_percentage_max`: Max amount for scarcity.
- The actual number is clamped in the range [0, 1], but the CVars aren't, which means you can shift towards less or more ammo by going below 0 or above 1, respectively.