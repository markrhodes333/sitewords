# Sight Word Star Quest

A phone-friendly Progressive Web App (PWA) for practicing weekly sight words.

## Included features

- Editable weekly sight-word lists
- Save multiple weekly lists and switch between them
- Paste words one-per-line or separated by commas
- 10-word, all-word, and missed-word practice modes
- Randomized word order
- Text-to-speech "Hear the Word" button
- Stars, daily practice count, and missed-word tracking
- Parent setup protected by a PIN
- Offline use after installation
- Android "Install app / Add to Home screen" support
- No account, ads, analytics, or cloud storage

## Parent PIN

Default PIN: `2468`

You can change it inside Parent Setup.

## Easiest Android installation

A PWA must be opened from an HTTPS website at least once before Android can install it. The files in this folder are ready to host as-is.

### Option A: Netlify Drop

1. On a computer, unzip the project.
2. Open Netlify Drop in a web browser.
3. Drag the entire `sight_word_star_quest` folder into the upload area.
4. Netlify will give you an HTTPS web address.
5. Open that address in Chrome on your Android phone.
6. Tap the browser menu and choose **Install app** or **Add to Home screen**.
7. After installation, the game works offline.

### Option B: GitHub Pages

1. Create a new GitHub repository.
2. Upload all files from this folder to the repository root.
3. Turn on GitHub Pages for the repository.
4. Open the Pages HTTPS address on your Android phone.
5. In Chrome, choose **Install app** or **Add to Home screen**.

## Changing the words each week

1. Open the app.
2. Tap the gear icon in the upper-right corner.
3. Enter the parent PIN.
4. Enter a list name such as `Week of Sept. 28`.
5. Paste the new words into the Sight Words box.
6. Tap **Save as New List**.
7. The new list becomes the active practice list automatically.

Old lists remain saved on that phone until you delete them.

## Important storage note

The lists and progress are stored in the browser/app storage on that device. Clearing site data or uninstalling the app can remove that data.
