| Command | Parameter | Remarks | Direction |
|:--------|:----------|:--------|:----------|
|MT00SW0000NT||Mirrored output 1  ?  1, 2  ?  2... |PC -> Matrix|
|MT00SW<u><b>XX</b></u>00NT|XX is the input port number(digits 01\~04)|1 input to all outputs|PC -> Matrix|
|MT00SW<u><b>XX</b></u><u><b>YY</b></u>NT|XX is the input port number (digits 01\~04)<br/>YY is the output port number (digits 01\~04)|Connect input XX to output YY|PC -> Matrix|
|MT00RD0000NT||Request matrix connection status.|PC -> Matrix|
|LINK:O<u><b>Y</b></u>I<u><b>X</b></u>;END|X is the input port number (digits 1\~4)<br/>Y is the output port number (digits 1\~4)|Matrix return current connection status to console|Matrix -> PC|
