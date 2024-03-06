<!DOCTYPE html>

 <!-- Fig. 3.1: newforminputtypes.html -->
 <!-- New HTML5 form input types and attributes. -->
 <html>
 <head>
<meta charset="utf-8">
 <title>New HTML5 Input Types</title>
 </head>

 <body>
 <h1>New HTML5 Input Types Demo</h1>
 <p>This form demonstrates the new HTML5 input types
 and the placeholder, required and autofocus attributes.
 </p>

 <form method = "post" action = "http://www.deitel.com">
 <p>
 <label>Color:
    <input type = "color" autofocus />
(Hexadecimal code such as #ADD8E6)
</label>
 </p>
 <p>
 <label>Date:
    <input type = "date" />
(yyyy-mm-dd)
</label>
</p>
<p>
 <label>Datetime:
    <input type = "datetime" />
(yyyy-mm-ddThh:mm+ff:gg, such as 2012-01-27T03:15)
</label>
 </p>
 <p>
 <label>Datetime-local:
    <input type = "datetime-local" />
(yyyy-mm-ddThh:mm, such as 2012-01-27T03:15)
</label>
 </p>
 <p>
 <label>Email:
    <input type = "email" placeholder = "name@domain.com"
required /> (name@domain.com)
</label>
 </p>
 <p>
 <label>Month:
    <input type = "month" /> (yyyy-mm)
</label>
 </p>
 <p>
    <label>Number:
        <input type = "number"
min = "0"
max = "7"
step = "1"
value = "4" />
</label> (Enter a number between 0 and 7)
 </p>
 <p>
 <label>Range:
    0 <input type = "range"
min = "0"
max = "20"
value = "10" /> 20
</label>
 </p>
 <p>
 <label>Search:
    <input type = "search" placeholder = "search query" />
</label> (Enter your search query here.)
 </p>
 <p>
 <label>Tel:
    <input type = "tel" placeholder = "(###) ###-####"
pattern = "\(\d{3}\) +\d{3}-\d{4}" required />
(###) ###-####
</label>
 </p>
 <p>
 <label>Time:
    <input type = "time" /> (hh:mm:ss.ff)
</label>
 </p>
 <p>
 <label>URL:
    <input type = "url"
placeholder = "http://www.domainname.com" />
(http://www.domainname.com)
</label>
</p>
 <p>
 <label>Week:
    <input type = "week" />
(yyyy-Wnn, such as 2012-W01)
</label>
 </p>
 <p>
 <input type = "submit" value = "Submit" />
 <input type = "reset" value = "Clear" />
 </p>
 </form>
 </body>
 </html>
