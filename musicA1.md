### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# تأليف الموسيقى

## الخطوة الأولى
علينا فتح الباب من خلال عزف اللحن الصحيح. استخدم ``||hoc:إضافة آلة||`` لاضافة آلة و ``||hoc:note||`` لاضافة النوتات.

#### ~ tutorialhint
أضف أولاً ``||hoc:guitar||`` استخدم ``||hoc:إضافة آلة||`` ثم استخدم ``||hoc:note||`` لاضافة النوتات ``||hoc:la||`` ``||hoc:re||`` ``||hoc:so||`` ``||hoc:do||``


```ghost
    hoc._add_instrument_activity()
    hoc.note()
```
```template
    hoc._add_instrument_activity(Instrument_Activity.Bells)
    hoc.note(Note.Do)
    hoc.note(Note.Do) 
    hoc.note(Note.Do)
    hoc.note(Note.Do)     
```

```package
hoc2024-ts-ar=github:ReWrite-Media/hoc2024-ts-ar/n/music
```