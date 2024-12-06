### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# تصميم الديكور

## الخطوة الأولى
ابحث في الغرفة عن النصوص الثلاث التي تشرح المشاهد، ثم استخدم  ``||hoc:biome, time, and weather||`` لترتيبها حسب التسلسل الصحيح. 

#### ~ tutorialhint
يجب أن تكون بيئة التايغا ``||hoc:day||`` مع ``||hoc:snow||`` يجب أن تكون بيئة الصحراء ``||hoc:sunset||`` مع ``||hoc:clear||`` الطقس، يجب أن تكون بيئة الغابة ``||hoc:night||`` مع ``||hoc:rain||``.

```ghost
    hoc._set_activity()
```
```template
    hoc._set_activity(Biome_Activity.Taiga, Time_Activity.Day, Weather_Activity.Clear)
    hoc._set_activity(Biome_Activity.Desert, Time_Activity.Day, Weather_Activity.Clear)
    hoc._set_activity(Biome_Activity.Jungle, Time_Activity.Day, Weather_Activity.Clear)
```

```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/n/set
```