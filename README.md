# Brooks-Shera-GPSDO
Simulink Model (and other information) of the Brooks Shera (W5OJM) GPSDO

This respository contains my Simulink model (.SLX file) of the 
Brooks Shera GPSDO, created from the comments and code in 
Rev 1.28 of his PIC software.

This simulation model was created using MATLAB version R2018B.

I have also included a PDF of a printout scan of Shera's 
PIC code (Rev. 1.28).  Please feel free to verify this source
code against my model.  (And my apologies for the PDF -- my copy of
the actual source code file disappeared long long ago).

I've included two Excel .XLSX files that contain 1 PPS jitter information.
The first file is jitter from a Quectel L76 GPS receiver, and the
other file is jitter from a Trimble Resolution T GPS receiver.  Either file can be used in
the Simulink model to simulate the PLL's response to jitter noise.

Please note that I might have made a mistake in my equations, assumptions, 
drawings, or interpretations.  If you see anything you believe to be in 
error or if anything is confusing, please feel free to contact me at:

        jca1955 'at' sbcglobal 'dot' net

And so I should add -- this information is distributed in the hope that
it will be useful, but WITHOUT ANY WARRANTY; without even the implied 
warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
