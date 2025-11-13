# yomitan-glass-theme
a glass theme for yomitan.

| OS/Browser | Light Mode  | Dark Mode |
| - | ------------- | ------------- |
| Windows Firefox | <img width="659" height="539" alt="image" src="https://github.com/user-attachments/assets/fbfac77a-b361-4159-8988-d991ac157f8b" /> | <img width="683" height="543" alt="image" src="https://github.com/user-attachments/assets/a18d194e-ebdb-42b7-b2e7-8f5a178ff8a2" /> |
| Android Firefox | ![Screenshot_20251113_165054_Firefox](https://github.com/user-attachments/assets/81b0eb9a-e730-47de-b58b-1d5284ea3675) | ![Screenshot_20251113_165152_Firefox (1)](https://github.com/user-attachments/assets/c8f9c482-dbcf-42c3-adeb-1b330dc6119d) |

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
