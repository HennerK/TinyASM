# TinyASM for Commodore VIC20 / VC20 / VC-20

 <img src="images/title.png" alt="TinyASM" width="500" />
 
 TINYASM is an assembler for an unexpanded Commodore VIC20, which can be loaded directly from disk or tape without a module or memory expansion.

 The whole project is separated to have as much free memory as possible for programming. 
 That is why only the most essential comfort features are implemented.

***The free area for your code is from $18a7 to $1dff = 1368 bytes or
$1973 to $1dff in the tape version.***

## it is necessary to have seen the video to be able to fully operate the assembler

<video id="meinVideo" width="640" height="360" poster="images/title.png" controls preload="none">
  <source src="images/TinyASM_tutorial.webm" type="video/webm">
  your browser doesn't support this video format.
</video>



(or watch on YouTube: https://www.youtube.com/watch?v=D-vyuzpaASA )

## here is a quick overview of all functions ##
* .D - delete line
* .I$0a - insert 10 Bytes (255 max)
* .J$1A00 - jump to address or .J$Mn label $Mn
* .L“NAME“,8 - load program
  (.L"NAME",1 in tape version)
* .S“NAME“,8 - save program
  (.S"NAME",1 in tape version)
* .B - switches between code and byte view
* .T“ABCD…“ - insert text
* .$01$02$03... - enter bytes directly
* .Mn – (simple) memory labels - it's better to watch the video for this
* F1 – start your code

**Note:**
Only hexadecimal numbers are accepted by the assembler.

*lda #$0a* instead of *lda #10* 

enjoy!
