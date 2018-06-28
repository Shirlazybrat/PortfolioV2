# Personal Portfolio

## I am a Full-Stack Developer with an emphasis in JavaScript


[Alt text](img/portfolioHome.png "Home Page")


### This is my personal portfolio created to showcase my projects, share my contact information and give each visitor insight into who I am and what I do.

Visit here: [Portfolio](http://shirletterly.com/)

## Built with:
	- Html
	- CSS
	- Javascript
	- jQuery 
	- Bootstrap

## Sample Code
### The following code was created with the  use of Bootstrap to allow the visitor to click on a contact button resulting in the dynamic display of a modal where there may enter information to send.

```html
<!-- Modal -->
<div class="modal fade" id="myModal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
	<div class="modal-dialog" role="document">
		<div class="modal-content">
			<div class="modal-header">
				<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
				<h4 class="modal-title" id="myModalLabel">Contact Information</h4>
			</div>
		<div class="modal-body">
			<div class="email row text-center">
				<h3 id="myModalLabel">I'd Love to Hear From You</h3>
			</div>
			<form action="mail.php" method="post">
			<!-- <input type="text" name="fullName" placeholder="Enter Your Name">
	            <input type="email" name="email" placeholder="Enter Your Email"> -->
				<div class="form-group">
					<label for="recipient-name" class="control-label">Full Name:</label>
						<input type="text" class="form-control" id="recipient-name">
				</div>
				<div class="form-group">
					<label for="recipient-email" class="control-label">Email Address:</label>
					<input type="text" name="email" class="form-control" id="recipient-email">
				</div>
				<div class="form-group">
					<label for="message-text" class="control-label">Message:</label>
					<textarea name="body" class="form-control" id="message-text" placeholder="Enter Your Message here"></textarea>
				</div>
				<div class="text-center"><a href="#">Direct email: shirlette.chambers@gmail.com></a></div>
					<button type="submit" class="btn btn-default btn-info send-success">
					<href src="#">Submit</button>
				<div class="span4">
					<div class="alert alert-default fade">
					<button type="button" class="close" data-dismiss="alert">×</button>
					<strong>Success!</strong> You message was sent..
				</div>
		        </div>
			</form>
		</div>
	<div class="modal-footer">
		<button type="button" class="btn btn-default btn-info " data-dismiss="modal">Close</button>
	</div>
	</div>
</div>
</div>
```


#### Early stages of site
[Alt text](img/earlyStage.png "Early stages of site")

<!-- add a video of interaction with the site -->

## Future Add-ons
- Links to more current projects.
- Ability for visitors to send messages directly from the site to me.
- An enhanced UX/UI design that encourages more visitors.


### Please visit my personal profile to see more current projects.
- [Shirlette Chambers](https://github.com/Shirlazybrat)
