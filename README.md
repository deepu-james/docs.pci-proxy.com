# Welcome to PCI Proxy

Here you will find information on how to integrate with and use the PCI Proxy. We have tried to make the documentations as simple and example-filled as possible, just check it out !

## Overview

Before we get started, take a minute and let us introduce you to the magic of PCI Proxy.

PCI Proxy is a tokenization service that allows you to reduce your PCI scope in a simple kind of way.

Our webservice API securely **extracts credit cards out of any XML/SOAP/JSON calls. ** Thereby, your requests and responses remain unchanged. Means, we leave you complete control over your processes. _For instance, you receive XML reservation data from _[_Booking.com_](http://www.booking.com/)_ or other third party systems that contain credit cards, our webservice API filters the card data and replaces them with a token. The rest of the response will remain unchanged, whit the small difference, that there will be a token instead of a real card number. _Same procedure if you use our payment page APIs that will let you **collect payment data on websites or mobile apps**.

By using tokenization, our APIs ensure **sensitive payment data never touch your systems**. Tokens can be used like normal credit cards. You can validate, forward or charge them. Our APIs detokenize them automatically for processing.

### Overview of major features: Collect, Validate, Use.

| [**Collect**](collect_payment_data.html) | [**Validate**](validate.html) | [**Utilize**](utilize) |
| --- | --- | --- |
| From [Web Service](webservice.html) | [Credit Card Check](validate.html) | [Forward](forward.html) |
| From [Website / Application](website-application.html) |  | [Charge](charge.html) |
| From [Mobile App](mobile-app.html) |  | [Show](show.html) |

## Quick Start

If you are just getting started with PCI Proxy, it is highly recommended that you start with the get started guide first.

1. [Sign up](https://www.pci-proxy.com/#/signup) for a free test account.
2. [Choose API](collect_payment_data.html) to collect or extract payment data.
3. Explore features, e.g. [validate](validate.html), [charge](charge.html), [forward](forward.html) or [display](retrieve.html) payment data.
4. After successful testing, [activate your account](live_mode-test.html) and reduce your PCI scope.

_Before you activate your account, you can use PCI Proxy for free in test mode. With the exception that only _[_test credit cards_](live_mode-test.html)_ can be used, all PCI Proxy features are fully available in test mode._

