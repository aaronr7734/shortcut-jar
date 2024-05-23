---
title: Describe Images: AI-Powered Image Descriptions

---

# Describe Images: AI-Powered Image Descriptions

## Table of Contents

- [Quick-start](#quick-start)
- [What are Apple Shortcuts?](#what-are-apple-shortcuts)
- [Why use my shortcuts instead of Be My Eyes?](#why-use-my-shortcuts-instead-of-be-my-eyes)
- [Can Sighted People Use This?](#can-sighted-people-use-this)
- [Getting Started And Some Prerequisites](#getting-started-and-some-prerequisites)
  - [OpenAI Account Setup](#openai-account-setup)
  - [Install the Shortcuts App](#install-the-shortcuts-app)
  - [Install the shortcuts themselves](#install-the-shortcuts-themselves)
- [Using the Shortcuts](#using-the-shortcuts)
  - [Using Describe Photo](#using-describe-photo)
  - [Using Describe Screenshot](#using-describe-screenshot)
- [Changing your answers to set up questions](#changing-your-answers-to-set-up-questions)
- [Changelog](#changelog)
- [Updating The Shortcuts](#updating-the-shortcuts)
- [Thanks](#thanks)

## Quick-start

Already know what you're doing and would rather not read through this whole document? no worries! I won't get in your way!

- [Download Describe Screenshot](https://www.icloud.com/shortcuts/eca5fc921a14481295f0fef3b4617e2c)
- [Download Describe Photo](https://www.icloud.com/shortcuts/365c2cabdec548d293073c2652236c38)

Just here to check for updates? [Jump Straight To The Changelog!](#changelog)

If you do have any questions down the road though, please start with this document. I've done my best to answer as much as I could and it's all organized into sections.

## What are Apple Shortcuts?

Shortcuts are powerful automation tools built into Apple products, including iPhones, iPads, and Macs. They allow users to create custom workflows and mini-programs that can be triggered by various methods, such as tapping an icon, using Siri, or even assigning them to accessibility features like VoiceOver gestures or the Action Button on the iPhone 15 Pro.

## Why use my shortcuts instead of Be My Eyes?

Though Be My Eyes is an excellent free service that already exists to provide visual assistance to blind people, there are several reasons why you might prefer to use these shortcuts:

1. **Gesture and Keyboard Assignment**: As mentioned earlier, these shortcuts can be assigned to a VoiceOver gesture, Voice Control command, or keyboard shortcut on your Apple device. This allows for quick and easy access to the feature without needing to navigate to a separate app or service.

2. **macOS Compatibility**: Be My Eyes was written for iOS and does not work on macOS. In contrast, these Shortcuts are designed to work seamlessly on both iOS/iPadOS and macOS, providing a consistent experience across all your Apple devices. In fact, the Describe Photo shortcut will even work on Apple Vision Pro if you have enough money to shell out on one of those!

3. **Data Privacy**: While Be My Eyes is a trustworthy company, using the Describe Images Shortcuts allows you to communicate directly with the AI service (OpenAI) without involving a third party. This means that your data is only shared between you and OpenAI, reducing the number of entities that have access to your information.

4. **Processing Multiple Images at once**: With Describe Photos, you're able to share multiple images from your photo library in one message.  Got some vacation photos you'd like described together? This can handle that!

5. **Greater Control and Customization**: The Shortcuts offer more control over your interactions with the AI. For example, you can customize the AI's writing style, language, and other advanced parameters to better suit your needs and preferences. This level of customization is not available with Be My Eyes.

On the other hand, using these Shortcuts is not free. Images will cost you around 1 cent per description, so if this is a concern for you, stick with Be My Eyes.

## Can Sighted People Use This?

Absolutely! While the documentation is written with VoiceOver users in mind, sighted users can easily customize the shortcuts to fit their needs. For example, you can adjust the AI prompt to add a personal touch, like describing memes in a snarky tone.

Only download Describe Photos though, as it's the only shortcut that works with the share sheet. During setup, pay special attention to the last two questions. These will undo some VoiceOver-specific changes, making the shortcuts easier for sighted users to use.

## Getting Started And Some Prerequisites

Before using either shortcut, you must first do the following:

### OpenAI Account Setup

If you already have an account set up with OpenAI and already have an API key you can use, feel free to skip this section.

1. Create an OpenAI account at [platform.openai.com](https://platform.openai.com). If you have a ChatGPT account, you can sign in with the same email address and password.

2. Add a payment method and create a billing agreement at [platform.openai.com/account/billing](https://platform.openai.com/account/billing).
   The minimum amount you can add to your account is $5, which should last for many descriptions (each description costs around 2 cents).
   Keep in mind that the form where you fill in your credit card details will automatically advance you to the next field after the one you're in has been filled.
   For example: If you're on the cvv field, you'll be pushed to the next field after typing the three numbers without having to hit tab.

3. Generate an API key at [platform.openai.com/api-keys](https://platform.openai.com/api-keys). Give the key a name, click "Create," and copy the generated key to a safe place. Do not share this key with anyone.

### Install the Shortcuts App

This one doesn't really need a section of its own, especially because the Shortcuts app comes preinstalled on most devices, but just make sure you have it. If you don't, it's free on the app store.

### Install the shortcuts themselves

There are currently two Shortcuts. Both will be described and are accompanied by download links. You'll want to click on the download links with a device that already has the Shortcuts app installed. Clicking the link from Google Chrome on your windows laptop unfortunately won't work.

After clicking the link, you'll be asked if you want to add them to Shortcuts. After adding them, you'll be walked through a bunch of set up questions.\
If you're already sick of setting things up, no worries! The only required question is the first one which asks for your API key. Fill that in then press "Skip setup." You can always come back to the other questions later.

#### Describe Screenshot

Describe Screenshot allows you to take a screenshot on your iPhone, iPad, or Mac and within about 10 seconds, get a detailed description of its contents. This shortcut is particularly useful for VoiceOver users who may not be able to see the content of UI elements in inaccessible apps or games.

Download Link: [Describe Screenshot](https://www.icloud.com/shortcuts/eca5fc921a14481295f0fef3b4617e2c)

#### Describe Photo

Describe Photo works similarly to Describe Screenshot, but it allows you to either:

1. Take a photo within the shortcut
2. Share one or more photos with the shortcut with the share sheet (iOS, iPad OS and Vision OS) or quick actions (macOS.)
3. Grab the most recent photo from your camera roll, intended for Apple Vision Pro and other glasses or headsets.

Download Link: [Describe Photo](https://www.icloud.com/shortcuts/365c2cabdec548d293073c2652236c38)

### Integrate the shortcuts with VoiceOver

These instructions will walk you through assigning a gesture or keyboard shortcut for VoiceOver on both iOS and macOS. The process for both shortcuts is identical, so I'll only be walking you through assigning gestures / keyboard shortcuts for Describe Photo.

#### Assigning a VoiceOver Gesture on iOS

To assign a VoiceOver gesture to the Describe Photo shortcut on iOS:

1. Open the Settings app on your device.
2. Tap on "Accessibility."
3. Tap on "VoiceOver."
4. Tap on "Commands."
5. Tap on "All Commands."
6. Tap on "Shortcuts."
7. you'll be asked if you want to add either a touch gesture or keyboard shortcut, just hit the "add" button for which ever you want.
8. Choose the touch gesture or keyboard shortcut you'd like to use.

That's it! Just use that gesture whenever you want to take a picture and the shortcut will activate!

#### Assigning a Keyboard Shortcut on macOS

You can assign the Describe Photo shortcut to any of the VoiceOver commanders (Keyboard, Trackpad, or Numpad). The following instructions demonstrate how to assign it to the Keyboard Commander (accessed by pressing Right Option + Shift + r), but the process is similar for other commanders.

1. Press VO + F8 to open the VoiceOver Utility.
2. Navigate to the Commanders section in the table or press Command + 8 to move there directly.
3. Press on the Keyboard Commander tab.
4. Hit VO + Right Arrow until you reach the Add button, then press it.
5. In the text field, type the letter "R" and press Enter.
6. Press VO + Right Arrow to navigate to the menu button and activate it.
7. In the menu, use the Up Arrow to select "Custom Commands," then press Right Arrow to expand the submenu and navigate to "Run Shortcut." Press Enter.
8. VoiceOver has a bug where it doesn't recognize the table correctly at first. Stop interacting with the table and re-interact with it to resolve this issue.
9. Once you re-interact with the table, find the Describe Screenshots shortcut in the list and press Enter to select it.

Now, whenever you press Right Option + R, the shortcut will run.

## Using the Shortcuts

Both shortcuts are nearly identical in their usage but I'm including separate sections for each in case a reader may only care about one shortcut.

### Using Describe Photo

On iOS:

1. Use the assigned gesture or keyboard shortcut to activate the shortcut.
2. You'll be prompted to take a photo, go ahead and do so. then tap "use photo" when you're satisfied with what you took. A text box will appear asking you to include an optional question.
3. Tap "Done" or press Enter on the question field.
4. The image and optional question will be sent to OpenAI for processing. The description should be returned within 10-15 seconds as an alert covering the top of the screen.
5. The alert will display the cost of the description and provide two buttons: "Cancel" and "Okay."
   - Press "Cancel" if you're done with the shortcut.
   - Press "Okay" to reply to the AI. Note that replying will cost more because the entire conversation history is sent and processed each time.

The functionality on macOS is identical to that on iOS. The cursor will automatically be placed in the message box, and you can press enter to send your message. When the description comes back, VoiceOver should automatically place focus on the alert.

#### What about on Apple Vision Pro or other headsets or glasses?

If the shortcut detects it is being run on an Apple Vision Pro, it will grab the most recently taken photo from your camera roll rather than taking one on the spot, because Shortcuts on Vision Pro does not support the take photos action.

If you are not using a Vision Pro but prefer this behavior, the fifth set up question has you covered. Simply remove the "y" from that text box and the shortcut will grab the last photo from your camera roll no matter what device you're using. This is useful if you're using smart glasses to take photos, or if you just prefer the enhanced functionality of the photos app.

#### Saving The Picture

When in the reply field, you can enter the command `/save` to save the photo to the album you chose during the shortcut setup. If you didn't specify an album, the photo will be saved to the Recents album. You can enter this command anywhere in the text field, including in the middle of a reply. If you type it in the text box by itself, when you hit done, the photo will be saved and the shortcut will stop. This way you don't have to actually reply to save your photo.

**Note**: This command does not work in your original message, only once you hit "okay" on your first description and are presented with the reply box.

#### Adding Additional Photos

Sometimes, you may want to take a second picture to include with a reply, for example, if GPT-4 had trouble interpreting the first image you sent. to do so, type `/add` anywhere in a reply. Once you finish typing the rest of your reply and hit "done," you'll be prompted to take the next photo.

**Notes**:

1. Similar to the `/save` command, this does not work in your original message.
2. If `/save` and `/add` are put in the same reply, the last photo taken and thus the most recent photo described will be saved, then the new photo will be taken. if you want that one saved, you'll have to type `/save` in your next reply.
3. If the shortcut is grabbing the last photo from the camera roll, `/add` will still work. Just remember to take a new photo before using the `/add` command or you'll upload the same photo as before.

#### Using the share sheet or Mac OS Quick Actions

Once installed, this shortcut will accept photos from the share sheet or macOS quick actions. You can share more than one image at once, if you'd like.

To use Quick Actions on macOS, you need to first enable the Describe Photo extension in System Settings.

To do this, do the following:

1. In Finder, press VO+Shift+m on any image.
2. Navigate to Quick Actions in the menu that appears, then hit the right arrow key to open it.
3. Press customize. This should open System Settings and put you in the list of extensions that can be used as quick actions.
4. Select Describe Photo.

and that's it! Now when you hit VO+Shift+M on an image in Finder, the quick actions menu will now show Describe Photo.

#### Having Long Chats

If you intend to have long chats (more than 3-5 messages) on iOS you should do the following:

1. Open the settings app
2. Tap "Shortcuts"
3. Tap "advanced"
4. Enable "Allow Sharing Large Amounts Of Data"

If you don't enable that setting, the Shortcuts app will stop the shortcut after a few messages because it will think you're sending large amounts of data.

### Using Describe Screenshot

On iOS:

1. Ensure that screen curtain is off.
2. Use the assigned gesture or keyboard shortcut to activate the shortcut.
3. A screenshot will be taken, and you'll be placed in a text box where you can optionally ask a question to include with the screenshot.
4. Tap "Done" or press Enter on the question field.
5. The image and optional question will be sent to OpenAI for processing. The description should be returned within 10-15 seconds as an alert covering the top of the screen.
6. The alert will display the cost of the description and provide two buttons: "Cancel" and "Okay."
   - Press "Cancel" if you're done with the shortcut.
   - Press "Okay" to reply to the AI. Note that replying will cost more because the entire conversation history is sent and processed each time.

The functionality on macOS is identical to that on iOS. The cursor will automatically be placed in the message box, and you can press enter to send your message. When the description comes back, VoiceOver should automatically place focus on the alert.

#### Saving The Screenshot

When in the reply field, you can enter the command `/save` to save the screenshot to the album you chose during the shortcut setup. If you didn't specify an album, the screenshot will be saved to the Recents album. You can enter this command anywhere in the text field, including in the middle of a reply. If you type it in the text box by itself, when you hit done, the screenshot will be saved and the shortcut will stop. This way you don't have to actually reply to save your screenshot.

## Changing your answers to set up questions

If you would like to change some of your answers to the set up questions, do the following:

### On iOS

1. Open the Shortcuts app.
2. Find the shortcut you'd like to edit. You may have to hit the back button and tap on "all shortcuts" before it shows up.
3. Once you've found the shortcut, use the actions rotor (swipe up and down) and double tap on "edit"
4. Tap "Info" on the bottom of your screen. It should be between "Redo" and "share."
5. At the top of the info screen, you should see three tabs going left to right. Tap on Setup, which should be the third tab (furthest on the right.)
6. Tap the "customize Shortcut" button, which should be near the top center of your screen.
   From here, you should be able to adjust your answers to questions.

   **Note**: Some fields, like your API key field will appear blank in this set up screen. You don't have to fill them in again as long as you've filled them in before.

### On macOS

1. Open the Shortcuts app
2. Navigate to your Shortcuts list. VoiceOver will read it as "Collection"
3. Interact with this collection and find the shortcut you want to edit.
4. press vo+shift+m on the shortcut, and choose "edit"
5. Navigate to and interact with the toolbar, then press "Shortcut Details"
6. stop interacting with the toolbar, then VO+Right Arrow until you reach "details group."
7. Interact with this details group, then press the "setup" radio button.
8. Now the "customize Shortcut" button should appear. VO+Right arrow a couple times till you find it and press it.
9. Edit these fields as needed, then stop interacting with the scroll area and hit the "done" button.

**Note**: Some fields, like your API key field will appear blank in this set up screen. You don't have to fill them in again as long as you've filled them in before.

## Changelog

All changes to each Shortcut will be documented here.

### 2024-05-22

Download Links:
- [Download Describe Screenshot](https://www.icloud.com/shortcuts/eca5fc921a14481295f0fef3b4617e2c)
- [Download Describe Photo](https://www.icloud.com/shortcuts/365c2cabdec548d293073c2652236c38)

#### Smarter and quicker AI responses!

Both Shortcuts are now powered by OpenAI's new GPT-4o model. This model is  quicker and more accurate than the previous GPT-4 model, and is also 50% cheaper. Your descriptions should now cost around 1 cent, sometimes less!

#### Share Multiple Images

The Describe Photo shortcut will now allow you to share multiple images through the share sheet or Finder. Got vacation photos you want described all at once? We've got you covered! Can also come in handy when comparing images. Generating AI art just got a lot easier!

#### Where'd my description go?

There's a really annoying issue with the Show Alert action these Shortcuts use to display descriptions. If the description is too long, the text visually cuts off and there's no way to read the rest. It doesn't affect us blind folks, but if you're sighted, you were out of luck!

Now, both Shortcuts will ask you, as part of their set up questions, if you're sighted. If you indicate that you are, descriptions will be shown with a different box that will comfortably hold the entire description. 

## Updating The Shortcuts

If you have an old version of either shortcut and would like to update to the latest version, the process is identical on iOS and macOS. Do the following:

1. Click on the link to the shortcut you'd like to update.
2. The Shortcuts app should open and show you the name and details for the Shortcut you clicked on.  Tap Set Up Shortcut.
3. You'll be asked the set up questions again. The only question you should have to answer again is the first one, which asks for your API key. Fill that in, then press "Skip setup."

That's it! You're now running the latest version of the shortcut. You don't need to set up VoiceOver again.

**Note**: If you adjusted other fields like the system prompt, you might have to adjust them again after updating. For this reason, I'd suggest saving prompts you write elsewhere in case an update clears them.

## Thanks

Thanks for checking out my Shortcuts and for reading to the end of this massive document!

I hope you find them useful. If you do, share them with your friends! AI tools like this might be the future of assistive tech, and now is the best time to start learning how to use them!

[Back To Home](index.md)