### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# تأليف الموسيقى

```python-template
hoc.add_instrument(Instrument.Xylophone)
hoc.add_instrument(Instrument.Guitar)
hoc.note(Note.La)
hoc.note(Note.Re)
hoc.note(Note.So)
hoc.note(Note.Do)
```

## استخدام الآلات الموسيقية
لازالت الأغنية تفتقر لشيء ما،دعنا نضيف بعض الإيقاع ``||hoc:Medium||`` باستخدام ``||hoc:hoc.drums()||`` .

#### ~ tutorialhint
أضف ``||hoc:hoc.drums()||`` إلى بداية الكود وقم بتعيينها إلى ``||hoc:Medium||`` لذا فإنه ستناغم مع الجيتار والإكسيليفون.


```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/n/music
```