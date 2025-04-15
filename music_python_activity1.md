### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# تأليف الموسيقى

```python-template
hoc.add_instrument(Instrument.Xylophone)
hoc.note(Note.Do)
hoc.note(Note.Do) 
hoc.note(Note.Do)
hoc.note(Note.Do)     
```

## استخدام الآلات الموسيقية
نحتاج لفتح الباب من خلال عزف اللحن الصحيح. أولاً، يجب أن يبدأ الكود الخاص بك بالآلة الموسيقية التي تعزف حالياً. استخدم ``||hoc:hoc.add_instrument()||`` لتحديد الآلة الموسيقية التي ستعزف. بعد ذلك، قم بتعريف النوتات التي ترغب في عزفها باستخدام ``||hoc:hoc.note()||`` .

#### ~ tutorialhint
أولاً، أضف ``||hoc:Instrument.Guitar||`` باستخدام ``||hoc:hoc.add_instrument()||`` ثم شغل النوتات ``||hoc:Note.La||`` ``||hoc:Note.Re||`` ``||hoc:Note.So||`` ``||hoc:Note.Do||`` باستخدام ``||hoc:hoc.note()||`` .


```package
hoc2024-ts-ar=github:ReWrite-Media/hoc2024-ts-ar/n/music
```