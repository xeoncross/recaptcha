ReCaptcha Class

Because it is often easier to work with classes I ported the recaptchalib functions to a class form. This will make autoloading much easier within frameworks. Every attempt was made to keep the functions exactly as they are.

<?php

//Include class
include('classes/recaptcha.php');

// Call method
recaptcha::get_html($public_key);