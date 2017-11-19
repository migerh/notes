# VIM semi-advanced (by blendi)

## visual line modes
* visual line mode shift+v, markiert komplette zeilen
* ctrl+v -> visual block mode. mit i / shift+i in insert mode gehen, editieren. beim verlassen wird der input im gesamten block gesetzt

## inside movement
* inside movement. z.B. ein string 'hello world' kann man mit ci' den kompletten inhalt ersetzen. di' löscht den inhalt
* f<char>, F, t, T jump to <char> (t => right, T => left, f on char, t before char)

## registers
* * register fügt aus/in OS clipboard ein, z.b. "*dd
* ctrl+r register name fügt den register inhalt in der vim command line ein

## marks
* sind sowas wie bookmarks
  * m<char> setzt ein mark auf <char>
  * '<char> geht zum entsprechenden mark
  * magische marks:
    * '' letzter mark wo man hergekommen ist?
  * :marks

## Macros
  * q<char> record Macro
  * @<char> play Macro
  * 10@q play macro 10 times

## split windows
  * ^Ws split horizontally
  * ^Wv veritcal split
  * ^W[hjkl] navigate windows
  * ^W= windows alignen
  * ^W[hjkl] move current buffer somewhere
  * ^Wc close buffer

## Plugins
  * NerdTree
  * MiniBufExpl
  * CtrlP

## misc
* shift+j -> join zeilen
* während man im normal mode auf einem wort steht mit * werden alle instanzen markiert. mit n+p kann man navigieren