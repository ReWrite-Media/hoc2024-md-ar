### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# تصميم الرقصات

## الخطوة الأولى
هيا نرقص! رتب حركات الرقص ``||hoc:رقصة||`` لتصمم رقصة للروبوت

#### ~ tutorialhint
يمكنك استخدام ``||loops:الحلقات التكرارية||`` بدلاً من استخدام عدة كتل لتكرار حركات الرقص

```ghost
    hoc.dances()
    for (let i = 0; i < 5; i++) {}
```
```template
    hoc.dance(Dance.DolphinDisco)
    hoc.dance(Dance.MushroomMarch)
    hoc.dance(Dance.WitherWave)
    hoc.dance(Dance.GolemGallop)
    hoc.dance(Dance.BlazeBounce)
    for (let i = 0; i < 3; i++) {
        hoc.dance(Dance.MushroomMarch)
    }
    hoc.dance(Dance.HoglinHandJive)
    hoc.dance(Dance.DungeonDig)
    hoc.dance(Dance.AlexAxle)
```

```package
hoc2024-ts-ar=github:ReWrite-Media/hoc2024-ts-ar/n/dance
```