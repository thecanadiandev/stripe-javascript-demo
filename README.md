### Stripe javascript payment demo

All we need to do is 

#### Step 1

- download the source code 
- create a stripe account & provide card details if you havent
- make sure we are in test mode
- get the keys and use in env file  (STRIPE_PUBLISHABLE_KEY & STRIPE_SECRET_KEY)
- Download and setup [Stripe CLI](https://docs.stripe.com/stripe-cli) 
- copy the executable to `/usr/local/bin` and expand the 
- Trouble shooting on [MAC](https://www.lifewire.com/fix-developer-cannot-be-verified-error-5183898)

#### Step 2

- `stripe login`
- Will get a pairing code and copy the webhook secret to env file 
- Dummy credit card details [here](https://docs.stripe.com/testing)
- Add a test product and use the key in the code 
- Once submitted, see the hono console.
- Should see a session completed and a 200 POST 
- Check Stripe dashboard for the sample payment. 