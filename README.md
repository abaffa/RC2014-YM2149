# CP/M PTX Player compatible with RC2014 

PTX Player patched to run under CP/M that plays PT2/PT3. There are to versions adjusted to play correctly under 4Mhz and 8Mhz clocks.

* Requires an AY-3-8910 or YM2149 at D0 hex.


To assemble, you need to find SJASM, (runs under Windows, command line).


There are a number of undocumented Z80 instructions used in the original PTXPlayer. Also, it uses specific to SJASM
data types, which make it hard to port to other assemblers.

SJASM can be found at:

http://www.xl2s.tk/

----
* PTxPlay.asm - original source-code of PT2 and PT3 player for ZX Spectrum and MSX by S.V.Bulba 
* player_8mhz.asm - MM-PTxPlay.asm adjusted to run under 8 Mhz
* player_4mhz.asm - MM-PTxPlay.asm adjusted to run under 4 Mhz
