# Total-toasts
This winter is so cold in Himanchal! A group of n friends decided to buy k bottles of a soft drink called "Take- It- Light" to warm up a bit. Each bottle has l milliliters of the drink. Also, they bought c limes and cut each of them into d slices. After that, they found p grams of salt.


n, k, l, c, d, p, nl, np = map(int, input().split())

toasts_drink = (k * l) // nl
toasts_lime = c * d
toasts_salt = p // np

max_toasts = min(toasts_drink, toasts_lime, toasts_salt)

result = max_toasts // n
print(result)
