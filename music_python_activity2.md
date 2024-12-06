### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# تأليف الموسيقى

```python-template
hoc.add_instrument(Instrument.Guitar)
hoc.note(Note.La)
hoc.note(Note.Re)
hoc.note(Note.So)
hoc.note(Note.Do)
```

## استخدام الآلات الموسيقية
لم تنجح هذه الفكرة تمامًا، دعنا نجعل الأغنية أكثر قوة من خلال إضافة آلة ``||hoc:Instrument.Xylophone||`` لتحديد الآلة الموسيقية التي ستعزف. بعد ذلك، قم بتعريف النوتات التي ترغب في عزفها باستخدام.

#### ~ tutorialhint
الآن، أضف ``||hoc:Instrument.Xylophone||`` إضافة الآلة في بداية الكود باستخدام ``||hoc:hoc.add_instrument()||`` .


```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/n/music
```