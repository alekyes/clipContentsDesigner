# Designer für den Inhalt der Zwischenablage  #

*	Autoren: Noelia Ruiz Martínez.
*	[stabile Version herunterladen][1]
*	[Entwicklerversion herunterladen][2]

This add-on is used to add text to the clipboard, which can be useful when
you want to join sections of text together ready for pasting.  The clipboard
content can also be cleared.

## Tastenkombinationen ##
*	NVDA+windows+c: Add selected text, Unicode braille characters which
  represent MathML objects, or the string which has been marked with the
  review cursor, to the clipboard.
*	NVDA+windows+x: löscht die Zwischenablage
*	NVDA+windows+f9: Mark the current position of the review cursor as the start of the text to be added to the clipboard.
    If you use nvda+F9, the text will not be added.

Anmerkung: die obigen Befehle können im NVDA-Menü unter
Einstellungen/eingaben in der Kategorie Befehle zum Betrachten von Text
geändert werden.

## Einstellungen ##
*	Clip Contents Designer settings: Allows to set a separator which can be used to find the text segments once the entire added text is pasted.
It's also possible to choose if the added text will be appended or prepended.

Anmerkung: der obige Befehl kann im NVDA-Menü unter Einstellungen/eingaben
in der Kategorie Konfiguration geändert werden.

## Änderungen in Version 5.0 ##

*	The visual presentation of the dialog has been enhanced, adhering to the
  appearance of the dialogs shown in NVDA.
*	Benötigt NVDA 2016.4 oder neuer.

## Änderungen in Version 4.0 ##
*	Add-on settings are managed from NVDA configuration, so that standard
  profiles can be used to save different separators, and it's not needed to
  copy the settings for importing at reinstallation.
*	Now it's possible to choose if the added text will be appended or
  prepended, using the Add text before clip data check box from the Clip
  Contents Designer settings dialog.

## Änderungen in Version 3.0 ##
*	Braille representation of MathML objects can be added to the clipboard if
  MathPlayer is installed.
*	If no separator is set, just a single line will be placed between the
  added text segments.
*	A shortcut can be assigned to open the Clip Contents Designer settings
  dialog.
*	Added a check box in the settings dialog, for choosing if the separator
  should be copied to be imported when reinstalling the add-on.

## Änderungen in Version 2.0 ##
*	Hindi characters can be used as the separator between added contents.

## Änderungen in Version 1.0 ##
*	anfängliche Version

[[!tag dev stable]]

[1]: http://addons.nvda-project.org/files/get.php?file=ccd

[2]: http://addons.nvda-project.org/files/get.php?file=ccd-dev
