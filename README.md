# Homework-01.02.2024
Homework for Mr Tauheed
# myfamily.py

myfamily = ("mother", "father", "sister", "brother", "sister")

print("Type of myfamily:", type(myfamily))

print("First sister:", myfamily[2])
print("Second sister:", myfamily[4])

new_family = myfamily + ("me",)
print("Updated family with 'me':", new_family)

updated_family = tuple(item for item in myfamily if item != "brother")
print("Updated family without 'brother':", updated_family)
