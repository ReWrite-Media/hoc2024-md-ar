### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# تأليف الموسيقى

## الخطوة الأولى
الأغنية لا تزال تفتقر إلى شيء ما. دعنا نضيف إيقاعًا متوسط السرعة ``||hoc:drum||`` .

#### ~ tutorialhint
أضف إيقاع طبول متوسط السرعة عن طريق إضافة ``||hoc:drum||`` في بداية الكود.

```ghost
    hoc._add_instrument_activity()
    hoc.note()
    hoc.drums()
```
```template
    hoc._add_instrument_activity(Instrument_Activity.Xylophone)
    hoc._add_instrument_activity(Instrument_Activity.Guitar)
    hoc.note(Note.La)
    hoc.note(Note.Re)
    hoc.note(Note.So)
    hoc.note(Note.Do)
```

```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/n/music
```