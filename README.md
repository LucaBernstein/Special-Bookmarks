# Special-Bookmarks

## Google Calendar Jitsi Meet link with random characters

```
javascript:(function(){
	var length = 15;
	var characters = '0123456789-_abcdefghijklmnopqrstuvwxyz';
	var result = '';
	for ( var i = 0; i < length; i++ ) {
		result += characters.charAt(Math.floor(Math.random() * characters.length));
	};
	var d=document;
	var el = d.getElementsByClassName("DD3VVc")[1].click();
	var e=d.getElementsByClassName("T2Ybvb KRoqRc editable")[0];
	e.innerText='https://jitsi.mpi-bremen.de/Meeting-'+result;
})();
```

Steps to insert:
* Add a new bookmark entry in Chrome (right click on bookmark bar > `Add page`)
* Give meaningful name
* Enter snippet content as `URL`
* Enjoy (in calendar by creating a new event in the weekly overview just click the button)
