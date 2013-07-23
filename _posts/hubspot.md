---
title: Integrate HubSpot and Wistia
layout: post
description: 
  HubSpot is a suite of popular marketing tools for driving more leads and better engagment. See how Wistia works with HubSpot to give it special powers!
category: integrations
---

[HubSpot](http://hubspot.com) is marketing software designed to help increase
leads and drive better engagement. They are the masters of inbound
marketing...heck, they *invented* it!

HubSpot and Wistia work together through a [Wistia Turnstile]({{ '/turnstile' | post_url }})
integration. Read on to learn how to get it set up.

## Setting Up Turnstile

The first step is to get your HubSpot account connected and authorized in
Wistia. While a short tutorial on this follows, the more in-depth guide is on
the [turnstile doc page]({{ '/turnstile' | post_url }})

{% post_image hashed_id: "d6166e343c3cebdda782d3b8a8370a8d782d9a90", class: 'center' %}

Open your [Account Dashboard]({{ '/account-setup#open_your_account_dashboard' | post_url }}),
and select *Setup An Email Provider*.

{{ "Just as a reminder, only the Account Owner can open the Dashboard" | note }}

{% post_image hashed_id: "1a41347bfeb5390f3ed666167b39b751e565fe2b", class: 'center' %}

Select HubSpot from the list, and then click <span class='faux_button'>Configure</span>.

{% post_image hashed_id: '', class: 'center' %} #HUB_ID

For HubSpot configuration, you will need your *Hub ID*, *username*, and
*password*. Your *Hub ID* can be found in the lower-right-hand corner of any
page in your HubSpot account (see [this HubSpot doc](http://help.hubspot.com/articles/How_To_Doc/How-to-find-your-hub-id) for more).

Once you've entered all your HubSpot info and configured it, you are ready to
use the HubSpot Turnstile with your next Wistia video (look for it under
*Turnstile Email Capture*).

## Setting up Bonus JavaScript

For folks that also build their webpages using HubSpot, we've worked
with the HubSpot team to develop some pretty powerful javascript. This will
allow you to pass viewing analytics into HubSpot.

The JavaScript snippet will be added to the *Site Footer HTML* in your HubSpot
Account.

{% post_image hashed_id: '', class: 'center' %} #CONTENT_SETTINGS

Open the Content > Content Settings area in your account. 

{% post_image hashed_id: '', class: 'center' %} #post_footer

Add the JavaScript to the *Site Footer HTML* area, as shown in the image below.

For easy copying, here is the HubSpot integration JavaScript:

<code class="full_width"><script src="//fast.wistia.com/static/integrations-hubspot-v1.js" async></script></code>

## Tracking Form Submissions in HubSpot