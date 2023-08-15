# Status.cafe CSS

## A fully commented css template for status.cafe profiles

In order to change the styling of your status.cafe page, you need to go to your settings, and in the "About" section, add a ```<style> </style>``` tag under your profile:


![](/profile-ss.png)

*The default style.css from the cafe is located at https://status.cafe/assets/style.css for reference, so you can override anything below.*

````
<style>

/*Importing a custom font*/
@import url(https://fonts.bunny.net/css?family=azeret-mono:400);

/*nav bar */
nav {
	font-family: 'Azeret Mono', monospace;
}


/*main body styling*/
body {
	background-image: url("https://cdn.some.pics/binarydigit/64db7ba89f8a7.png");
	background-repeat: repeat;
	font-family: 'Azeret Mono', monospace;
 	background-color: #fff0f6;
 	color: #D7D7D7;
}

a {
	color: #d633c4;
}
a:visited {
	color: purple;
}
a:hover {
  text-decoration: none;
}

/*H2 is used for the username and "statuses" heading*/
h2 {
	color: #33b0d6;;
}

</style>
```