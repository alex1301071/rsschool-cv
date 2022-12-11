# **Aleksey Stukalov**
___

## Contacts:
* Discord: alex130
* Telegram: @alex1301071
* E-mail: alex1301071@gmail.com

## About myself:
-

## Skils and Proficiency:
* Python
* html and css

## Code example:
Kata 'Pick peaks' from CodeWars.com (link):
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

