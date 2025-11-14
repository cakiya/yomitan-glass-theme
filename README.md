# yomitan-glass-theme
a glass theme for yomitan.

| Light Mode  | Dark Mode |
| ------------- | ------------- |
| <img width="651" height="539" alt="image" src="https://github.com/user-attachments/assets/247d801a-486f-4729-ad14-a90b3c39126b" /> | <img width="677" height="562" alt="image" src="https://github.com/user-attachments/assets/38f67a21-d711-4346-9b4f-b65f9c30585c" /> |

adapted from [GameSentenceMiner's wiki](
https://github.com/bpwhelan/GameSentenceMiner/wiki/Overlay-%E2%80%90-Overview#custom-glassy-css-for-yomitan
) to work for light theme as well as various bug fixes (eg. not working on google.com)

# Setup

1. Navigate to `Appearance` -> `Configure custom CSS...`
2. Copy the contents of `popup.css` into "Popup CSS"
3. Copy the contents of `popup-outer.css` into "Popup outer CSS"

> [!WARNING]
> if you're NOT on Firefox, remove the top portion of `popup.css`

this is because Firefox renders the ruby differently than chromium browsers, it's an issue with firefox. [relevant yomitan issue](https://github.com/yomidevs/yomitan/issues/1969)
<img width="1735" height="1033" alt="image" src="https://github.com/user-attachments/assets/7b5c2a68-4094-40e6-9df3-bf5375b0edec" />

# To-Do
1. figure out how to bring back the scroll bar without making it look ugly on chromium
2. make the light theme look better (lol)
3. make it work with shadow set to None on yomitan(?)
