### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# تصميم الديكور

## تصميم الديكور
لنقم بتصميم ديكورات العرض! اختر أي من ``||hoc:biome, time, and weather||`` التي يجب أن يتم عرضها في كل فقرة من فقرات العرض.

#### ~ tutorialhint
بإمكانك استخدام ``||loops:الحلقات التكرارية||`` بدلاً من استخدام الكتل المتعددة للحفاظ على إعداد ديكورات معين لفترة أطول.

```ghost
    hoc.set(Biome.Taiga, Time.Sunrise, Climate.Clear)
    for (let i = 0; i < 5; i++) {}
```
```template
    hoc.set(Biome.Taiga, Time.Sunrise, Climate.Clear)
    hoc.set(Biome.Taiga, Time.Sunrise, Climate.Clear)
    for (let i = 0; i < 3; i++) {
        hoc.set(Biome.Taiga, Time.Day, Climate.Snow)
    }
    for (let i = 0; i < 3; i++) {
        hoc.set(Biome.Taiga, Time.Sunset, Climate.Rain)
    }
    for (let i = 0; i < 3; i++) {
        hoc.set(Biome.Taiga, Time.Night, Climate.Thunderstorm)
    }
    
```

```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/n/set
```