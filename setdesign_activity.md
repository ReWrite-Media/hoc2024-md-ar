### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# تصميم الديكور

## الخطوة الأولى
ابحث في الغرفة عن النصوص الثلاث التي تشرح المشاهد، ثم استخدم  ``||hoc:البيئة الوقت الطقس||`` لترتيبها حسب التسلسل الصحيح. 

#### ~ tutorialhint
يجب أن تكون بيئة التايغا ``||hoc:نهار||`` مع ``||hoc:ثلوج||`` يجب أن تكون بيئة الصحراء ``||hoc:غروب||`` مع ``||hoc:صافي||`` الطقس، يجب أن تكون بيئة الغابة ``||hoc:ليل||`` مع ``||hoc:ماطر||``.

```ghost
    hoc._set_activity()
```
```template
    hoc._set_activity(Biome_Activity.Taiga, Time_Activity.Day, Weather_Activity.Clear)
    hoc._set_activity(Biome_Activity.Desert, Time_Activity.Day, Weather_Activity.Clear)
    hoc._set_activity(Biome_Activity.Jungle, Time_Activity.Day, Weather_Activity.Clear)
```

```package
hoc2024-ts-ar=github:ReWrite-Media/hoc2024-ts-ar/n/set
```