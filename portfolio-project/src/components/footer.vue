<template>
    <div class="footer-section" id="contact">
			<div class="container"> 
			<div class="contact-header">
				<h3> contact</h3>
					
			</div>
			<div class="social-icon">
				<a href="#"><i class="icon1"></i></a>
				<a href="#"><i class="icon2"></i></a>
				<a href="#"><i class="icon3"></i></a>
				<a href="#"><i class="icon4"></i></a>
				<a href="#"><i class="icon5"></i></a>
				<a href="#"><i class="icon6"></i></a>
				<a href="#"><i class="icon7"></i></a>
				<a href="#"><i class="icon8"></i></a>
			</div>
			<div class="contact">
				<form>
					<div class="col-md-4 contactgrid">
						<input type="text" class="text" value=" name" onfocus="this.value = '';" onblur="if (this.value == '') {this.value = ' name';}">
					</div>
					<div class="col-md-4 contactgrid">
						<input type="text" class="text" value="email" onfocus="this.value = '';" onblur="if (this.value == '') {this.value = 'email';}">
					</div>
					<div class="col-md-4 contactgrid">
						<input type="text" class="text" value="phone" onfocus="this.value = '';" onblur="if (this.value == '') {this.value = 'phone';}">
					</div>
					<div class="col-md-8 contactgrid1">
						<textarea onfocus="if(this.value == 'Your Message') this.value='';" onblur="if(this.value == '') this.value='Your Message';" >Your Message</textarea>
					</div>
					<div class="col-md-4 contactgrid2">
						<input type="submit" value="[send message]">
					</div>
				   <div class="clearfix"></div>
				</form>
			</div>
			<div class="footer-bottom">

				

			</div>
					<script type="text/javascript">
						$(document).ready(function() {
							/*
							var defaults = {
					  			containerID: 'toTop', // fading element id
								containerHoverID: 'toTopHover', // fading element hover id
								scrollSpeed: 1200,
								easingType: 'linear' 
					 		};
							*/
							
							$().UItoTop({ easingType: 'easeOutQuart' });
							
						});
					</script>
				<a href="#" id="toTop" style="display: block;"> <span id="toTopHover" style="opacity: 1;"> </span></a>
</div>
</template>