---
description: A page explaining how to setup custom bots
---

# Custom bot

First, head on over to the appy dashboard by [clicking here](https://appybot.xyz/dashboard?selected=customInstance)

Once done, you will see the following page. Now its time to start configuring your bot, see below for more details

<figure><img src="../../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>

## Creating the app

First, kick the main Appy bot from your server (don't worry, your server settings wont be deleted). Once done, visit the discord developer page by [clicking here](https://discord.com/developers/applications)

### Click the new application button:

<figure><img src="../../.gitbook/assets/image (5) (1).png" alt=""><figcaption></figcaption></figure>

Fill out the contents of the form and click create:

<figure><img src="../../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

Head on over to the "bot" page and enable the circled intents.

{% hint style="warning" %}
## Important

You must only enable the settings which are circled. If you enable any others you may run into issues.
{% endhint %}

<figure><img src="../../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

## Setting up OAuth callbacks

The next step is to setup the oauth callback so that you can invite the bot to your server. Head on over to the "oauth" page and copy the following url into the redirects box: `https://appy.bot/callback/discord`&#x20;

<figure><img src="../../.gitbook/assets/image (25).png" alt=""><figcaption></figcaption></figure>

## Obtaining the bot token

Head on over to the "bot" tab, and you'll see your token. Copy this and paste it into the appy website

<figure><img src="../../.gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>

Now, go back to appy site and finish the configuration!
