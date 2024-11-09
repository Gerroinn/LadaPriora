# LadaPriora
izuchaem github
## hello world
![my photo](https://ichef.bbci.co.uk/ace/standard/745/cpsprodpb/048c/live/2bb03f70-1753-11ef-b507-edbcd7518f5c.jpg)
```$('input').on('change', function() {
	let username = $('input').val();
	$.ajax(`https://api.github.com/users/${username}`, {
		success: function(result) {
			$('#results').html(`
				<h3>${result.login}</h3>
				<img src="${result.avatar_url}">
				<a href="${result.html_url}">Link to procile</a>
			`);
	}
})
})```
