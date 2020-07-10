+++
fragment = "contact"
#disabled = true
date = "2017-09-10"
weight = 1100
#background = "light"
form_name = "defaultContact"

title = "Get in touch"
subtitle  = "Send us a message, and we'll get back to you"

# PostURL can be used with backends such as mailout from caddy
post_url = "https://example.com/mailout" #default: formspree.io
email = "service@blorenge.co.uk"
button = "Send Button" # defaults to theme default
netlify = true

# Optional google captcha
#[recaptcha]
#  sitekey = ""

[message]
  success = "Thank you for your enquiry, we will be in touch as soon as possible"
  error = "I'm sorry, there was an error sending that message. Please email service@blorenge.co.uk"

# Only defined fields are shown in contact form
[fields.name]
  text = "Your Name *"
  #error = "" # defaults to theme default

[fields.email]
  text = "Your Email *"
  #error = "" # defaults to theme default

[fields.phone]
  text = "Your Phone *"
  #error = "" # defaults to theme default

[fields.message]
  text = "Your Message *"
  #error = "" # defaults to theme default

# Optional hidden form fields
# Fields "page" and "site" will be autofilled
#[[fields.hidden]]
#  name = "page"

#[[fields.hidden]]
#  name = "someID"
#  value = "example.com"
+++
