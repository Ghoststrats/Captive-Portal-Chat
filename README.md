# GhostStrats Portal Messenger

GhostStrats Portal Messenger is a simple offline HTML portal system for creating custom evil portal message pages without having to edit the code by hand.

This project includes two files:

1. `Portal-Message-Builder.html`  
   This is the builder tool. Use this file to type your custom message and generate a new portal HTML file.

2. `GhostStratsPortalMessenger.html`  
   This is the base portal messenger file. You can use it as a ready made portal page or as the template style for your generated portals.

## How It Works

Start by opening `Portal-Message-Builder.html` in your browser.

Inside the builder, type the message you want to broadcast through the portal. This is the message people will see when they connect to your evil portal.

Once your message is ready, click **Generate Portal File**.

The builder will create a new HTML file for you. Upload that generated file to your device and use it as the HTML page for your evil portal.

When someone connects to the portal, they will see your custom message. They will also have one message box where they can type a response and send it back.

If the device or firmware you are using supports receiving messages through the `/message` endpoint, the response can show up on your device.

## Basic Workflow

1. Open `Portal-Message-Builder.html`
2. Type the message you want the portal to broadcast
3. Click **Generate Portal File**
4. Upload the generated HTML file to your evil portal device
5. Use that file as the portal page
6. Wait for someone to connect
7. They read your message and send one response
8. Their response can appear on your device if supported by your firmware

## Files Included

### `Portal-Message-Builder.html`

Use this file first.

This lets you build a custom portal by typing your message into a simple form. When you click generate, it creates a ready to upload HTML portal file.

### `GhostStratsPortalMessenger.html`

This is the base portal messenger page.

You can use it directly, edit it manually, or use the builder to generate customized versions.

## Notes

This is not a secure chat system. It is a simple one message captive portal response page.

The password system from the older version was removed because it was too easy to inspect or bypass from the page source. This version is cleaner and focuses on a simple message broadcast and response flow.

The generated portal is designed for devices and firmware that support evil portals or custom captive portal HTML pages.

Response capture depends on your device or firmware supporting the `/message` route or an equivalent message handling endpoint.

## Use Responsibly

Only use this in controlled environments, on devices and networks you own or have permission to test.

Do not use this to trick people, steal information, capture credentials, or collect private data.

This project is for educational, experimental, and authorized testing only.

## GhostStrats

Safety is an illusion.
