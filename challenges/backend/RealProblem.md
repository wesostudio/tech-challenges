# Weso Studio | Real Technical Situation

You can pick one of the challenges and try to finish it with 3-4 days.

Please organize, design, test, document and deploy your code as if it were
going into production, then send us a link to the hosted repository (e.g.
Github, Bitbucket, Gitlab).

## Functional spec

Prototype **one** of the following projects:

1. Exchange Rate
2. SF Movies
3. Email Service API

The UX/UI is totally up to you. If you like, get creative and add additional
features a user might find useful!

### Exchange Rate

Create a service that gives the latest and historical exchange rate for the currency.
Please use three tier network architecture in this challenge.
You can also consider using pub / sub, worker mode to process the request to make it more scalable.

Here are some examples of freely available data:

- [openexchangerates.org](https://openexchangerates.org/)

### SF Movies

Create a service that shows on a map where movies have been filmed in San
Francisco. The user should be able to filter the view using autocompletion
search.

The data is available on [DataSF](http://www.datasf.org/): [Film
Locations](https://data.sfgov.org/Arts-Culture-and-Recreation-/Film-Locations-in-San-Francisco/yitu-d5am).

### Email Service API

1. Create an email npm package, which can be open source and reuseable in any other services.

   The package should provide an abstraction between multiple email service providers.

   If one of the services goes down, it can quickly failover to a another provider without affecting your customers.

2. Create a RESTful API that accepts the necessary information and sends emails via the created npm package, if you like, you can build an UI to use that RESTful API.

Example Email Providers:

- [SendGrid](https://sendgrid.com/user/signup) - [Simple Send Documentation](https://sendgrid.com/docs/API_Reference/Web_API/mail.html)
- [Mailgun](http://www.mailgun.com) - [Simple Send Documentation](http://documentation.mailgun.com/quickstart.html#sending-messages)
- [Mandrill](https://mandrillapp.com) - [Simple Send Documentation](https://mandrillapp.com/api/docs/messages.JSON.html#method-send)
- [Amazon SES](http://aws.amazon.com/ses/) - [Simple Send Documentation](http://docs.aws.amazon.com/ses/latest/APIReference/API_SendEmail.html)

All listed services are free to try and are pretty painless to sign up for, so
please register your own test accounts on each.

### Back-end

We believe there is no one-size-fits-all technology. Good engineering is about
using the right tool for the right job, and constantly learning about them.
Therefore, feel free to mention in your `README` how much experience you have
with the technical stack you choose, we will take note of that when reviewing
your challenge.

Here are some technologies we are more familiar with.
Unless request by us, you can chooose any language to work on the challenge.

- Node
- PHP
- Java
- Go
- Rust
- Python

You are also free to use any web framework.

### Front-end

The front-end should ideally be a single page app with a single `index.html`
linking to external JS/CSS/etc. You may take this opportunity to demonstrate
your CSS3 or HTML5 knowledge.

BTW, we like React!

## Host it!

When you’re done, if you want, host it somewhere (e.g. on Amazon EC2, Heroku, Google AppEngine, Vercel, Netlify, etc.).