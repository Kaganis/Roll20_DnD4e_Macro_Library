# Roll20 D&D 4th ed Macro Library
A collection of example macros for playing D&amp;D 4th edition in Roll20.  Supporting Pandemonium, The Guild, and the official Roll20 sheet conventions.

With the lack of official support for playing the 4th edition of D&D in Roll20, I've created this to give people a helping hand in getting new characters up & running.

While there is an official Roll20 4th edition sheet, it still largely leaves players up to their own devices when it comes to entering powers etc.  So to speed that process up, this repository tries to collect examples where other people have already written up that power, so all that people need to do is copy it to their sheet & do some light customisation, rather than write it from scratch themselves.  They will still need _some_ understanding of how the Roll20 macro language works, but hopefully less than if they were writing it from scratch.

For reasons mostly to do with the poor performance of the official 4e sheet at scale, not everywhere uses it.  Therefore this repository is divided into three broad sections:

### Pandemonium

<https://app.roll20.net/lfg/listing/41334/pandemonium>

This is the area for macro's created for use in the Pandemonium server & those who follow the same conventions.  This is characterised by a mostly empty character sheet, with attributes added as needed.  Templates with light customisation are used in the output format, and sometimes TokenMod is used.

Pandemonium does have significant & growing homebrew content.  Anything accepted in the main Pandemonium server is accepted here.

### The Guild

<https://app.roll20.net/lfg/listing/17445/guild-living-campaign>

This is the area for macro's created for use in The Guild server & those who follow the same conventions.  This is characterised by using bare bones text output, with the bare minimum of run time calculations to be as performant as possible on bare-bones hardware.

### The Roll20 official sheet.

<https://wiki.roll20.net/DnD4e_Character_Sheet>

This is the area for macro's created for use with the official Roll20 4e sheet.  The sheet is quite complex & rather big, with a lot of moving parts.

## Other notes

You can of course dig out example macro's from a different section than the tradition you're using it for (mainly if your section doesn't have that power, but another one does), but you'll need to convert it, which will take more work.  I think The Guild will be the easiest to pinch from here, due to the simplicity of their format.  Do beware that the different servers have their own different rules interpretations & rulings, which can change powers in very important & fundamental ways!

## How to use this Library

All three areas are organised identically.  Each power will have its own file, at the logical place in the directory structure.

The file for the power may have a few different implementations in it, so have a look through all of them, find whichever fits your personal preference best.

Each implementation will be organised in the following way:
- The macro in question.
- Any support or required secondary macro's, like secondary attacks, etc.
- Then a listing of any Attributes the Ability macro makes use of.
- At the bottom will be any explanitory notes.

Where you see **CHARACTER_NAME**, replace it with the name of the character you're building, exactly as found on the character sheet.

Powers won't include the effects of feats, magic items, or enhancements gained due to later levelling up, etc.  Only the most rules basic form of the power will be found here (though different levels of macro sophistication will be accepted).

Finally, we are accepting submissions!  Despite my best efforts, I'm never going to play with _every_ possible power.  ;-) Get me the text via any medium you care for should be fine.  Pull requests with the powers already perfectly formatted for the library is ideal, but a PM with your version just cut & pasted from your sheet will work.

Oh, and and if anyone I know from the communities wants commit rights & is willing to help fill this out, that would be most welcome.  :-)