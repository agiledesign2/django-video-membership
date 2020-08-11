# A simple video membership website built with Django.

This project shows how to create a video membership website using Django and Stripe billing.

## Getting Started

Create a stripe account and put your stripe publishable key and secret key inside `settings.py` as well as your publishable key inside `checkout.js` in the static folder. Follow the [Demo Site](https://base-blog.herokuapp.com/) for guidance.

**Note** that you will need to create your own Stripe plans in your dashboard and link those plan ID's in your Django admin.

[![alt text](https://github.com/agiledesign2/django-video-membership/blob/master/thumbnail.png "Logo")](https://base-blog.herokuapp.com/)

## Latest update of the code

Stripe changed their API to no longer allow a source being passed into a subscription. The code has been updated to now correctly bill a customer.

## Where to find us

Like us on [Linkedin](www.linkedin.com/in/agiledesign2)

Follow us on [Twitter](https://twitter.com/pythondesign1)

Subscribe to our [Demo Site](https://base-blog.herokuapp.com/)

Or visit our [Website](https://agiledesign2.github.io/)