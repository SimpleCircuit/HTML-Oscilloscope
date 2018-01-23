	The HTML oscilloscope (HTMLO) serves as a teaching aide for those who are new to the use and functions of the oscilloscope, particularly beginning
	electronics students and hobbyists. This is a VIRTUAL oscilloscope - it is not functional, but a simulation designed to facilitate teaching the fundamentals
	of oscilloscope operation.

	The HTMLO is a web based program utilizing only HTML, CSS, and JavaScript. The program was written entirely by the author with the exception of the four 
	widget dials obtained from the YUI library (yuilibrary.com).
	
	Yahoo Software License Agreement (BSD License)
	Copyright (c) 2013, Yahoo! Inc. All rights reserved.

	-----------------------------------------------------------------------------------------------------------------------------------------------------
	This program is licensed under a BSD 3-clause (New BSD) license.

	Copyright (c) 2018  author:Terry Dunlap, All rights reserved.

	Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

	Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
	Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation
	and/or other materials provided with the distribution. Neither the name of the copyright holder nor the names of its contributors may be used to
	endorse or promote products derived from this software without specific prior written permission.
	 
	THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDER AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
	IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS
	BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE
	GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT
	LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH
	DAMAGE.
	------------------------------------------------------------------------------------------------------------------------------------------------------	

	Although it has been extensively tested it is still considered a beta version, and any corrections, improvements, or suggestions are appreciated.
	The HTMLO was designed on a PC at resolution of 1920x1080 pixels and is not scalable, although it runs well on a Microsoft Surface Pro 4.
	It's best viewed at higher resolutions with a width to height pixel ratio around 1.3 to 1.5. 
	The program can be accessed via the internet at http://www.ced3.net/HTMLO/Oscilloscope.html or used locally. It can be downloaded as a zip file from
	GitHub. The zip file contains the following files in a folder named HTMLO:

	Oscilloscope.css
	Oscilloscope.html
	yui-min.js
	readMe.txt
	
 	The program is run in a browser, but does not require an internet connection.
	It has been tested on Internet Explorer 10, Microsoft Edge, Google Chrome (version 62.0), and Firefox (version 43 and higher).
	
	Operational Notes
	The HTML oscilloscope is designed as a 20kHz dual-channel digital oscilloscope. It contains a variety of buttons, dials,
	and soft menus that control its various functions. Press buttons by left clicking them. Turn the &quotdigital&quot dials by
	clicking their outer edge. Each click will turn the dial one stop. Right click to turn the dial clockwise and left click to
	turn counter-clockwise.  Turn the &quotanalog&quot dials (the 5 widget dials on the right of the scope) by clicking and dragging
	the indicator dot clockwise or counter-clockwise. Pressing the center of a dial will reset it to its default value (0 or 1 position).
	Press the menu buttons to activate soft menus containing additional scope functions. Select a 
	function by clicking it. The soft menu can be closed by either moving the cursor off of it or pressing the Menu button.
	The combination of oscilloscope and wave function generator is found in some student lab and hobbyist scopes but not so
	much in advanced consumer or professional scopes. However, since the HTMLO is essentially a &quotstudent&quot scope and we 
	need some way of inputing signals, a handy function generator is included in the lower left panel. Even though the function generator is
	built-in, it must be connected to the scope by clicking one or both of the BNC jacks located next to the generator.
	Common waveforms (1kHz, 1V) are displayed by using the top row buttons. Bottom row buttons produce complex waveforms.
	Pressing the User button will display a soft menu where the operator can manually enter a waveform signal.

	Many of the controls on the HTMLO are not functional but will instead display information about their use when selected. There are also several
	labels that display tutorials on various aspects of the oscilloscope when clicked. Click on the "X" button at the upper right of the display or click on
	any label to close these tutorials. Clicking the Examples label will open a display with examples covering most of the controls of the HTMLO. 
	Working throught the examples is highly recommended.