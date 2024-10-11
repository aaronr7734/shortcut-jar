---
title: Describe Images: AI-Powered Image Descriptions

---

# Describe Images: AI-Powered Image Descriptions

## Table of Contents

- [Describe Images: AI-Powered Image Descriptions](#describe-images-ai-powered-image-descriptions)
  - [Table of Contents](#table-of-contents)
  - [Quick-start](#quick-start)
  - [What are Apple Shortcuts?](#what-are-apple-shortcuts)
  - [Why use my shortcuts instead of Be My Eyes?](#why-use-my-shortcuts-instead-of-be-my-eyes)
  - [Can Sighted People Use This?](#can-sighted-people-use-this)
  - [Getting Started And Some Prerequisites](#getting-started-and-some-prerequisites)
    - [OpenAI Account Setup](#openai-account-setup)
    - [Install the Shortcuts App](#install-the-shortcuts-app)
    - [Install the shortcuts themselves](#install-the-shortcuts-themselves)
      - [Describe Screenshot](#describe-screenshot)
      - [Describe Photo](#describe-photo)
    - [Integrate the shortcuts with VoiceOver](#integrate-the-shortcuts-with-voiceover)
      - [Assigning a VoiceOver Gesture on iOS](#assigning-a-voiceover-gesture-on-ios)
      - [Assigning a Keyboard Shortcut on macOS](#assigning-a-keyboard-shortcut-on-macos)
        - [Mac OS Sequoia](#mac-os-sequoia)
        - [Mac OS Sonoma or below](#mac-os-sonoma-or-below)
  - [Using the Shortcuts](#using-the-shortcuts)
    - [Using Describe Photo](#using-describe-photo)
      - [What about on Apple Vision Pro or other headsets or glasses?](#what-about-on-apple-vision-pro-or-other-headsets-or-glasses)
      - [Saving The Picture](#saving-the-picture)
      - [Adding Additional Photos](#adding-additional-photos)
      - [Sharing Photos](#sharing-photos)
      - [Describing Photos from share sheet or Mac OS Quick Actions](#describing-photos-from-share-sheet-or-mac-os-quick-actions)
      - [Having Long Chats](#having-long-chats)
    - [Using Describe Screenshot](#using-describe-screenshot)
      - [Saving The Screenshot](#saving-the-screenshot)
      - [Sharing the screenshot](#sharing-the-screenshot)
  - [Changing your answers to set up questions](#changing-your-answers-to-set-up-questions)
    - [On iOS](#on-ios)
    - [On macOS](#on-macos)
  - [Updating The Shortcuts](#updating-the-shortcuts)
  - [Changelog](#changelog)
    - [2024-10-11](#2024-10-11)
      - [Saving Cash With The Cache!](#saving-cash-with-the-cache)
      - [Yet another new setting, oh no!](#yet-another-new-setting-oh-no)
      - [Other Changes](#other-changes)
    - [2024-09-29](#2024-09-29)
      - [New model!](#new-model)
      - [Apple Vanquished the Dreaded Bug!](#apple-vanquished-the-dreaded-bug)
      - [One last thing!](#one-last-thing)
    - [2024-09-17](#2024-09-17)
      - [Faster, Cheaper, and more reliable!](#faster-cheaper-and-more-reliable)
      - [Sharing screenshots and photos](#sharing-screenshots-and-photos)
      - [European Users, rejoice!](#european-users-rejoice)
      - [Other changes](#other-changes-1)
    - [2024-05-24](#2024-05-24)
      - [Minor Bug Fix](#minor-bug-fix)
    - [2024-05-22](#2024-05-22)
      - [Smarter and quicker AI responses!](#smarter-and-quicker-ai-responses)
      - [Share Multiple Images](#share-multiple-images)
      - [Where'd my description go?](#whered-my-description-go)
  - [Thanks](#thanks)

## Quick-start

Already know what you're doing and would rather not read through this whole document? no worries! I won't get in your way!

- [Download Describe Screenshot](https://www.icloud.com/shortcuts/5394f77c9f0e463da7264c7eaaa6d398)
- [Download Describe Photo](https://www.icloud.com/shortcuts/0a788f17242f48e08f2867101f9ef368)

Just here to check for updates? [Jump Straight To The Changelog!](#changelog)

If you do have any questions down the road though, please start with this document. I've done my best to answer as much as I could and it's all organized into sections.

## What are Apple Shortcuts?

Shortcuts are powerful automation tools built into Apple products, including iPhones, iPads, and Macs. They allow users to create custom workflows and mini-programs that can be triggered by various methods, such as tapping an icon, using Siri, or even assigning them to accessibility features like VoiceOver gestures or the Action Button on the iPhone 15 Pro.

## Why use my shortcuts instead of Be My Eyes?

Though Be My Eyes is an excellent free service that already exists to provide visual assistance to blind people, there are several reasons why you might prefer to use these shortcuts:

1. **Gesture and Keyboard Assignment**: As mentioned earlier, these shortcuts can be assigned to a VoiceOver gesture, Voice Control command, or keyboard shortcut on your Apple device. This allows for quick and easy access to the feature without needing to navigate to a separate app or service.

2. **macOS Compatibility**: Be My Eyes was written for iOS and does not work on macOS. In contrast, these Shortcuts are designed to work seamlessly on both iOS/iPadOS and macOS, providing a consistent experience across all your Apple devices. In fact, the Describe Photo shortcut will even work on Apple Vision Pro if you have enough money to shell out on one of those!

3. **Data Privacy**: While Be My Eyes is a trustworthy company, using the Describe Images Shortcuts allows you to communicate directly with the AI service (OpenAI) without involving a third party. This means that your data is only shared between you and OpenAI, reducing the number of entities that have access to your information.

4. **Processing Multiple Images at once**: With Describe Photos, you're able to share multiple images from your photo library in one message. Got some vacation photos you'd like described together? This can handle that!

5. **Greater Control and Customization**: The Shortcuts offer more control over your interactions with the AI. For example, you can customize the AI's writing style, language, and other advanced parameters to better suit your needs and preferences. This level of customization is not available with Be My Eyes.

On the other hand, using these Shortcuts is not free. Images will range from 0.5 to 1 cent with the regular model, and 1-2 cents with the latest one per description, so if this is a concern for you, stick with Be My Eyes.

## Can Sighted People Use This?

Absolutely! While the documentation is written with VoiceOver users in mind, sighted users can easily customize the shortcuts to fit their needs. For example, you can adjust the system prompt to add a personal touch, like "describe my memes in a snarky tone."

Only download Describe Photos though, as it's the only shortcut that works with the share sheet. During setup, pay special attention to the fifth question. It will undo a VoiceOver-specific change, making the shortcuts easier for sighted users to use.

## Getting Started And Some Prerequisites

Before using either shortcut, you must first do the following:

### OpenAI Account Setup

If you already have an account set up with OpenAI and already have an API key you can use, feel free to skip this section.

1. Create an OpenAI account at [platform.openai.com](https://platform.openai.com). If you have a ChatGPT account, you can sign in with the same email address and password.

2. Add a payment method and create a billing agreement at [platform.openai.com/account/billing](https://platform.openai.com/account/billing).
   The minimum amount you can add to your account is $5, which should last for many descriptions (each description costs around 1 cent).
   Keep in mind that the form where you fill in your credit card details will automatically advance you to the next field after the one you're in has been filled.
   For example: If you're on the cvv field, you'll be pushed to the next field after typing the three numbers without having to hit tab.

3. Generate an API key at [platform.openai.com/api-keys](https://platform.openai.com/api-keys). Give the key a name, click "Create," and copy the generated key to a safe place. Do not share this key with anyone.

### Install the Shortcuts App

This one doesn't really need a section of its own, especially because the Shortcuts app comes preinstalled on most devices, but just make sure you have it. If you don't, it's free on the app store.

### Install the shortcuts themselves

There are currently two Shortcuts. Both will be described and are accompanied by download links. You'll want to click on the download links with a device that already has the Shortcuts app installed. Clicking the link from Google Chrome on your windows laptop unfortunately won't work.

After clicking the link, you'll be asked if you want to add them to Shortcuts. After adding them, you'll be walked through a bunch of set up questions.

If you're already sick of setting things up, no worries! The only required question is the first one which asks for your API key. Fill that in then press "Skip setup." You can always come back to the other questions later.

#### Describe Screenshot

Describe Screenshot allows you to take a screenshot on your iPhone, iPad, or Mac and within about 3-5 seconds, get a detailed description of its contents. This shortcut is particularly useful for VoiceOver users who may not be able to see the content of UI elements in inaccessible apps or games.

Download Link: [Describe Screenshot](https://www.icloud.com/shortcuts/5394f77c9f0e463da7264c7eaaa6d398)

#### Describe Photo

Describe Photo works similarly to Describe Screenshot, but it allows you to either:

1. Take a photo within the shortcut
2. Share one or more photos with the shortcut with the share sheet (iOS, iPad OS, Mac OS, and Vision OS) or quick actions (macOS.)
3. Grab the most recent photo from your camera roll, intended for Apple Vision Pro and other glasses or headsets, or for those who prefer the functionality provided by the photos app.

Download Link: [Describe Photo](https://www.icloud.com/shortcuts/0a788f17242f48e08f2867101f9ef368)

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

##### Mac OS Sequoia

The new Commands tab in VoiceOver's preferences is a bit more complicated than the old one, though as a result, it is much more powerful. If you want an audio walk-through of this new feature, check out [this Applevis Podcast Episode!](https://www.applevis.com/podcasts/demonstration-walkthrough-voiceover-command-customization-macos)

You can assign the Describe photo shortcut to any of VoiceOver's modifiers. For the sake of this guide, we'we'll be assigning it to the right option key, specifically, Right Option + Shift + R. The process for assigning it to other modifiers is similar, but again, this interface is complicated and I can't cover all of it here.
Note: If you've already assigned the shortcuts in mac Os Sonoma or below, you can ignore this step.

1. Open the VoiceOver Utility by pressing VO+F8
2. navigate to the Commands tab in the table, alternatively, press Command + 8
3. On this screen, you're looking for a radio button that says, "Command set: User" Press it.
4. Press VO+RightArrow. You should see a Command Set: edit button. Press that.
5. On this edit screen, past the command assignment table, you'll see an "add" button. Press that.
6. Your cursor should be placed back in the command assignment table with your new item selected. Press VO+Space on the Input Edit button.
7. Navigate to the Option Keys submenu, then the letters with shift key submenu, then press enter on the R item. This will assign Right Option shift R to something, but that something hasn't yet been defined.
8. Now press the Command (None) button to the right of the command assignment button. This will open another menu.
9. navigate down to the "custom commands" submenu, then choose run shortcut.
10. In the table that appears, find Describe Photo and press VO+Space on it.

The command should now be assigned and you can safely close the commands window.

##### Mac OS Sonoma or below

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
4. The image and optional question will be sent to OpenAI for processing. The description should be returned within 3-5 seconds as an alert covering the top of the screen.
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

#### Sharing Photos

To share the last photo you took from within the shortcut, type /share into the reply field. This will allow you to share the photo with whoever or whatever you'd like using the regular share sheet. Just like the other commands, you can only enter this in the reply field, and you can type this anywhere in your message, or by itself.

#### Describing Photos from share sheet or Mac OS Quick Actions

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
5. The image and optional question will be sent to OpenAI for processing. The description should be returned within 3-5 seconds as an alert covering the top of the screen.
6. The alert will display the cost of the description and provide two buttons: "Cancel" and "Okay."
   - Press "Cancel" if you're done with the shortcut.
   - Press "Okay" to reply to the AI. Note that replying will cost more because the entire conversation history is sent and processed each time.

The functionality on macOS is identical to that on iOS. The cursor will automatically be placed in the message box, and you can press enter to send your message. When the description comes back, VoiceOver should automatically place focus on the alert.

#### Saving The Screenshot

When in the reply field, you can enter the command `/save` to save the screenshot to the album you chose during the shortcut setup. If you didn't specify an album, the screenshot will be saved to the Recents album. You can enter this command anywhere in the text field, including in the middle of a reply. If you type it in the text box by itself, when you hit done, the screenshot will be saved and the shortcut will stop. This way you don't have to actually reply to save your screenshot.

#### Sharing the screenshot

Just as with the /save command, you can type /share in the reply field and the screenshot will be shared with the share sheet, at which point you can send the screenshot to whoever or whatever you want. This command can be entered anywhere in the reply field, and can be entered by itself. When entered by itself, the Shortcut will stop after the screenshot has been shared.

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

## Updating The Shortcuts

If you have an old version of either shortcut and would like to update to the latest version, the process is identical on iOS and macOS. Do the following:

1. Click on the link to the shortcut you'd like to update.
2. The Shortcuts app should open and show you the name and details for the Shortcut you clicked on. Tap Set Up Shortcut.
3. You'll be asked the set up questions again. The only question you should have to answer again is the first one, which asks for your API key. Fill that in, then press "Skip setup."

That's it! You're now running the latest version of the shortcut. You don't need to set up VoiceOver again.

**Note**: If you adjusted other fields like the system prompt, you might have to adjust them again after updating. For this reason, I'd suggest saving prompts you write elsewhere in case an update clears them.

## Changelog

All changes to each Shortcut will be documented here.

### 2024-10-11

- [Download Describe Screenshot](https://www.icloud.com/shortcuts/5394f77c9f0e463da7264c7eaaa6d398)
- [Download Describe Photo](https://www.icloud.com/shortcuts/0a788f17242f48e08f2867101f9ef368)

#### Saving Cash With The Cache!

Recently, OpenAI introduced [Prompt Caching](https://openai.com/index/api-prompt-caching/) to their API. This is a feature that makes long conversations significantly cheaper than before, but only with the default model. This process happens automatically. The shortcut will now take caching into account when telling you how much a conversation costs.

#### Yet another new setting, oh no!

Now, the shortcut will copy the AI's responses to the clipboard. Seeing as not everyone will like this, there is a set up question to turn this behavior off. Happy copy and pasting!

#### Other Changes

- The default max_tokens parameter has been dropped to 1500 tokens. The newer model can't generate tokens quickly enough to pass this point before the Shortcut times out, and the default model can never manage to write even 1000 tokens.
- Adjusted messaging slightly so when using the new model, the price is shown before the phrase telling you you're using the newer model.




### 2024-09-29

- [Download Describe Screenshot](https://www.icloud.com/shortcuts/f82fce2bbea54d92909d270127929fbe)
- [Download Describe Photo](https://www.icloud.com/shortcuts/74ffbda2b0144be68f6c5404084a3ad9)

#### New model!

The shortcut now gives you the option to use OpenAI's ChatGPT-latest model, which is basically the same one you’ll find on the ChatGPT website. It’s currently much more detailed and conversational than the previous model, gpt-4o-2024-08-06. On the flip side, it’s a bit pricier, averaging around 1-2 cents per description. Just a heads-up: unlike the older model, this one can change as OpenAI updates things, so it might be awesome today and not-so-great next week. The default model will still be gpt-4o-2024-08-06, but if you want to give the new one a shot, just type 'y' in the second setup question. For what it’s worth, I’m using it and enjoying it a lot!

#### Apple Vanquished the Dreaded Bug!

The dynamic island bug that required us to open the Shortcuts app to operate the shortcuts has now been fixed. in iOS 18. Now, the dynamic island set up question defaults to being empty. If you are still on iOS 17 and on a phone with a dynamic island, you'll need to re-add the y to that question. Otherwise, rejoice, for we can now use Shortcuts the way the rest of the world does!

#### One last thing!

For the two of you using the Quick Look view, it will now convert the AI's response to rich text. So if text is bold, italicized, or what have you, the   box will correctly reflect that.

### 2024-09-17

- [Download Describe Screenshot](https://www.icloud.com/shortcuts/01a99ff2108e4d1791ace2213eae47c3)
- [Download Describe Photo](https://www.icloud.com/shortcuts/66587eb787194abf870d7929489c07ea)

#### Faster, Cheaper, and more reliable!

Remember when it used to take 10-15 seconds to get image descriptions back? After this update, it should only take from 3 to 5 seconds. Additionally, now you should easily be able to send 15-20 images through Describe Photos with no issues. I haven't yet updated the messaging when sharing large amounts of photos though, just because I don't have enough data on what the limits will be. Also, you should no longer see the "image too large" or the "image not compatible" errors. This typically happened when sharing live photos. Finally, prices are even lower now. I typically will get image descriptions for around half a penny.

#### Sharing screenshots and photos

Now, when in a reply field, you can type /share and the last photo or screenshot will be shared via the share sheet so you can have a sighted friend or family member verify a description. This will only share the most recent photo taken by the shortcut, not all of them.

#### European Users, rejoice!

I say European users, but really, it's anyone that has their number formatting set up so that , is the decimal separator. The shortcuts will now function properly for you! Thanks Apple for making me have to build workarounds for your broken code!

#### Other changes

- The system prompt has been adjusted slightly to make the descriptions more detailed and verbose.
- The Max_Tokens parameter is now 8000 since everything is significantly cheaper and faster. Remember though, the model will never actually hit or even get close to that limit.

### 2024-05-24

Download Links:

- [Download Describe Screenshot](https://www.icloud.com/shortcuts/1729c507d8c144ffacbefdf6f9108c61)
- [Download Describe Photo](https://www.icloud.com/shortcuts/733905244a6d4aa0bd77a46d3f83aae5)

#### Minor Bug Fix

Fun fact: The Apple product line consists of more than just iPhones, Macs, and Vision Pros. Describe Photo and Describe Screenshot are now aware of the existence of iPads. Since iPads don't currently have Dynamic Islands, the Blind Dynamic Island user setting is ignored if the shortcut detects it's being run on an iPad.

### 2024-05-22

Download Links:

- [Download Describe Screenshot](https://www.icloud.com/shortcuts/eca5fc921a14481295f0fef3b4617e2c)
- [Download Describe Photo](https://www.icloud.com/shortcuts/365c2cabdec548d293073c2652236c38)

#### Smarter and quicker AI responses!

Both Shortcuts are now powered by OpenAI's new GPT-4o model. This model is quicker and more accurate than the previous GPT-4 model, and is also 50% cheaper. Your descriptions should now cost around 1 cent, sometimes less!

#### Share Multiple Images

The Describe Photo shortcut will now allow you to share multiple images through the share sheet or Finder. Got vacation photos you want described all at once? We've got you covered! Can also come in handy when comparing images. Generating AI art just got a lot easier!

#### Where'd my description go?

There's a really annoying issue with the Show Alert action these Shortcuts use to display descriptions. If the description is too long, the text visually cuts off and there's no way to read the rest. It doesn't affect us blind folks, but if you're sighted, you were out of luck!

Now, both Shortcuts will ask you, as part of their set up questions, if you're sighted. If you indicate that you are, descriptions will be shown with a different box that will comfortably hold the entire description.

## Thanks

Thanks for checking out my Shortcuts and for reading to the end of this massive document!

I hope you find them useful. If you do, share them with your friends! AI tools like this might be the future of assistive tech, and now is the best time to start learning how to use them!

[Back To Home](../index.md)
