# Mollie Checkout

Accept one-time payments on WemX through Mollie’s hosted checkout.

## Features

- Redirect the customer to a Mollie checkout page
- Store the Mollie payment id on the WemX payment
- Mark the payment paid when the customer returns and Mollie reports the payment as paid

## Install

Install from the WemX marketplace, or download `MollieCheckout.zip` from a GitHub release and place the `MollieCheckout` folder at `extensions/Gateways/MollieCheckout`. Then enable **Mollie Checkout**.

Publishing a release builds `MollieCheckout.zip`. Unzipping it creates a folder named `MollieCheckout`. GitHub’s own “Source code” archive still unpacks to `gateway-mollie-<tag>`. Use `MollieCheckout.zip`.

## Connection

Add a gateway configuration with your Mollie API key. Use a live key for real charges and a test key while you are testing.
