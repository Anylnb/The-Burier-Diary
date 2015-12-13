The Burier Diary uses following open sourse code

# [Start Bootstrap](http://startbootstrap.com/) - [Clean Blog](http://startbootstrap.com/template-overviews/clean-blog/)

[Clean Blog](http://startbootstrap.com/template-overviews/clean-blog/) is a stylish, responsive blog theme for [Bootstrap](http://getbootstrap.com/) created by [Start Bootstrap](http://startbootstrap.com/). This theme features a blog homepage, about page, contact page, and an example post page along with a working PHP contact form.

## Getting Started

The Burier Diary helps users to store their diaries. The Burier Diary is intended to be a unique combination between a time capsule and a diary. Our product will allow users to write entries and submit them. Then after submission they will be stored away, inaccessible until a predetermined period of time, at which point the user can review them is desired. 

index.html: login page, type user name password, click on "login" direct to home.html, click upper right corner "New User? Register" direct to register.html.

register.html: signup page, type email (used to identify user), password, confirm password, display name, click on "register" direct to home.html

home.html: home page (user front page), header to access different functionalities. 
	Header: 
		home: link to home.html, can be accessed any page except index.html and register.html
		new entry: link to new_entry.html
		message: dropdown menu, click on message link to post.html to view message
		username (Maddie): dropdown, click "my entry" to my_entry.html, "following list" to follow.html, "setting" to setting.html
		exit icon: back to index.html
	"Learn More" button under welcome: about.html, introduces burier diary
	Main content:
		list of posts made by different users
		click on post to view the post (post.html or post_photo.html)
		click on username to view user info (account_info.html)

new_entry.html/new_entry_photo.html: typing interface, two types of entry: text and photo. Click on "photo diary", "text diary" to change between photo and text diary. Photo diary enables you to upload photo for diary. Type in title, diary content, choose to put to a diary book, and set the privacy of the diary, then click "submit" to home.html (if backend fully implemented, diary will be shown up in the home.html)

post.html/post_photo.html: view the post and comment

my_entry.thml: three parts
	top: shows graphs for mood detection
	middle: shows today's entry, you can edit (edit_post.html/ edit_post_photo.html) or delete the entry
	buttom: shows diary book, can click "add" button to add_diarybook.html. or click on diarybook with "available status" to view contents in the diarybook (diarybook.html)

diarybook.html: two parts
	top: calender shows the date of diary written, highlighted for the date of diary currently view
	buttom: edit/delte diarybook, show diary of the date highlighted, click to view entire post

	






