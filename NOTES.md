# 39. Applying CSS Classes Dynamically with ngClass
- Of course `ngStyle` and `ngClass` are related.
- `ngStyle` lets us change the style
- `ngClass` lets us change the class.
- Write the `{online:}` and if you have a dash, you have to wrap with a single quotation mark like `{'online'}` in the `server.component.html` of course. Wow, I think I'll always go with `{'online'}` format. It's consistent.
- I quickly changed to `{online-world}` and it didn't work. But `{'online-world'}` worked. And that means quotation mark is a must for all when doing this. 