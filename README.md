# HTMLs

<HTML>
<head>
<title><title> tag for for info on Browser-Tab</title>
</head>
<!--tag attribute=value attribute value><!-->
<body bgcolor=FFFFFF text=000000>


<h1><center><b><u><i>HTML Basics</i></u></b></center></h1>
<br>
<b>"Hypertext"</b> is a text that can produce documents (web pages), that can contains reference to other documents (web pages). 
<br><br>
<b> "Markup Language"</b> is a language which sysntax can be used in the form of tags.
<br><br>
<b>"Tag"</b> is an instruction to browser
<br><br>
HTML developed by <b>"Tim Berners Lee"</b> 
<br><br>
<b><<!--><!-->head></b> section is used for non-content items, items which we do not want to show on page.<br>
<b><<!--><!-->body></b> section is used for content items, items which we want to show on page.<br>
<br><br>
<<!--"><!-->body> tag has 2 attributes (1) <b>bgcolor</b> for background color and (2) <b>text</b> for text color. Color can be mentioned in Hexadecimal from 0 (Low) to F (High).<br><br>
first 2 is Red => 00 = No Red, FF= Full Red<br>
middle 2 is Green => 00 = No Green, FF= Full Green<br>
last 2 is Blue => 00 = No Blue, FF= Full Blue<br><br>

Example:
<<!--"><!-->body bgcolor=110000 text=00FF00><br>
<br><br>------------------------------------------------------<br><br>
<h3><center><b><u>Tag : <i>header</i></u></b></center></h3>
<br> 
Body Provides 6 types of header from h1 to h6.
<h1><<!--"><!-->h1>This is header 1 <<!--"><!-->/h1></h1>
<h2><<!--"><!-->h2>This is header 2 <<!--"><!-->/h2></h2>
<h3><<!--"><!-->h3>This is header 3 <<!--"><!-->/h3></h3>
<h4><<!--"><!-->h4>This is header 4 <<!--"><!-->/h4></h4>
<h5><<!--"><!-->h5>This is header 5 <<!--"><!-->/h5></h5>
<h6><<!--"><!-->h6>This is header 6 <<!--"><!-->/h6></h6>

<br><br>----------------------------------<br><br>
<h3><center><b><u><i>Text Formating tags</i></u></b></center></h3>
<<!--"><!-->b> <b> tag</b><<!--"><!-->/b> for bold <br>
<<!--"><!-->i> <i> tag</i><<!--"><!-->/i> for Italic <br>
<<!--"><!-->u> <u> tag</u><<!--"><!-->/u> for Underline  <br>
<<!--"><!-->mark> <mark> tag</mark><<!--"><!-->/mark> for highlighting a text.  <br>
<<!--"><!-->strike> <strike> tag</strike><<!--"><!-->/strike> for strikethrough  <br>
<<!--"><!-->sup> <sup> tag</sup><<!--"><!-->/sup> for superscript. Application : 2<sup>3</sup>=8 <br>
<<!--"><!-->sub> <sub> tag</sub><<!--"><!-->/sub> for subscript.Application : Formula of water = H<sub>2</sub>O  <br>
<center> <<!--"><!-->center> tag</u> to show text in center of screen <<!--"><!-->/center></center>
<<!--"><!-->br> tag at end of line for new line without closing tag <br>

<br><br>----------------------------------<br><br>
<h3><center><b><u><i>Paragraph tag</i></u></b></center></h3>
<p><<!--"><!-->p>Paragraph is collection of lines.this is used to wirte data in paragraphs.<<!--"><!-->/p></p>
<br><br>----------------------------------<br><br>


<h3><center><b><u>Tag : <i>marquee</i></u></b></center></h3>
<br>
<<!--"><!-->marquee> tag is used for scrolling or sliding text.
<marquee><<!--"><!-->marquee>This tesx is written inside marquee<<!--"><!-->/marquee></marquee>
<br>
marquee has 4 attributes:<br>
(1) behavior => this define type of scrollin. 3 types : <br>
(i) scroll<br>
<marquee behavior=scroll><<!--"><!-->marquee behavior=scroll>This tesx is written inside marquee with behavior=scroll<<!--"><!-->/marquee></marquee>
(ii) slide<br>
<marquee behavior=slide><<!--"><!-->marquee behavior=slide>This tesx is written inside marquee with behavior=slide<<!--"><!-->/marquee></marquee>
(iii) alternate<br>
<marquee behavior=alternate><<!--"><!-->marquee behavior=alternate>This tesx is written inside marquee with behavior=alternate<<!--"><!-->/marquee></marquee>
<br><br>
(2) direction => values can be up, down, left, right, alternate <br>
(i) up <br>
<marquee direction=up><<!--"><!-->marquee direction=up>This tesx is written inside marquee with direction=up<<!--"><!-->/marquee></marquee>
(ii) down <br>
<marquee direction=down><<!--"><!-->marquee direction=down>This tesx is written inside marquee with direction=down<<!--"><!-->/marquee></marquee>
(iii) left <br>
<marquee direction=left><<!--"><!-->marquee direction=left>This tesx is written inside marquee with direction=left<<!--"><!-->/marquee></marquee>
(iv) right <br>
<marquee direction=right><<!--"><!-->marquee direction=right>This tesx is written inside marquee with direction=right<<!--"><!-->/marquee></marquee>
<br><br>
(3) loop => Specifies how many times content moves. The default value is infinite.<br> 	
<marquee loop=2><<!--"><!-->marquee loop=2>This tesx is written inside marquee with loop=2. After 2 attempt, it will be invisible.<<!--"><!-->/marquee></marquee>
<br><br>
(4) height and hspace (pixel) to defnie height of marquee and  horizontal empty space from left and right side around the marquee.<br>

<marquee height=100 hspace=100 bgcolor=red><<!--"><!-->marquee height=100 hspace=100>This tesx is written inside marquee with height=100 hspace=100 <<!--"><!-->/marquee></marquee>
width and vspace (pixel) to defnie width of marquee and  vertical empty space from last line to next line around the marquee.<br>
<marquee width=500 vspace=100 bgcolor=red><<!--"><!-->marquee width=500 vspace=1000>This tesx is written inside marquee with width=500 vspace=100<<!--"><!-->/marquee></marquee>
<br><br>
mixture of all 4 attributes : <br>
<marquee height =100 width=1000 vspace=10 hspace=100 bgcolor=red><<!--"><!-->marquee height =100 width=1000 vspace=10 hspace=100 bgcolor=red>This tesx is written inside marquee with height =100 width=1000 vspace=10 hspace=100 bgcolor=red<<!--"><!-->/marquee></marquee>
<br>
(5) scrolldelay	in seconds	Defines how long to delay between each jump. <br> 
<marquee scrolldelay=60><<!--"><!-->marquee scrolldelay=60>This tesx is written inside marquee with scrolldelay=60<<!--"><!-->/marquee></marquee>

<br><br>----------------------------------<br><br>

<h3><center><b><u>Tag : <i>img</i></u></b></center></h3>
<b>JPG</b> : Joint Photograph Graphic<br>
<b>PNG</b> : Portable Network Graphic<br>
<br>
<<!--><!-->img> tag to display image on webpage. It is a <b><u>non-paired</u></b> tag.
<br><br>
If image is in same folder as HTML file, then no need to give path. <<!--><!-->img src=image_in_same_folder.jpg>
<br><br>
<img src=image_in_same_folder.jpg><br>
<br><br>
If image is in different folder as HTML file, then need to give path. <<!--><!-->img src=image/image_in_different_folder.jpg>
<br><br>
<img src=image/image_in_different_folder.jpg><br>
<br><br>
4 Attributes of <<!--><!-->img> tag :
<br>
(1) <b>src</b> : To specify the sourcepath of images
<br>
(2) <b>width</b> : Horizontal size of image in unit of pixels
<br>
(3)<b>height</b> : Vertical size of image in unit of pixels
<br>
(4) <b>alt</b> : Alternative text of image, if images not loaded.
<br><br>
Example : <<!--><!-->img src=image_in_same_folder.jpg width=200px heoght=300px <u>alt="image_in_same_folder.jpg, an alternative text to show info to reader that here is an image to be loaded."</u>>
<br><br>
<img src=image_in_same_folder.jpg width=200px heoght=300px alt="image_in_same_folder.jpg, an alternative text to show info to reader that here is an image to be loaded.">
<img src=image_in_same_folder2.jpg width=200px heoght=300px alt="image_in_same_folder.jpg, an alternative text to show info to reader that here is an image to be loaded.">
<br><br>----------------------------------<br><br>

<h3><center><b><u>Tag : <i><<!--><!-->a>, anchor tag for Hypelinks</i></u></b></center></h3>
<br>
Hyperlinks are used to create link from one page to another page.<br>
<br><br>
anchor <<!--><!-->a> is a paired tag with attribute href="url".
<br><br>
<<!--><!-->a href="https://google.co.in">Click This Hyperlink to open Google webpage<<!--><!-->/a>
<br><br>
<a href="https://google.co.in">Click This Hyperlink to open Google webpage</a>

<br><br>----------------------------------<br><br>
<h3><center><b><u>Tag : <i>List</i></u></b></center></h3>
<b>List</b> cab be 2 types -<br>
(1) <b>Un-odered list <<!--><!-->ul></b> : list-items <<!--><!-->li> are present with dot (.) bullets
<br><br>
<<!--><!-->ul><br>
	<<!--><!-->li>item 1<<!--><!-->/li><br>
	<<!--><!-->li>item 2<<!--><!-->/li><br>
	<<!--><!-->li>item 3<<!--><!-->/li><br>
<<!--><!-->/ul><br>

<ul>
	<li>item 1</li>
	<li>item 2</li>
	<li>item 3</li>
</ul>

<br><br>
(2) <b>Odered list<<!--><!-->ol></b> : list-items <<!--><!-->li> are present with number bullets
<br><br>
<<!--><!-->ol><br>
	<<!--><!-->li>item 1<<!--><!-->/li><br>
	<<!--><!-->li>item 2<<!--><!-->/li><br>
	<<!--><!-->li>item 3<<!--><!-->/li><br>
<<!--><!-->/ol><br>

<ol>
	<li>item 1</li>
	<li>item 2</li>
	<li>item 3</li>
</ol>

<br><br>----------------------------------<br><br>

<h3><center><b><u>Tag : <i>Table</i></u></b></center></h3>
<br>
To create Table, we need 5 types of Paired-tags in html - <br>
(1) <b><<!--><!-->table></b> : to start/end the table. it has 1 attribute called <b>border</b>.border=0 means no border and border="1" means border 
<br><br>

<<!--><!-->table border="0"><br>
<<!--><!-->tr><br>
<<!--><!-->td>Table without Border<<!--><!-->/td><br>
<<!--><!-->/tr><br>
<<!--><!-->/table>

<br><br>

<table border="0">
	<tr>
		<td>Table without Border</td>
	</tr>
</table>

<br>

<<!--><!-->table border="1"><br>
<<!--><!-->tr><br>
<<!--><!-->td>Table with Border<<!--><!-->/td><br>
<<!--><!-->/tr><br>
<<!--><!-->/table>


<table border="1">
	<tr>
		<td>Table with Border</td>
	</tr>
</table>

<br>
(2) <b><<!--><!-->caption></b> : heading of the table <br>

<br><br>

<<!--><!-->table border="1"><br>
<<!--><!-->caption>Caption of Table<<!--><!-->/caption><br>
<<!--><!-->tr><br>
<<!--><!-->td>Table with Border<<!--><!-->/td><br>
<<!--><!-->/tr><br>
<<!--><!-->/table>

<br><br>

<table border="1">
	<caption><b>Caption of Table</b></caption>
	<tr>
		<td>Table with Border</td>
	</tr>
</table>

<br>

(3) <b><<!--><!-->tr></b> : to define the row the table <br>
<br><br>

<<!--><!-->table border="1"><br>
<<!--><!-->caption>Caption of Table<<!--><!-->/caption><br>
<<!--><!-->tr><br>
<<!--><!-->td>Row 1, cell 1<<!--><!-->/td><br>
<<!--><!-->/tr><br>
<<!--><!-->tr><br>
<<!--><!-->td>Row 2, cell 1<<!--><!-->/td><br>
<<!--><!-->/tr><br>
<<!--><!-->/table>

<br><br>

<table border="1">
	<caption><b>Caption of Table</b></caption>
	<tr>
		<td>Row 1, cell 1</td>
	</tr>
	<tr>
		<td>Row 2, cell 1</td>
	</tr>
</table>

<br>

(4) <b><<!--><!-->th></b> : to define header cell the table. Automatically text will be in bold. <br>
<br><br>

<<!--><!-->table border="1"><br>
<<!--><!-->caption>Caption of Table<<!--><!-->/caption><br>
<<!--><!-->tr><br>
<<!--><!-->th>Row 1, header cell 1<<!--><!-->/th><br>
<<!--><!-->/tr><br>
<<!--><!-->tr><br>
<<!--><!-->td>Row 2, normal cell 1<<!--><!-->/td><br>
<<!--><!-->/tr><br>
<<!--><!-->/table>

<br><br>

<table border="1">
	<caption><b>Caption of Table</b></caption>
	<tr>
		<th>Row 1, header cell 1</th>
	</tr>
	<tr>
		<td>Row 2, normal cell 1</td>
	</tr>
</table>

<br>
(5) <b><<!--><!-->td></b> : to define normal cell the table <br>
<br><br>

<<!--><!-->table border="1"><br>
<<!--><!-->caption>Caption of Table<<!--><!-->/caption><br>
<<!--><!-->tr><br>
<<!--><!-->th>Row 1, header cell 1<<!--><!-->/th><br>
<<!--><!-->th>Row 1, header cell 2<<!--><!-->/th><br>
<<!--><!-->/tr><br>
<<!--><!-->tr><br>
<<!--><!-->td>Row 2, normal cell 1<<!--><!-->/td><br>
<<!--><!-->td>Row 2, normal cell 2<<!--><!-->/td><br>
<<!--><!-->/tr><br>
<<!--><!-->/table>

<br><br>

<table border="1">
	<caption>	<b>Caption of Table</b></caption>
	<tr>
		<th>Row 1, header cell 1</th>
		<th>Row 1, header cell 2</th>
	</tr>
	<tr>
		<td>Row 2, normal cell 1</td>
		<td>Row 2, normal cell 2</td>
	</tr>
</table>

<br>
Example :
<br>

<table border="1">
	<caption><u><<!--><!-->table border="1"></u><<!--><!-->caption><b>Caption of Table</b><<!--><!-->/caption></caption>
	<tr>
		<th><b><<!--><!-->tr></b><<!--><!-->th>Row 1, header cell 1<<!--><!-->/th></th>
		<th><<!--><!-->th>Row 1, header cell 2<<!--><!-->/th></th>
		<th><<!--><!-->th>Row 1, header cell 3<<!--><!-->/th><b><<!--><!-->/tr></b></th>
	</tr>
	<tr>
		<td><b><<!--><!-->tr></b><<!--><!-->td>Row 2, normal cell 1<<!--><!-->/td></td>
		<td><<!--><!-->td>Row 2, normal cell 2<<!--><!-->/td></td>
		<td><<!--><!-->td>Row 2, normal cell 3<<!--><!-->/td><b><<!--><!-->/tr></b><u><<!--><!-->/table></u></td>
	</tr>
</table>

<br>
<<!--><!-->td> <<!--><!-->th> or  has 2 attributes <b>"cospan"</b> i.e. to murge cells horizontally and <b>"rowspan"</b> i.e. to murge cells vertically. 
<br>
Note: 
<br>
in case of "colspan" : same row's next cell "<<!--><!-->td>" will be not written.
<br>
in case of "rowspan" : next row's next cell "<<!--><!-->td>" will be not written. Next row will have less cell entries.
<br><br>

<<!--><!-->table border="1"><br>
<<!--><!-->caption>Caption of Table<<!--><!-->/caption><br>
<<!--><!-->tr><br>
<<!--><!-->th>Row 1, header cell 1<<!--><!-->/th><br>
<<!--><!-->th colspan=2>use of "colspan" : murger of header cells 2 and 3 in Row 1<<!--><!-->/th><br>
<<!--><!-->th>Row 1, header cell 4<<!--><!-->/th><br>
<<!--><!-->/tr><br>
<<!--><!-->tr><br>
<<!--><!-->td>Row 2, normal cell 1<<!--><!-->/td><br>
<<!--><!-->td rowspan=2>use of "rowspan" : murger of normal cell 3 of Row 2 and 3 <<!--><!-->/td><br>
<<!--><!-->td>Row 2, normal cell 3<<!--><!-->/td><br>
<<!--><!-->td>Row 2, normal cell 4<<!--><!-->/td><br>
<<!--><!-->/tr><br>
<<!--><!-->tr><br>
<<!--><!-->td>Row 3, normal cell 1<<!--><!-->/td><br>
<<!--><!-->td>Row 3 and , normal cell 3 <<!--><!-->/td><br>
<<!--><!-->td>Row 3 and , normal cell 4 <<!--><!-->/td><br>
<<!--><!-->/tr><br>
<<!--><!-->/table>

<br><br>

<table border="1">
	<caption><b>Caption of Table</b></caption>
	<tr>
		<th>Row 1, header cell 1</th>
		<th colspan=2>use of <b>"colspan"</b> : murger of header cells 2 and 3 in Row 1</th>
		
		<th>Row 1, header cell 4</th>
	</tr>
	<tr>
		<td>Row 2, normal cell 1</td>
		<td>Row 2, normal cell 2</td>
		<td rowspan=2>use of <b>"rowspan"</b> : murger of normal cell 3 of Row 2 and 3</td>
		<td>Row 2, normal cell 4</td>
	</tr>
	<tr>
		<td>Row 3, normal cell 1</td>
		<td>Row 3, normal cell 2</td>

		<td>Row 3, normal cell 4</td>
	</tr>
</table>

<br><br>----------------------------------<br><br>

<h3><center><b><u>Tag : <i>Form</i></u></b></center></h3>
<b>Form</b> is a collection of "form-elements".
<br>
Form is used to collect details from users.
<br>
HTML Forms are created by using a set of tags (around 11) : <br>
<br>

<table border="1">
	<tr>
		<td>(1) <<!--><!-->form></td>
		<td>(2) <<!--><!-->input></td>
	</tr>
	<tr>
		<td>(3) <<!--><!-->textarea></td>
		<td>(4) <<!--><!-->label></td>
	</tr>
	<tr>
		<td>(5) <<!--><!-->button></td>
		<td>(6) <<!--><!-->select></td>
	</tr>
	<tr>
		<td>(7) <<!--><!-->option></td>
		<td>(8) <<!--><!-->optgroup></td>
	</tr>
	<tr>
		<td>(9) <<!--><!-->fieldset></td>
		<td>(10) <<!--><!-->legend></td>
	</tr>
	<tr>
		<td>(11) <<!--><!-->details></td>
		<td></td>
	</tr>
</table>

<br>
<<!--><!-->input> tag has around set of 20 attributes : 
<br><br>

<table border="1">
	<caption>Attributes of <b><<!--><!-->input> </b>tag</caption>
	<tr>
		<td>(1) type</td>
		<td>(2) maxlength</td>
		<td>(3) value</td>
		<td>(4) name</td>
	</tr>
	<tr>
		<td>(5) id</td>
		<td>(6) tabindex</td>
		<td>(7) placeholder</td>
		<td>(8) src</td>
	</tr>
	<tr>
		<td>(9) width</td>
		<td>(10) height</td>
		<td>(11) checked</td>
		<td>(12) disabled</td>
	</tr>
	<tr>
		<td>(13) min</td>
		<td>(14) max</td>
		<td>(15) autofocus</td>
		<td>(16) required</td>
	</tr>
	<tr>
		<td>(17) pattern</td>
		<td>(18) multiple</td>
		<td>(19) autocomplete</td>
		<td>(20) list</td>
	</tr>
</table>
<br>
<br>
<<!--><!-->input> tag "type" attribute can have around 20 values : 
<br><br>

<table border="1">
	<caption>Value options for attribute <b>"type"</b> of <<!--><!-->input> tag</caption>
	<tr>
		<td>(1) text</td>
		<td>(2) password</td>
		<td>(3) checkbox</td>
		<td>(4) radio</td>
	</tr>
	<tr>
		<td>(5) file</td>
		<td>(6) submit</td>
		<td>(7) reset</td>
		<td>(8) image</td>
	</tr>
	<tr>
		<td>(9) hidden</td>
		<td>(10) button</td>
		<td>(11) color</td>
		<td>(12) date</td>
	</tr>
	<tr>
		<td>(13) month</td>
		<td>(14) time</td>
		<td>(15) week</td>
		<td>(16) search</td>
	</tr>
	<tr>
		<td>(17) number</td>
		<td>(18) range</td>
		<td>(19) email</td>
		<td>(20) url</td>
	</tr>
</table>
<br><br>

Though "input" tag wil work outside of the form tag, but it is recommended to use it inside "form" tag.<br><br>
Use name attribute to give "name" to each input tag. This name will be used along with submitted value while submitting th form through "submit" type. Check the Url after submitting the form.<br>

<br>
<br>

<form>
	Enter Username : <input type="text" name="input_type_text">
	<br>
	Enter Password : <input type="password" name="input_type_password">
	<br>
	Enter Age (min =18 max =60, otherwise while submit it will give error) : <input type="number" name="input_type_number" min="0" max="60">
	<br>
	Select Gender (Use radio with same "name") : Female:<input type="radio" name="input_type_radio"> Male: <input type="radio" name="input_type_radio">
	<br>
	Are you Indian ( use checbox, to get answer in yes or no) : <input type="checkbox" name="input_type_checkbox">
	<br>
	DOB : <input type="date" name="input_type_checkbox">
	<br>
	Office Enter Time : <input type="time" name="input_type_time">
	<br>
	upload Profile Photo (only 1 upload): <input type="file" name="input_type_file">
	<br>
	upload 3 Months Bills ( multiple upload): <input type="file" name="input_type_mfile" multiple="multiple">
	<br>
	Enter Email Address : <input type="email" name="input_type_email">
	<br>
	Enter Company URL : <input type="url" name="input_type_url">
	<br>
	Choose T-Shirt Color: <input type="color" name="input_type_color">
	<br>
	Hidden Input (auto-filled in form by browser while submit): <input type="hidden" name="input_type_hidden" value="Hidden_item_autofilled">
	<br>
	Search-Box (text input with a cross x): <input type="search" name="input_type_search">
	<br>
	Reset/Clear Form : <input type="reset">
	<br>
	Submit/Register Form : <input type="submit">
</form>
<br><br>
<b> Use Table to arrange/structure Form in presentable way.</b>
<br><br>

<<!--><!-->table border="1"><br>
	<<!--><!-->form><br>
		<<!--><!-->tr><br>
			<<!--><!-->td>Enter Username :<<!--><!-->/td><br>
			<<!--><!-->td><<!--><!-->input type="text" name="input_type_text"><<!--><!-->/td><br>
			<<!--><!-->td><<!--><!-->input type="submit"><<!--><!-->/td><br>
		<<!--><!-->/tr><br>
	<<!--><!-->/from><br>
<<!--><!-->/table><br>

<br><br>
<table border="1">
	<form>
		<tr>
			<td>Enter Username :</td>
			<td><input type="text" name="input_type_text"></td>
			<td><<!--><!-->input type="text" name="input_type_text"></td>
		</tr>
		<tr>
			<td>Enter Password :</td>
			<td><input type="password" name="input_type_password"></td>
			<td><<!--><!-->input type="password" name="input_type_password"></td>
		</tr>
		<tr>
			<td>Enter Age (min =18 max =60, otherwise while submit it will give error) :</td>
			<td><input type="number" name="input_type_number" min="0" max="60"></td>
			<td><<!--><!-->input type="number" name="input_type_number" min="0" max="60"></td>
		</tr>
		<tr>
			<td>Select Gender (Use radio with same "name" or "list") :</td>
			<td>Female:<input type="radio" name="input_type_radio"> Male: <input type="radio" name="input_type_radio" checked></td>
			<td>Female:<<!--><!-->input type="radio" name="input_type_radio"> Male: <<!--><!-->input type="radio" name="input_type_radio" checked></td>
		</tr>
		<tr>
			<td>Are you Indian ( use checbox, to get answer in yes or no) : </td>
			<td><input type="checkbox" name="input_type_checkbox"></td>
			<td><<!--><!-->input type="checkbox" name="input_type_checkbox"></td>
		</tr>
		<tr>
			<td>DOB :</td>
			<td><input type="date" name="input_type_checkbox"></td>
			<td><<!--><!-->input type="date" name="input_type_checkbox"></td>
		</tr>
		<tr>
			<td>Office Enter Time : </td>
			<td><input type="time" name="input_type_time"></td>
			<td><<!--><!-->input type="time" name="input_type_time"></td>
		</tr>
		<tr>
			<td>upload Profile Photo (only 1 upload):</td>
			<td><input type="file" name="input_type_file"></td>
			<td><<!--><!-->input type="file" name="input_type_file"></td>
		</tr>
		<tr>
			<td>upload 3 Months Bills ( multiple upload):</td>
			<td><input type="file" name="input_type_mfile" multiple="multiple"></td>
			<td><<!--><!-->input type="file" name="input_type_mfile" multiple="multiple"></td>
		</tr>
		<tr>
			<td>Enter Email Address :</td>
			<td><input type="email" name="input_type_email"></td>
			<td><<!--><!-->input type="email" name="input_type_email"></td>
		</tr>
		<tr>
			<td>Enter Company URL :</td>
			<td><input type="email" name="input_type_email"></td>
			<td><<!--><!-->input type="email" name="input_type_email"></td>
		</tr>
		<tr>
			<td>Choose T-Shirt Color:</td>
			<td><input type="color" name="input_type_color"></td>
			<td><<!--><!-->input type="color" name="input_type_color"></td>
		</tr>
		<tr>
			<td>Hidden Input (auto-filled in form by browser while submit):</td>
			<td><input type="hidden" name="input_type_hidden" value="Hidden_item_autofilled"></td>
			<td><<!--><!-->input type="hidden" name="input_type_hidden" value="Hidden_item_autofilled"></td>
		</tr>
		<tr>
			<td>Search-Box (text input with a cross x):</td>
			<td><input type="search" name="input_type_search"></td>
			<td><<!--><!-->input type="search" name="input_type_search"></td>
		</tr>
		<tr>
			<td>Select Nationality :</td>
			<td><input type="text" name="nationality" list="id_for_list_of_countries_in_world_datalist">
					<datalist id="id_for_list_of_countries_in_world_datalist">
						<option>India</option>
						<option>Pakistan</option>
						<option>Nepal</option>
						<option>Others</option>
					</datalist>	
			</td>
			<td><<!--><!-->input type="search" name="nationality" list="id_for_list_of_countries_in_world_datalist"><br>
					<<!--><!-->datalist id="id_for_list_of_countries_in_world_datalist"><br>
						<<!--><!-->option>India<<!--><!-->/option><br>
						<<!--><!-->option>Pakistan<<!--><!-->/option><br>
						<<!--><!-->option>Nepal<<!--><!-->/option><br>
						<<!--><!-->option>Others<<!--><!-->/option><br>
					<<!--><!-->/datalist>
			</td>
		</tr>
		<tr>
			<td>Reset/Clear Form :</td>
			<td><input type="reset"></td>
			<td><<!--><!-->input type="reset"></td>
		</tr>
		<tr>
			<td>Submit/Register Form :</td>
			<td><input type="submit"></td>
			<td><<!--><!-->input type="submit"></td>
		</tr>
	</form>
</table>

<br><br>

<b>tabindex</b> attribute to change order of TAB key. <<!--><!-->input type="text" name="input_type_text" tabindex="3">
<br><br>
<b>checked</b> attribute to default check/select in Checkbox or radio button. <<!--><!-->input type="checkbox" name="input_type_checkbox" checked="checked">
<br><br>
<b>autocomplete</b> attribute to maintain histoy of all entered values in form. Default is on <<!--><!-->input type="text" name="input_type_text" autocomplete="off"> or can be used as entire form level <<!--><!-->form autocomplete="off">
<br><br>
<b>autofocus</b> attribute to place the cursor/mouse pointer in the specific textbox automatically when webpage is opened. <<!--><!-->input type="text" name="input_type_text" autofocus>
<br><br>
<b>step</b> attribute to specify the value should be used in incremental/decremental in case of type=number. Default is 1 <<!--><!-->input type="number" name="input_type_number" step="10">
<br><br>
<b>required</b> attribute to make an input mandatory to submit the form. <<!--><!-->input type="number" name="input_type_number" required>
<br><br>
<b>pattern</b> attribute to specify regex pattern to check the entered value of an input. <<!--><!-->input type="number" name="input_type_number" pattern="*[0-9]*$">
<br><br>
<b>list="id of datalist" (with datalist/option)</b> attribute to specifies "id" of the <<!--><!-->datalist> tag, from which the list of serach result should be retreived, while typing something in textbox. <<!--><!-->input type="text" name="input_type_country" list="id of datalist">
<br><br>
<form>
	Select Nationality : <input type="text" list="id_for_list_of_countries_in_world_datalist">
	<datalist id="id_for_list_of_countries_in_world_datalist">
		<option>India</option>
		<option>Pakistan</option>
		<option>Nepal</option>
		<option>Others</option>
	</datalist>	
</form>
<br><br>

<br><br>----------------------------------<br><br>

<h3><center><b><u>Tag : <i>IFrame</i></u></b></center></h3>

<br>

<iframe width="30%" height="200" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" 
	src="https://goo.gl/maps/dF3JcJon4u5EenZ26"> 
</iframe>

<br><br>
<<!--><!-->iframe width="420" height="315"
	src="https://www.youtube.com/embed/tgbNymZ7vqY">
<<!--><!-->/iframe><br>
<iframe width="420" height="315"
	src="https://www.youtube.com/embed/tgbNymZ7vqY">
</iframe>

<br><br>----------------------------------<br><br>

<h3><center><b><u>Tag : <i>DIV and span</i></u></b></center></h3>

<br>
<<!--><!-->div> tag is a paired block level tag which means it took complete block of that line.<br>It works in row, but to use it in column we need to use CSS. <br> It is used to created different sections indise webpage, hence named division tag.<br> It is like a container to group different tags.
<br><br>
<<!--><!-->div><br>
	Hello div 1<br>
<<!--><!-->/div><br>
<<!--><!-->div><br>
	Hello div 2, it will come in next line not the same line.<br>
<<!--><!-->/div><br>
*****************
<div>
	Hello div 1
</div>
<div>
	Hello div 2, it will come in next line not the same line.
</div>
<br>******<<!--><!-->div> tag without CSS *******
<br> 
<<!--><!-->div><br> 
	<<!--><!-->div><br> 
		<<!--><!-->div><br> 
			Home<br> 
		<<!--><!-->/div><br> 	
		<<!--><!-->div><br> 
			About<br> 
		<<!--><!-->/div><br> 	
	<<!--><!-->/div><br> 				
	<<!--><!-->div><br> 
		<<!--><!-->div><br> 
			Contact Us<br> 
		<<!--><!-->/div><br> 	
		<<!--><!-->div><br> 
			Carrier<br> 
		<<!--><!-->/div><br> 	
	<<!--><!-->/div><br> 			
<<!--><!-->/div><br> 
**************<br> 
<div>
	<div>
		<div>
			Home
		</div>	
		<div>
			About
		</div>	
	</div>				
	<div>
		<div>
			Contact Us
		</div>	
		<div>
			Carrier
		</div>	
	</div>			
</div>		
		
		
		
<br><br>
<<!--><!-->span> tag is used to reduce code length if we want to apply same style on mutliple lines. we can write contenet inside a <<!--><!-->span> paired tag and in <<!--><!-->header> section we can use css to provide style to aal the contents written in span.

<br><br>----------------------------------<br><br>

<h3><center><b><u><i>Audio and Vedio</i></u></b></center></h3>

<br>
<br><br>----------------------------------<br><br>

<h3><center><b><u><i>Deprecated tags</i></u></b></center></h3>

<br>
<br><br>----------------------------------<br><br>

<h3><center><b><u><i>Semantic tags</i></u></b></center></h3>

<br>
<br><br>----------------------------------<br><br>

<h3><center><b><u><i>Article</i></u></b></center></h3>

<br>
<br><br>----------------------------------<br><br>

<h3><center><b><u><i>Aside</i></u></b></center></h3>

<br>
<br><br>----------------------------------<br><br>

<h3><center><b><u><i>Local Storage</i></u></b></center></h3>

<br>
<br><br>----------------------------------<br><br>

<h3><center><b><u><i>Session Storage</i></u></b></center></h3>

<br>
<br><br>----------------------------------<br><br>

<h3><center><b><u><i>Progress</i></u></b></center></h3>

<br>
<br><br>----------------------------------<br><br>

<h3><center><b><u><i>Web workers</i></u></b></center></h3>

<br>

<br><br>----------------------------------<br><br>

<h3><center><b><u><i>Details and Summary</i></u></b></center></h3>

<br>
</body>
<HTML>
