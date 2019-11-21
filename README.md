## Bulk Stripe subscriptions manager

Need to do lots of things in Stripe, like canceling all subscriptions programmatically, and don't want to click each one in the dashboard? This is for you! This simple project makes it easy to bulk-cancel subscriptions and perform other mass actions that aren't possible with the Stripe API today.

**Warning**: Do not use this on a live server! It's intended to be used locally to make your life easier. This app requires no authentication and your API key is hardcoded. ¯\_(ツ)_/¯ 

### What it does
1. Bulk Stripe cancellations (with optional proration)
2. Overview of all Stripe subscribers status
3. Select which subscriptions you want to cancel (coming soon)

### How to use

1. Clone the Git repo
2. Spin up a PHP server, run `composer install`
3. Copy `.env.example` to `.env` and add your Stripe key to `STRIPE_SECRET`. **Warning**: Test the app using your test mode API key first! 
4. Hit the URL of your server and browse to `/customers`
5. Click delete (or don't) at your own risk
