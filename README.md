# YTPlus by Mark02 (YTLite with extra tweaks)
A version of YTPlus with more tweaks.

## Table of Contents
- [Screenshots](#screenshots)
- [Main Features](#main-features)
- [FAQ](#faq)
- [Reviews](#reviews)
- [How to build a YouTube Plus app using GitHub Actions](#how-to-build-a-youtube-plus-app-using-github-actions)
- [Supported YouTube Version](#supported-youtube-version)
- [Tweak Integration Details](#tweak-integration-details)
- [Preset settings YTPlus for lazy people](#Preset-settings-YTPlus-for-lazy-people)
## Screenshots
<table>
   <tr>
      <td><img src="Resources/scr1.jpg" alt="Screenshot 1" /></td>
      <td><img src="Resources/scr2.jpg" alt="Screenshot 2" /></td>
      <td><img src="Resources/scr3.jpg" alt="Screenshot 3" /></td>
   </tr>
</table>

<details>
  <summary>More screenshots</summary>
  <table>
    <tr>
      <td><img src="Resources/scr4.jpg" alt="Screenshot 4" /></td>
      <td><img src="Resources/scr5.jpg" alt="Screenshot 5" /></td>
      <td><img src="Resources/scr6.jpg" alt="Screenshot 6" /></td>
    </tr>
    <tr>
      <td><img src="Resources/scr7.jpg" alt="Screenshot 7" /></td>
      <td><img src="Resources/scr8.jpg" alt="Screenshot 8" /></td>
      <td><img src="Resources/scr9.jpg" alt="Screenshot 9" /></td>
    </tr>
  </table>
</details>

## Main Features
<li>Download videos, audio (including audio track selection), thumbnails, posts, and profile pictures</li>
<li>Copy video, comment, and post information</li>
<li>Interface customization: Remove feed elements, reorder tabs, enable OLED mode, and as use Shorts-only mode</li>
<li>Player settings: Gestures, default quality, preferred audio track</li>
<li>Save, Load and Restore settings. Clear cache once or automatically on app startup</li>
<li>Built-in SponsorBlock</li>
<li>And much, much more</li>
<br>


**YouTube Plus preferences can be found in the YouTube Settings**

<details>
<summary>In Italian</summary>

<strong>Funzioni principali</strong>

 <li>Scarica video, audio (inclusa la selezione delle tracce audio), miniature, post e immagini del profilo</li>
 <li>Copia informazioni su video, commenti e post</li>
 <li>Personalizzazione dell'interfaccia: rimuovi elementi del feed, riordina le schede, abilita la modalità OLED e usa la modalità solo Shorts</li>
 <li>Impostazioni del player: gesti, qualità predefinita, traccia audio preferita</li>
 <li>Impostazioni di salvataggio, caricamento e ripristino. Svuota la cache una volta o automaticamente all'avvio dell'app</li>
 <li>SponsorBlock integrato</li>
 <li>E molto, molto altro</li>
<br>


 **Le preferenze di YouTube Plus si trovano nelle Impostazioni di YouTube**
</details>

## FAQ
- [🇺🇸 English FAQ](FAQs/FAQ_EN.md)
- [🇷🇺 ЧаВо на Русском](FAQs/FAQ_RU.md)
- [🇮🇹 FAQ in Italiano](FAQs/FAQ_IT.md)
- [🇵🇱 FAQ po polsku](FAQs/FAQ_PL.md)

## Reviews
Review by [@qbap](https://github.com/qbap) on ONE Jailbreak: https://onejailbreak.com/blog/youtube-plus/

## How to build a YouTube Plus app using Github actions
> [!NOTE]
> If this your first time, complete following steps before starting:
>
> 1. Fork this repository using the fork button on the top right
> 2. On your forked repository, go to **Repository Settings** > **Actions**, enable **Read and Write** permissions.

<details>
  <summary>How to build the YouTube Plus app</summary>
  <ol>
    <li>Click on <strong>Sync fork</strong>, and if your branch is out-of-date, click on <strong>Update branch</strong>.</li>
    <li>Navigate to the <strong>Actions tab</strong> in your forked repository and select <strong>Create YouTube Plus app</strong>.</li>
    <li>Click the <strong>Run workflow</strong> button located on the right side.</li>
    <li>Mark or unmark the tweaks you want to integrate. Learn more about them in the <a href="#tweak-integration-details">Tweak Integration Details</a> section.</li>
    <li>Prepare a decrypted .ipa file <em>(we cannot provide this due to legal reasons)</em>, then upload it to a file provider (e.g., filebin.net, filemail.com, or Dropbox is recommended). Paste the URL of the decrypted IPA file in the provided field.</li>
    <li><strong>NOTE:</strong> Make sure to provide a direct download link to the file, not a link to a webpage. Otherwise, the process will fail.</li>
    <li>Enter the tweak version from the releases (the latest release is selected by default). You can also change the BundleID and Display Name if desired.</li>
    <li>Make sure all inputs are correct, then click <strong>Run workflow</strong> to start the process.</li>
    <li>Wait for the build to finish. You can download the YouTube Plus app from the releases section of your forked repo. (If you can't find the releases section, go to your forked repo and add /releases to the URL, i.e., github.com/user/YTLite/releases.)</li>
  </ol>
</details>


<details>
  <summary>How to build the YouTube Plus app with your own link for the YouTube Plus tweak</summary>
  <ol>
    <blockquote>
      <p><strong>NOTE:</strong> This option is primarily intended for building the YouTube Plus app based on the beta file you have. In other cases, it is generally not needed.</p>
    </blockquote>
    <li>Click on <strong>Sync fork</strong>, and if your branch is out-of-date, click on <strong>Update branch</strong>.</li>
    <li>Navigate to the <strong>Actions tab</strong> in your forked repository and select <strong>[BETA] Build YouTube Plus app</strong>.</li>
    <li>Click the <strong>Run workflow</strong> button located on the right side.</li>
    <li>Mark or unmark the tweaks you want to integrate. Learn more about them in the <a href="#tweak-integration-details">Tweak Integration Details</a> section.</li>
    <li>Prepare a decrypted .ipa file <em>(we cannot provide this due to legal reasons)</em>, then upload it to a file provider (e.g., filebin.net, filemail.com, or Dropbox is recommended). Paste the URL of the decrypted IPA file in the provided field.</li>
    <li>Upload your beta tweak file to a file provider and paste direct link to the <strong>URL to the YouTube Plus tweak file</strong> field. You can also change the BundleID and Display Name if desired.</li>
    <li><strong>NOTE:</strong> Make sure to provide a direct download link to the file, not a link to a webpage. Otherwise, the process will fail.</li>
    <li>Make sure all inputs are correct, then click <strong>Run workflow</strong> to start the process.</li>
    <li>Wait for the build to finish. You can download the YouTube Plus app from the releases section of your forked repo. (If you can't find the releases section, go to your forked repo and add /releases to the URL, i.e., github.com/user/YTLite/releases.)</li>
  </ol>
</details>

## Supported YouTube Version
<ul>
   <li><strong>Latest confirmed:</strong> <em>21.10.2</em></li>
   <li><strong>Date tested:</strong> <em>March 9, 2026</em></li>
   <li><strong>YouTube Plus:</strong> <em>5.2 beta 4</em></li>
</ul>

## Tweak Integration Details
<details>
  <summary>YouPiP</summary>
  <p>YouPiP is a tweak developed by <a href="https://github.com/PoomSmart">PoomSmart</a> that enables the native Picture-in-Picture feature for videos in the iOS YouTube app.</p>
  <p><strong>YouPiP preferences</strong> are available in the <strong>YouTube settings</strong>.</p>
  <p>Source code and additional information are available <a href="https://github.com/PoomSmart/YouPiP">in PoomSmart's GitHub repository</a>.</p>
</details>

<details>
  <summary>YTUHD</summary>
  <p>YTUHD is a tweak developed by <a href="https://github.com/PoomSmart">PoomSmart</a> that unlocks 1440p (2K) and 2160p (4K) resolutions in the iOS YouTube app.</p>
  <p><strong>YTUHD preferences</strong> are available in the <strong>Video quality preferences</strong> section under <strong>YouTube settings</strong>.</p>
  <p>Source code and additional information are available <a href="https://github.com/PoomSmart/YTUHD">in PoomSmart's GitHub repository</a>.</p>
</details>

<details>
  <summary>Return YouTube Dislikes</summary>
  <p>Return YouTube Dislikes is a tweak developed by <a href="https://github.com/PoomSmart">PoomSmart</a> that brings back dislikes on the YouTube app.</p>
  <p><strong>Return YouTube Dislikes preferences</strong> are available in the <strong>YouTube settings</strong>.</p>
  <p>Source code and additional information are available <a href="https://github.com/PoomSmart/Return-YouTube-Dislikes">in PoomSmart's GitHub repository</a>.</p>
</details>

<details>
  <summary>YouQuality</summary>
  <p>YouQuality is a tweak developed by <a href="https://github.com/PoomSmart">PoomSmart</a> that allows to view and change video quality directly from the video overlay.</p>
  <p><strong>YouQuality can be enabled</strong> in the <strong>Video overlay</strong> section under <strong>YouTube settings</strong>.</p>
  <p>Source code and additional information are available <a href="https://github.com/PoomSmart/YouQuality">in PoomSmart's GitHub repository</a>.</p>
</details>

<details>
  <summary>DontEatMyContent</summary>
  <p>DontEatMyContent is a tweak developed by <a href="https://github.com/therealFoxster">therealFoxster</a> that prevents the Notch/Dynamic Island from munching on 2:1 video content in the iOS YouTube app.</p>
  <p><strong>DontEatMyContent preferences</strong> are available in the <strong>YouTube settings</strong>.</p>
  <p>Source code and additional information are available <a href="https://github.com/therealFoxster/DontEatMyContent">in therealFoxster's GitHub repository</a>.</p>
</details>

<details>
  <summary>YTABConfig</summary>
  <p>YTABConfig is a tweak developed by <a href="https://github.com/PoomSmart">PoomSmart</a>  This tweak adds a new section named "A/B" in the app settings where all features can be toggled freely by you.</p>
  <p><strong>YTABConfig preferences</strong> are available in the <strong>YouTube settings</strong>.</p>
  <p>Additional information are available <a href="https://github.com/PoomSmart/YTABConfig">in PoomSmart's GitHub repository</a> and in <a href="https://poomsmart.github.io/repo/depictions/ytabconfig.html"> his website</a>.</p>
</details>

<details>
  <summary>YTweaks</summary>
  <p>YTweaks is a tweak developed by <a href="https://github.com/fosterbarnes">fosterbarnes.</a>  This tweak adds features like night mode, disable floating miniplayer, virtual fullscreen bezels and others.</p>
  <p><strong>YTweaks preferences</strong> are available in the <strong>YouTube settings</strong>.</p>
  <p>Deb file, source code and additional information are available <a href="https://github.com/fosterbarnes/YTweaks">in fosterbarnes's GitHub repository</a></p>
</details>

## Preset settings YTPlus for lazy people
### (specifically for 5.2b4, not recommended on other versions)
https://files.catbox.moe/14rc7w.plist

To use this preset, you have to:

<strong>1.</strong> Download it (on the phone) clicking on the link

<strong>2.</strong> Get on YTPlus, open settings>YouTube Plus>YouTube Plus Settings>Import settings

<strong>3.</strong> Select the .plist file

<strong>This preset enable:</strong>

- 2 fingers-clic on the overlay to pause the long video

- Oled theme

- YouTube Premium logo 

- Remove share identifier

- Progress bar in shorts

- No "Include Paid Promotion" in shorts

- Hide Trends on shorts

<strong>This preset modify:</strong>

- Some settings on SponsorBlock

- Preferred resolution with Wi-Fi 1080p60 for shorts and long videos

- Add "History" on the tab bar

<details>
 <summary>In Italian</summary>
 **Impostazioni preimpostate YTPlus per i pigri**
 **(specificamente per 5.2b4, non consigliato su altre versioni)**
   
https://files.catbox.moe/14rc7w.plist

Per utilizzare questo preset, è necessario:

<strong>1.</strong> Scaricalo (sul telefono) cliccando sul link

<strong>2.</strong> Accedi a YTPlus, apri impostazioni>YouTube Plus>Impostazioni YouTube Plus>Importazione impostazioni

<strong>3.</strong> Seleziona il file .plist

<strong>Questo preset abilita:</strong>

- Clic con 2 dita sulla sovrapposizione per mettere in pausa il video lungo

- Tema Oled

- Logo YouTube Premium 

- Rimuovi l'identificatore di condivisione

- Barra di avanzamento negli shorts

- No "Include promozioni a pagamento" in shorts

- Nascondi le tendenze in shorts

<strong>Questo preset modifica:</strong>

- Alcune impostazioni in SponsorBlock

- Risoluzione preferita con Wi-Fi 1080p60 per shorts e video lunghi

- Aggiungi "Cronologia" sulla barra delle schede
</details>


