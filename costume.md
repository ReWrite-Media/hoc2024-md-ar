### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# اختر الأزياء

## الخطوة الاولى
حان الوقت لاختيار بعض الأزياء! اجمع الأشكال المختلفة معًا ``||hoc:الرأس والجسم والساقين||`` .نسق الأزياء التي ترغب في أن يرتديها الروبوت أثناء العرض

#### ~ tutorialhint
بإمكانك استخدام ``||loops:الحلقات التكرارية||`` بدلاً من استخدام عدة كتل للحفاظ على الزيّ
لفترة أطول


```ghost
    hoc.costume()
    for (let i = 0; i < 5; i++) {}
```
```template
    hoc.costume(HeadWear.Knight_Helmet, MidWear.Cowboy_Shirt, LowerWear.Swim_Shorts)
    hoc.costume(HeadWear.Superstar_Hat, MidWear.Ballerina_Shirt, LowerWear.Astronaut_Legs)
    hoc.costume(HeadWear.Cowboy_Hat, MidWear.Green_TShirt, LowerWear.Khaki_Shorts)
    hoc.costume(HeadWear.Construction_Helmet, MidWear.Varsity_Jacket, LowerWear.Black_Boots)
    for (let i = 0; i < 3; i++) {
        hoc.costume(HeadWear.Sun_Glasses, MidWear.Basketball_Jersey, LowerWear.Cowboy_Pants)
    }
```

```package
hoc2024-ts-ar=github:ReWrite-Media/hoc2024-ts-ar/n/costume
```