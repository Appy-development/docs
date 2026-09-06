# Applying for intents

### Applying for intents: application form:

## What does your application do? Please be as detailed as possible, and feel free to include links to image or video examples.

This application is a custom (white labelled) instance of appy bot, which provides the user the option to customize the bots appearance. Appy is a multipurpose discord bot that has a wide range of features, including tickets, polls, application forms, reaction roles, sticky messages, user welcomer, and more. This custom instance of this application is hosted by appy.

## Do you have a public Privacy Policy telling your users about their data usage?

Yes

## Where is your Privacy Policy available?

The privacy policy is available on the official appy website: https://appy.bot/privacy-policy

## Please share a link to your Privacy Policy.

https://appy.bot/privacy-policy

## Which intents are you applying for, if any? (Leave blank if you do not need any of these)

* Server members intent
* Message content intent

## Why do you need the Guild Members intent?

Appy relies on the guild members intent for the following features:

* welcome and leave messages - this intent is required to recieve the `GUILD_MEMBER_ADD` and `GUILD_MEMBER_REMOVE` events, which is needed so we can detect when a member joins or leaves so the welcome and leave messages can be sent.
* auto roles - this feature grants a role whenever a member joins a server.
* user verification - when a user joins the server they are given an 'unverified' role, this intent is needed so we can listen to the `GUILD_MEMBER_ADD` event.
* ticket auto closing and application auto denying - these features auto close and deny application submissions when a user leaves the server.

## Please provide links to screenshots and/or videos that demonstrate your use case

This video outlines all of the use cases that appy needs the guild member intent for - https://youtu.be/ycoI8yFIShM

## Are you storing any API Data off-platform (outside of Discord)?

Yes

## Are you storing API Data for 30 days or less?

Yes

## How do users contact you to request deletion of their activity data?

Users can email us at admin@appybot.xyz or join our support server which is listed throughout our website (https://appy.bot): https://discord.gg/JHGsebRA9e

## Are you encrypting the data that you store at rest, as is required by our developer policy?

Yes

## Can users opt-out of having their message content data tracked?

Yes, appy only tracks message content data when the user specifically interacts with the bot.

## Are you storing message content data off-platform (outside of Discord)?

Yes

## Are you storing user message content data for 30 days or less?

Yes

## How do users contact you to request deletion of their activity data?

Users can email us at admin@appybot.xyz or join our support server which is listed throughout our website (https://appy.bot): https://discord.gg/JHGsebRA9e

## Are you encrypting the data that you store at rest, as is required by our developer policy?

Yes

## Will the message content data be used to train machine learning or AI Models?

No

## Why do you need the Message Content intent?

Appy needs the message content intent so that it can send ticket transcripts to users who open and close a ticket. When an appy ticket is closed all of the messages which were sent in the ticket get saved sent to the user, so they can go back and view the ticket. If appy did not have this intent we would not be able to provide this feature.

## Please provide links to screenshots and/or videos that demonstrate your use case

This video outlines all of the usecases that appy needs the message content intent for - https://youtu.be/oJwCdAqacSE
