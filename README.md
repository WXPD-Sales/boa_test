# boa_test

The two entry points/files are:
widget.html
and
sdk.html

* The sdk.html is for the person receiving the incoming call.
* The widget.html file is for the person placing the outgoing call.

 
These files take url parameters, so in your browser:
* /path/to/widget.html?sip=personyouwanttocall@example.com&token=ABCDEFG
* /path/to/sdk.html?token=ZYXWVUT

It is recommended that you use a different token for the caller (widget.html) and the recipient (sdk.html)

Assuming you are using the correct token values (you can pull temporary test tokens from developer.webex.com), you can open the widget.html with the described parameters, and place a call to the person waiting with their token loaded for sdk.html.
