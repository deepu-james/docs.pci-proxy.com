---
description: Use PCI Proxy as a standalone authentication service for 3D Secure v1 and v2.
---

# 3D Secure v1 / v2

Secure Fields _Authentication Only_ integration allows you to securely collect sensitive card data \(card number and CVV code\) by injecting iframes to your DOM and perform an _Authentication Only_ call to validate a cardholder via 3D Secure v1 and v2. Decoupling _Authentication_ from _Authorization_ enables you to forward 3D data to an independent 3rd party payment provider. 

{% hint style="success" %}
A 3D Secure transaction can go either through a challenge or a frictionless flow. In case the issuer does not support 3D Secure 2 we automatically apply a fallback to 3D Secure 1.
{% endhint %}

If you decide to do Authorization with Datatrans payment gateway please continue with sending payment request to our [Authorize](authorize-1/) API after authentication is finished. 

{% hint style="success" %}
**Using Secure Fields qualifies you for SAQ A.**
{% endhint %}

If your business is located outside the European Economic Area \(EEA\) or if you don't need to apply 3D Secure process for another reason please go with our default [Secure Fields ](../collect-and-store-cards/capture-iframes/)implementation. 

{% hint style="info" %}
You are a PCI Level 1 compliant company, running a native mobile application or simply want to separate card capturing and authentication flow? 

That's solved as well. Just have a look at our [Server-to-Server based approach](authentication-only/api-beta.md). 
{% endhint %}



