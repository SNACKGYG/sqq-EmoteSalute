# Emotes


[شرح التركيب](#emotes)
1- في سكربت الحركات الخاص بك stream قم بأضافة الملفات الموجودة في ملف
1- In your stream animation script, add the files in the
2- قم بأضافة الأكواد التي في الأسفل في المسار المحدد
2- Add the codes below in the specified path

**(https://discord.gg/QFJPnxTV) [Discord]**


**ضيف هاذا داخل ملف الحركات عندك بالأغلب سيكون المسار**
**Add this to your animations file, and it will most likely be the path**

```lua
\qb-emotes\client\AnimationList
```

```lua
    ["airforce01"] = { 
        "airforce@at_ease",
        "base",
        "Airforce - At Ease",
        AnimationOptions = {
            EmoteLoop = true,
            EmoteMoving = false
        }
    },
    ["airforce02"] = { 
        "airforce@attention",
        "base",
        "Airforce - Attention",
        AnimationOptions = {
            EmoteLoop = true,
            EmoteMoving = false
        }
    },
    ["airforce03"] = { 
        "airforce@parade_rest",
        "base",
        "Airforce - Parade Rest",
        AnimationOptions = {
            EmoteLoop = true,
            EmoteMoving = true
        } 
    },
    ["airforce04"] = {
        "airforce@salute",
        "base",
        "Airforce - Salute",
        AnimationOptions = {
            EmoteLoop = true,
            EmoteMoving = false
        } -- n7
    },
```
