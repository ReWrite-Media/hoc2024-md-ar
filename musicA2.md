### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# تأليف الموسيقى

## الخطوة الأولى
لم تنجح الفكرة تمامًا، دعنا نجعل الأغنية أكثر قوة من خلال إضافة الآلات الموسيقية ``||hoc:الإكسيليفون||`` بحيث تعزف كل من الإكسيليفون والجيتار النوتات معًا.

#### ~ tutorialhint
أضف ``||hoc:الإكسيليفون||`` في بداية الكود.

```ghost
    hoc._add_instrument_activity()
    hoc.note()
```
```template
    hoc._add_instrument_activity(Instrument_Activity.Guitar)
    hoc.note(Note.La)
    hoc.note(Note.Re)
    hoc.note(Note.So)
    hoc.note(Note.Do)
```

```package
hoc2024-ts-ar=github:ReWrite-Media/hoc2024-ts-ar/n/music
```