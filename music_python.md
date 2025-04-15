### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# تأليف الموسيقى

```python-template
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

## اصنع موسيقاك الخاصة
يحتاج الروبوت إلى مساعدة في تأليف الموسيقى لعرضه. استخدم الوظائف التالية لإنشاء موسيقى للروبوت.

``||hoc:hoc.add_instrument()||``
``||hoc:hoc.remove_instrument()||``
``||hoc:hoc.note()||``
``||hoc:hoc.drums()||``



```package
hoc2024-ts-ar=github:ReWrite-Media/hoc2024-ts-ar/n/music
```