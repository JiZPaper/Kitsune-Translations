# Kitsune Translations

Thank you for your interest in helping translate Kitsune for MyAnimeList! By contributing, you help people from all over the world enjoy the app in their native language. This guide will walk you through the process, which is simpler than it looks!

### What are these files? A Quick Guide

To help you feel safe and confident, here’s a one-sentence explanation for each file type in this repository:

* **`.xliff` (for Translators):** This is a standard, safe-to-download text file that contains all the app's text, ready for you to translate. This is the file most people will use.
* **`.xcloc` (for Developers):** This is a special package used by developers on macOS with Xcode to manage all the app's text in one place.

---

## How to Contribute

There are two ways to contribute, depending on your technical comfort level. Please choose the path that works best for you.

### Path A: For Translators (The Easy Way)

This method is for everyone and does not require any coding experience. You will use a free online tool to edit the translation files.

#### Step 1: Find and Download Your Language File

1.  Navigate into the **`xliff`** folder in this repository.
2.  Find the file that matches your language (for example, `pt-BR.xliff` is for Brazilian Portuguese).
3.  Click on the file to open it, and then press the **"Download"** button to save it to your computer.

#### Step 2: Edit the File Online

1.  Open your web browser and go to the [**Brightec Online XLIFF Editor**](http://xliff.brightec.co.uk). It's a free and simple tool.
2.  Click the button to **upload** the `.xliff` file you just downloaded.
3.  You will see two main columns: **"Source"** (the original English text) and **"Target"** (where your translation goes). Simply fill in the "Target" fields with your translations.

    > **Heads up!** If you see any strange-looking code (like `%@` or `%d`), please leave it exactly as it is. The app needs it to work correctly!

#### Step 3: Send Us Your Work

1.  Once you're finished translating, click the **"Generate new XLIFF file"** button on the website to get your updated file.
2.  Attach this new `.xliff` file to an email and send it to **kitsune@alexandremadeira.dev**.
3.  You can also upload the file here.

And that's it!

#### Want to Add a New Language?

If you don't see your language in the list, no worries! It's super easy to add a new one.

1.  In the `xliff` folder, just download any existing language file. Starting with `en.xliff` (English) is usually a good bet.
2.  On your computer, rename that file to your language's code (for example, change `en.xliff` to `fr.xliff` for French).
3.  Now, just follow the "Path A" steps above to fill it out with your awesome translations.
4.  Email us the final file, and we'll get your new language into the app!

---

### Path B: For Developers

This option is for developers using macOS and Xcode.

1.  Clone this repository to your Mac.
2.  Navigate into the **`xcloc`** folder.
3.  Open the `.xcloc` file for your desired language directly in Xcode to begin translating.

---

Everyone who helps out will get a shout-out on the app's "About" screen. When you send your file, just let me know the name you'd like to be credited by, and feel free to include a link to your personal website or social media.

All new translations will be included in the upcoming app update.

### A Quick Note on Spreadsheets

To anyone who contributed using Apple Numbers, Google Sheets, or Excel before, thank you so much!

I've decided to remove the spreadsheet method for contributing. As the project has grown, it was becoming too complex to manage everyone's contributions this way, especially when fixing typos or adding new translations. I'm really sorry for any inconvenience this might cause!

The new system using the .xliff files should make the whole process much smoother and ensure everyone's hard work gets added to the app correctly.

### Need a Hand?

If you have any questions or get stuck, please don't hesitate to reach out! I'm happy to help.

[Email](mailto:kitsune@alexandremadeira.dev)

[Kitsune Discord Server](https://discord.gg/YCKAEFYasp)

Thanks again for helping out!
