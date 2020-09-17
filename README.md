# Chat Bot



## Context			

The chat bot is a programming software where one can interact with a bot with messages.

### Contacts

The contact element is composed of : 
1. The user profile
2. The other users

#### The user profile : 

The user profile div element contains the image of the user and its name.

		<div class="contacts--profiles">
          <div class="contacts--profiles-avatar">
            <img src="https://ih1.redbubble.net/image.617355277.4370/poster,504x498,f8f8f8-pad,600x600,f8f8f8.u1.jpg" alt="avatar" />
          </div>
          <div class="contacts--profiles-name">
            <span>Tyrion Lannister</span>
          </div>
        </div

#### The other users :

Other users have the same elements as the profile except that they are smaller and they have a message counter.

		<div class="contacts--list-item">
		  	<div class="contacts--list-item-avatar">
		    	<img src="https://tel.img.pmdstatic.net/fit/https.3A.2F.2Fprd2-tel-epg-img.2Es3-eu-west-1.2Eamazonaws.2Ecom.2FproviderPerson.2F70635f1576fb02de.2Ejpeg/300x300/quality/80/sansa-stark.jpeg" alt="avatar" />
		    </div>
		    <div class="contacts--list-item-name">
		      <span>Sansa Stark</span>
		    </div>
		   	<div class="contacts--list-item-counter">
		    	<span>32</span>
		   	</div>
		</div>

### Message Element

The message element is composed of :

1. The messages received and sent

2. The message form with a text input and a send button.


#### Messages sent/received : 

The message are composed of the name, image of the users and message date at the top of the div. At the bottom we have the message sent/received.

	<div class="messages--received">
	  <div class="messages--received-status">
	    <div class="messages--received-status-avatar">
	      <img src="https://tel.img.pmdstatic.net/fit/https.3A.2F.2Fprd2-tel-epg-img.2Es3-eu-west-1.2Eamazonaws.2Ecom.2FproviderPerson.2F70635f1576fb02de.2Ejpeg/300x300/quality/80/sansa-stark.jpeg" alt="avatar" />
	    </div>
	   	<div class="messages--received-status-name">
	      <span>Sansa Stark</span>
	    </div>
	    <div class="messages--received-status-date">
	      <span>16:04:54</span>
	   	</div>
	  </div>
	  <div class="messages--received-text clear">
	    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ac libero eget mi molestie tempus id ac tortor. Pellentesque ullamcorper arcu orci, eu bibendum ligula iaculis et</p>
	  </div>
	</div>

#### The message form 

The message form is simply composed of a text input and button meant to send the message into the message box above.

	<div class="form-message clear">
	  <form>
	  	<input type="submit" value="Envoyer">   
	    	<textarea placeholder="Envoyer un message"></textarea>
	  </form>
	</div>