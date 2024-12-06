### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# تصميم الديكور

```python-template
hoc.set(Biome.Taiga, Time.Sunrise, Climate.Clear)
hoc.set(Biome.Taiga, Time.Sunrise, Climate.Clear)
for i in range(3):
    hoc.set(Biome.Taiga, Time.Day, Climate.Snow)
for i in range(3):
    hoc.set(Biome.Taiga, Time.Sunset, Climate.Rain)
for i in range(3):
    hoc.set(Biome.Taiga, Time.Night, Climate.Thunderstorm)
```

## تصميم الديكور
لنقم بتصميم ديكورات العرض! اختر أي من ``||hoc:biome, time, and climate||`` التي يجب أن تعرض في كل فقرة من فقرات العرض ``||hoc:hoc.set()||`` .

```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/n/set
```