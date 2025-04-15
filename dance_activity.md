### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# تصميم الرقصات

## الخطوة الأولى
قم بمطابقة الراقصين مع الملصق المناسب على الحائط. استخدم ``||hoc:قاعدة الراقص رقصة||`` كتلة لاختيار أي راقص يجب أن يؤدي أي رقصة. اضغط على زر تشغيل لتتعلم الرقصات.

#### ~ tutorialhint
الرقصة الزرقاء هي ``||hoc:wither wave||``

```ghost
    hoc._dance_activity()
```
```template
    hoc._dance_activity(ArmorStand.One, _Dances_Actvity.GolemGallop)
    hoc._dance_activity(ArmorStand.Two, _Dances_Actvity.DolphinDisco)
    hoc._dance_activity(ArmorStand.Three, _Dances_Actvity.WitherWave)
    hoc._dance_activity(ArmorStand.Four, _Dances_Actvity.MushroomMarch)
```

```package
hoc2024-ts-ar=github:ReWrite-Media/hoc2024-ts-ar/n/dance
```