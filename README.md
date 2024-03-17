# Emotes Salute


- Warning: The animation was not created by us. We have only re-published it and attached an explanation of how to link it <br>
 تنبية لم يتم صنع الانميشن من قبلنا فقط قمنا بإعادة نشره و أرفاق شرح توضيحي لكيفية ربطه

[Discord](https://discord.gg/PWnxxHcpbr)

# Preview معاينة
![1211](https://github.com/SNACKGYG/sqq-emote/assets/97559522/66acc33e-6d09-4b4e-96b3-ba43939f2684)

### INSTALLATION التثبيت
1- In your stream animation script, add the files in the <br> في سكربت الحركات الخاص بك stream قم بأضافة الملفات الموجودة في ملف <br>

2- Add the codes below in the specified path <br> قم بأضافة الأكواد في المسار المحدد

3- **Add this to your animations file, and it will most likely be the path <br> ضيف هذا داخل ملف الحركات عندك بالأغلب سيكون المسار**

- Follow the next `qb-emotes > client.lua > AnimationList.lua` folder

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


[شرح التركيب](#emotes)
