### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# تأليف الموسيقى

## الخطوة الأولى
لنبدأ بتأليف بعض الموسيقى! يمكنك إضافة وإزالة الآلات الموسيقية باستخدام ``||hoc:إضافة آلة||`` و ``||hoc:إزالة الآلة الموسيقية ||`` وبدء إيقاع الطبول أيضًا باستخدام ``||hoc:طبل||`` ثم، استخدم ``||hoc:النوتة||`` لتصنع لحن. 

#### ~ tutorialhint
يمكنك إضافة أو إزالة أي آلة موسيقية في أي وقت خلال مقطوعتك الموسيقية. إذا قمت بتحديد عدة آلات، فستعزف جميعها نفس النغمة في الوقت نفسه.

```ghost
    hoc.add_instrument()
    hoc.remove_instrument()
    hoc.note()
    hoc.drums()
    for (let i = 0; i < 5; i++) {}
```
```template
    hoc.drums(Drums.Medium)
    hoc.add_instrument(Instrument.Xylophone)
    hoc.add_instrument(Instrument.Guitar)
    hoc.note(Note.Do)
    hoc.note(Note.So)
    hoc.note(Note.La)
    hoc.note(Note.Fa)
    hoc.add_instrument(Instrument.Bells)
    hoc.note(Note.Do)
    hoc.note(Note.So)
    hoc.note(Note.La)
    hoc.note(Note.Fa)
    hoc.remove_instrument(Instrument.Bells)
    hoc.note(Note.Do)
```

```package
hoc2024-ts-ar=github:ReWrite-Media/hoc2024-ts-ar/n/music
```