# **Aleksey Stukalov**
___

## Contacts:
* Discord: alex130
* Telegram: @s90_z
* E-mail: alex1301071@gmail.com

## About myself:
-

## Skils and Proficiency:
* Python
* html and css

## Code example:
Kata 'Pick peaks' from CodeWars.com [link](https://www.codewars.com/kata/reviews/565f448fb889330d06000116/groups/6305062a6468eb0001ed82ef):
```
def pick_peaks(arr):
	t, pos = 0, []
	for i in range(1, len(arr)):
		if arr[i-1] < arr[i]:
			if t: pos.pop()
			pos.append(i)
			t = 1
		if arr[i-1] > arr[i]:
			t = 0
	if t: pos.pop()
	peaks = [arr[i] for i in pos]
return {"pos":pos, "peaks":peaks}
```
## Experience
* No programming experience

## Edication
* htmlacademy.ru
* Python Programming (Michael Dawson)
* Programmin on Python stepik
* pythontutor.ru

## Languages
* English - A1

#

