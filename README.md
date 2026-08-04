<!-- LTeX: language=en-US -->

<div align="center">

  <img src="public/assets/images/git/banner.jpg" alt="Banner Image" width="75%">

# [Sky1984 Sheets Collection](https://api.github.com/repos/Ai-Vonie/Sky1984-Sheets-Collection)

🌍 Read in: **⮞⮞ English (en-US) ⮜⮜** _∙ [Español (es-ES)](README_es-ES.md) ∙
[Русский (ru-RU)](README_ru-RU.md)_

</div>

**Sky1984 Sheets Collection** is an extensive library of music sheets collected to simplify the
search for specific compositions in one place. These sheets are designed for playing on in-game
instruments in **Sky: Children of the Light** and for use on the
_[Sky Music Nightly](https://sky-music-nightly.pages.dev/)_ site. The music sheets are located in
three main folders ([**Multi-Sheet Songs**](Multi-Sheet%20Songs), [**Songs**](Songs), and
[**VSRG**](VSRG)), where they are sorted alphabetically.

> [!WARNING]
>
> ⚠️ **Attention!** This collection is not complete or final. It is recommended to check other
> sources and libraries for updates, as the content of this repository may be outdated or irrelevant
> compared to them.

<details open>
<summary><b>📋 Table of Contents</b></summary>

---

- [Sky1984 Sheets Collection](#sky1984-sheets-collection)
  - [🔍 How to Properly Search for Sheets](#-how-to-properly-search-for-sheets)
  - [💾 How to Download](#-how-to-download)
    - [1. Downloading an Individual File](#1-downloading-an-individual-file)
    - [2. Downloading a Specific Folder](#2-downloading-a-specific-folder)
    - [3. Downloading the Entire Repository](#3-downloading-the-entire-repository)
    - [4. Downloading archives from releases](#4-downloading-archives-from-releases)
  - [🎹 MIDI to Sky Sheet Converter](#-midi-to-sky-sheet-converter)
    - [📝 Usage Recommendations](#-usage-recommendations)
  - [💭 Why?](#-why)
  - [⚙️ Technical Details](#️-technical-details)
  - [⚖️ Legal \& Copyright](#️-legal--copyright)
    - [Repository](#repository)
    - [Sheet Music Collection](#sheet-music-collection)

---

</details>

## 🔍 How to Properly Search for Sheets

For an effective search of the desired composition, try to follow these recommendations:

- **Use main keywords:** Enter only keywords or the significant part of the song title, and also try
  searching separately by the author's nickname.
- **Avoid clutter:** Exclude **stop words** (articles, conjunctions, prepositions) and specific
  symbols from your query.
- **Search in a specific folder:** use the special syntax
  [**`path:/^Songs\//`**](https://github.com/search?q=repo%3AAi-Vonie%2FSky1984-Sheets-Collection%20path%3A%2F%5ESongs%5C%2F%2F%20&type=code)
  at the beginning of your search query to limit the search to a specific folder.

The repository search works in two modes:

1. **[By file name](https://docs.github.com/search-github/searching-on-github/finding-files-on-github)**
   — press `t` or click the button **`Go to file`** to start searching in the file quick jump menu.
2. **[By file content](https://docs.github.com/search-github/github-code-search/using-github-code-search)**
   — press `/` or click the search field above **`Type / to search`** to activate
   [global code search in this repository](https://github.com/search?q=repo%3AAi-Vonie%2FSky1984-Sheets-Collection%20&type=code).

> [!IMPORTANT]
>
> ‼️ **Important:** To use code search (file content), you must **be logged into your GitHub
> account**.

It is recommended to read the documentation on
[code search limitations](https://docs.github.com/search-github/github-code-search/about-github-code-search#limitations)
and
[special query syntax](https://docs.github.com/search-github/github-code-search/understanding-github-code-search-syntax)
to understand the capabilities and technical constraints.

## 💾 How to Download&nbsp;[![Latest Release](https://img.shields.io/github/v/release/Ai-Vonie/Sky1984-Sheets-Collection?label=Latest%20Version&style=flat-square)](https://github.com/Ai-Vonie/Sky1984-Sheets-Collection/releases/latest)

You can download individual files, specific folders, or the entire repository at once.

### 1. Downloading an Individual File

Go to the page of the desired file and choose a convenient method:

- **Download file:** Click the icon **`Download raw file`** in the upper right corner above the file
  code.
- **Copy content:** Click the icon **`Copy raw file`** to copy the text to the clipboard.
- **Via Raw:** Click the **`Raw`** button, then press `Ctrl + S` (Windows) or `Cmd + S` (macOS) to
  save the file.

### 2. Downloading a Specific Folder

GitHub does not allow downloading individual folders by default. Use
[Download Directory](https://github.com/download-directory/download-directory.github.io) for this:

1. Open the desired folder in this repository.
2. Copy the link (URL) from the browser address bar.
3. Go to [download-directory.github.io](https://download-directory.github.io/)
   (`https://download-directory.github.io/`).
4. Paste the link into the input field and press `Enter`. The folder will download as a ZIP archive.

### 3. Downloading the Entire Repository

To get a full local copy of the library:

1. Go to the main repository page.
2. Click the green **`<> Code`** button.
3. Select
   [**`Download ZIP`**](https://github.com/Ai-Vonie/Sky1984-Sheets-Collection/archive/refs/heads/master.zip)
   from the dropdown menu.

### 4. Downloading archives from releases

You can also download a specific folder or the entire repository as an archive in the
[latest version release](https://github.com/Ai-Vonie/Sky1984-Sheets-Collection/releases/latest) from
the [**Releases**](https://github.com/Ai-Vonie/Sky1984-Sheets-Collection/releases) tab.

> The archives in releases use a specialized compression algorithm with settings optimized for the
> structure of these files to ensure the smallest possible size.

## 🎹 MIDI to Sky Sheet Converter&nbsp;[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Kia0VrRyctLVs1q0lYKJVnGpW45U7_EQ?usp=sharing)

If you want to create music sheet for Sky from a MIDI file, you can try to use the
[specialized conversion tool](https://colab.research.google.com/drive/1Kia0VrRyctLVs1q0lYKJVnGpW45U7_EQ?usp=sharing)
linked below:

```plaintext
https://colab.research.google.com/drive/1Kia0VrRyctLVs1q0lYKJVnGpW45U7_EQ?usp=sharing
```

> [!WARNING]
>
> ⚠️ **Warning!** This MIDI transposition tool operates on a simplified algorithm and does not
> utilize any advanced third-party libraries for deep musical analysis. It is recommended to use
> other specialized MIDI transposition tools, as this converter may be imperfect or less functional
> compared to professional alternatives.

Can find examples of decent conversions made with this script on the
**[SkyAutoMusic](https://discord.gg/wzjWKyJtmk)** (**`https://discord.gg/wzjWKyJtmk`**) Discord
server via the links below:

<details open>
<summary><b>👀 Conversion Examples Table</b></summary>

---

<!-- LTeX: enabled=false -->

| Composition                                                                                                           |                Link to file                |    Download file    |
| :-------------------------------------------------------------------------------------------------------------------- | :----------------------------------------: | :-----------------: |
| [🎹][ms_01] [_My Dearest - supercell Guilty Crown OP1 + Animenz's 10th Anniversary_][yt_01]                           | [💬 Discord][msg_01]<br>[🐱 GitHub][gh_01] | [💾 Discord][dl_01] |
| [🎹][ms_02] [_Oppenheimer Can You Hear the Music - Music by Ludwig Göransson Arrangement by Akmigone_][yt_02]         | [💬 Discord][msg_02]<br>[🐱 GitHub][gh_02] | [💾 Discord][dl_02] |
| [🎹][ms_03] _Kawaki wo Ameku - Domestic Girlfriend OP_                                                                | [💬 Discord][msg_03]<br>[🐱 GitHub][gh_03] | [💾 Discord][dl_03] |
| [🎹][ms_04] _Freedom DiVE (Full) - xi_                                                                                | [💬 Discord][msg_04]<br>[🐱 GitHub][gh_04] | [💾 Discord][dl_04] |
| [🎹][ms_05] [_Tokyo Ghoul - Licht und Schatten (Akmigone)_][yt_05]                                                    | [💬 Discord][msg_05]<br>[🐱 GitHub][gh_05] | [💾 Discord][dl_05] |
| [🎹][ms_06] [_Interstellar Main Theme – Hans Zimmer - Arrangement by Peter Buka_][yt_06]                              | [💬 Discord][msg_06]<br>[🐱 GitHub][gh_06] | [💾 Discord][dl_06] |
| [🎹][ms_07] _Interstellar_                                                                                            | [💬 Discord][msg_07]<br>[🐱 GitHub][gh_07] | [💾 Discord][dl_07] |
| [🎹][ms_08] [_in the pool - Chainsaw Man Reze Arc OST – Music by Kensuke Ushio Arrangement by Animenz_][yt_08]        | [💬 Discord][msg_08]<br>[🐱 GitHub][gh_08] | [💾 Discord][dl_08] |
| [🎹][ms_09] [_One Last Kiss - Evangelion 3.0 + 1.0 Theme Song – Music by Hikaru Utada Arrangement by Animenz_][yt_09] | [💬 Discord][msg_09]<br>[🐱 GitHub][gh_09] | [💾 Discord][dl_09] |
| [🎹][ms_10] _Ghost Rule - DECO 27 ft. Hatsune Miku.HatsuneMiku_                                                       | [💬 Discord][msg_10]<br>[🐱 GitHub][gh_10] | [💾 Discord][dl_10] |
| [🎹][ms_11] _Sekai Wa Koi Ni Ochiteiru - Ao Haru Ride OP_                                                             | [💬 Discord][msg_11]<br>[🐱 GitHub][gh_11] | [💾 Discord][dl_11] |
| [🎹][ms_12] [_Microchip – Music by Patrik Pietschmann_][yt_12]                                                        | [💬 Discord][msg_12]<br>[🐱 GitHub][gh_12] | [💾 Discord][dl_12] |
| [🎹][ms_13] [_Kamado Tanjiro no Uta - Go Shiina feat. Nami Nakagawa (The title is too long)_][yt_13]                  | [💬 Discord][msg_13]<br>[🐱 GitHub][gh_13] | [💾 Discord][dl_13] |
| [🎹][ms_14] _Night of Nights - COOL&CREATE Marasy8_                                                                   | [💬 Discord][msg_14]<br>[🐱 GitHub][gh_14] | [💾 Discord][dl_14] |
| [🎹][ms_15] [_ナイト・オブ・ナイツ 2020 (marasy arr.)_][yt_15]                                                        | [💬 Discord][msg_15]<br>[🐱 GitHub][gh_15] | [💾 Discord][dl_15] |
| [🎹][ms_16] _Touhou Boss Rush!! (I)_                                                                                  | [💬 Discord][msg_16]<br>[🐱 GitHub][gh_16] | [💾 Discord][dl_16] |

<!-- Reference links for MIDI conversion examples -->

[ms_01]: https://musescore.com/user/64980103/scores/13568578
[yt_01]: https://www.youtube.com/watch?v=lAXJPop9LaY
[msg_01]: https://discord.com/channels/735827593710010369/798936282449182741/1458087590593958000
[gh_01]:
  https://github.com/Ai-Vonie/Sky1984-Sheets-Collection/blob/v26.01.08-v1.2.0/Songs/M/My%20Dearest%20-%20supercell%20Guilty%20Crown%20OP1%20+%20Animenz's%2010th%20Anniversary.txt
[dl_01]:
  https://fixcdn.hyonsu.com/attachments/798936282449182741/1458087590635896988/My_Dearest_-_supercell_Guilty_Crown_OP1__Animenzs_10th_Anniversary.txt

<!-- -->

[ms_02]: https://musescore.com/user/81591427/scores/23161579
[yt_02]: https://www.youtube.com/watch?v=3jBtnMUlIzo
[msg_02]: https://discord.com/channels/735827593710010369/798936282449182741/1457687970420097221
[gh_02]:
  https://github.com/Ai-Vonie/Sky1984-Sheets-Collection/blob/v26.01.08-v1.2.0/Songs/O/Oppenheimer%20Can%20You%20Hear%20the%20Music%20-%20Music%20by%20Ludwig%20Göransson%20Arrangement%20by%20Akmigone.txt
[dl_02]:
  https://fixcdn.hyonsu.com/attachments/798936282449182741/1457687970881736836/Oppenheimer_Can_You_Hear_the_Music_-_Music_by_Ludwig_Goransson_Arrangement_by_Akmigone.txt

<!-- -->

[ms_03]: https://musescore.com/user/2050876/scores/5981746
[msg_03]: https://discord.com/channels/735827593710010369/798936282449182741/1460664377920454832
[gh_03]:
  https://github.com/Ai-Vonie/Sky1984-Sheets-Collection/blob/v26.01.14-v1.2.2/Songs/K/Kawaki%20wo%20Ameku%20-%20Domestic%20Girlfriend%20OP.txt
[dl_03]:
  https://fixcdn.hyonsu.com/attachments/798936282449182741/1460664374094987469/Kawaki_wo_Ameku_-_Domestic_Girlfriend_OP.txt

<!-- -->

[ms_04]: https://musescore.com/user/16423076/scores/6251635
[msg_04]: https://discord.com/channels/735827593710010369/798936282449182741/1460584833871777987
[gh_04]:
  https://github.com/Ai-Vonie/Sky1984-Sheets-Collection/blob/v26.01.14-v1.2.2/Songs/F/Freedom%20DiVE%20(Full)%20-%20xi.txt
[dl_04]:
  https://fixcdn.hyonsu.com/attachments/798936282449182741/1460584833544753310/Freedom_DiVE_Full_-_xi.txt

<!-- -->

[ms_05]: https://musescore.com/user/1176981/scores/3319216
[yt_05]: https://www.youtube.com/watch?v=O8s4OcRJc3w
[msg_05]: https://discord.com/channels/735827593710010369/798936282449182741/1458503196497547401
[gh_05]:
  https://github.com/Ai-Vonie/Sky1984-Sheets-Collection/blob/v26.01.08-v1.2.0/Songs/T/Tokyo%20Ghoul%20-%20Licht%20und%20Schatten%20(Akmigone).txt
[dl_05]:
  https://fixcdn.hyonsu.com/attachments/798936282449182741/1458503194098270322/Tokyo_Ghoul_-_Licht_und_Schatten_Akmigone.txt

<!-- -->

[ms_06]: https://musescore.com/user/81591427/scores/20997538
[yt_06]: https://www.youtube.com/watch?v=BTBPAmcoZZA
[msg_06]: https://discord.com/channels/735827593710010369/798936282449182741/1458503196497547401
[gh_06]:
  https://github.com/Ai-Vonie/Sky1984-Sheets-Collection/blob/v26.01.08-v1.2.0/Songs/I/Interstellar%20Main%20Theme%20–%20Hans%20Zimmer%20-%20Arrangement%20by%20Peter%20Buka.txt
[dl_06]:
  https://fixcdn.hyonsu.com/attachments/798936282449182741/1458503196241690668/Interstellar_Main_Theme_Hans_Zimmer_-_Arrangement_by_Peter_Buka.txt

<!-- -->

[ms_07]: https://musescore.com/user/18619471/scores/5124259
[msg_07]: https://discord.com/channels/735827593710010369/798936282449182741/1457681743531474987
[gh_07]:
  https://github.com/Ai-Vonie/Sky1984-Sheets-Collection/blob/v26.01.08-v1.2.0/Songs/I/Interstellar%20_~%7B%5B%23v3%5D%7D~_.txt
[dl_07]:
  https://fixcdn.hyonsu.com/attachments/798936282449182741/1457681741136396401/Interstellar.txt

<!-- -->

[ms_08]: https://musescore.com/user/81591427/scores/28992002
[yt_08]: https://www.youtube.com/watch?v=1X8Jqn_TMzs
[msg_08]: https://discord.com/channels/735827593710010369/798936282449182741/1458503196497547401
[gh_08]:
  https://github.com/Ai-Vonie/Sky1984-Sheets-Collection/blob/v26.01.08-v1.2.0/Songs/I/in%20the%20pool%20-%20Chainsaw%20Man%20Reze%20Arc%20OST%20–%20Music%20by%20Kensuke%20Ushio%20Arrangement%20by%20Animenz.txt
[dl_08]:
  https://fixcdn.hyonsu.com/attachments/798936282449182741/1458503195541246188/in_the_pool_-_Chainsaw_Man_Reze_Arc_OST_Music_by_Kensuke_Ushio_Arrangement_by_Animenz.txt

<!-- -->

[ms_09]: https://musescore.com/user/81591427/scores/27140323
[yt_09]: https://www.youtube.com/watch?v=m4DF7mAgMoI
[msg_09]: https://discord.com/channels/735827593710010369/798936282449182741/1458779446793211935
[gh_09]:
  https://github.com/Ai-Vonie/Sky1984-Sheets-Collection/blob/v26.01.08-v1.2.0/Songs/O/One%20Last%20Kiss%20-%20Evangelion%203.0%20%2B%201.0%20Theme%20Song%20–%20Music%20by%20Hikaru%20Utada%20Arrangement%20by%20Animenz.txt
[dl_09]:
  https://fixcdn.hyonsu.com/attachments/798936282449182741/1458779446915108992/One_Last_Kiss_-_Evangelion_3.0__1.0_Theme_Song_Music_by_Hikaru_Utada_Arrangement_by_Animenz.txt

<!-- -->

[ms_10]: https://musescore.com/user/2050876/scores/7554869
[msg_10]: https://discord.com/channels/735827593710010369/798936282449182741/1460664377920454832
[gh_10]:
  https://github.com/Ai-Vonie/Sky1984-Sheets-Collection/blob/v26.01.14-v1.2.2/Songs/G/Ghost%20Rule%20-%20DECO%2027%20ft.%20Hatsune%20Miku.HatsuneMiku.txt
[dl_10]:
  https://fixcdn.hyonsu.com/attachments/798936282449182741/1460664375743352977/Ghost_Rule_-_DECO_27_ft._Hatsune_Miku.HatsuneMiku.txt

<!-- -->

[ms_11]: https://musescore.com/user/2050876/scores/5006566
[msg_11]: https://discord.com/channels/735827593710010369/798936282449182741/1460664377920454832
[gh_11]:
  https://github.com/Ai-Vonie/Sky1984-Sheets-Collection/blob/v26.01.14-v1.2.2/Songs/S/Sekai%20Wa%20Koi%20Ni%20Ochiteiru%20-%20Ao%20Haru%20Ride%20OP.txt
[dl_11]:
  https://fixcdn.hyonsu.com/attachments/798936282449182741/1460664376703848681/Sekai_Wa_Koi_Ni_Ochiteiru_-_Ao_Haru_Ride_OP.txt

<!-- -->

[ms_12]: https://musescore.com/user/81591427/scores/19218685
[yt_12]: https://www.youtube.com/watch?v=jC79M6HFOOE
[msg_12]: https://discord.com/channels/735827593710010369/798936282449182741/1458503196497547401
[gh_12]:
  https://github.com/Ai-Vonie/Sky1984-Sheets-Collection/blob/v26.01.08-v1.2.0/Songs/M/Microchip%20–%20Music%20by%20Patrik%20Pietschmann.txt
[dl_12]:
  https://fixcdn.hyonsu.com/attachments/798936282449182741/1458503195864334448/Microchip_Music_by_Patrik_Pietschmann.txt

<!-- -->

[ms_13]: https://musescore.com/user/64980103/scores/13530823
[yt_13]: https://www.youtube.com/watch?v=-jzET1Fe3oo
[msg_13]: https://discord.com/channels/735827593710010369/798936282449182741/1457632458081177833
[gh_13]:
  https://github.com/Ai-Vonie/Sky1984-Sheets-Collection/blob/v26.01.08-v1.2.0/Songs/K/Kamado%20Tanjiro%20no%20Uta%20-%20Go%20Shiina%20feat.%20Nami%20Nakagawa%20(The%20title%20is%20too%20long).txt
[dl_13]:
  https://fixcdn.hyonsu.com/attachments/798936282449182741/1457632457196306442/Kamado_Tanjiro_no_Uta_-_Go_Shiina_feat._Nami_Nakagawa_The_title_is_too_long.txt

<!-- -->

[ms_14]: https://musescore.com/user/38235231/scores/6338677
[msg_14]: https://discord.com/channels/735827593710010369/798936282449182741/1458510115714891849
[gh_14]:
  https://github.com/Ai-Vonie/Sky1984-Sheets-Collection/blob/v26.01.08-v1.2.0/Songs/N/Night%20of%20Nights%20-%20COOL%26CREATE%20Marasy8.txt
[dl_14]:
  https://fixcdn.hyonsu.com/attachments/798936282449182741/1458510114658189505/Night_of_Nights_-_COOLCREATE_Marasy8.txt

<!-- -->

[ms_15]: https://musescore.com/user/6480061/scores/6443683
[yt_15]: https://www.youtube.com/watch?v=OixrgxwNGyg
[msg_15]: https://discord.com/channels/735827593710010369/798936282449182741/1457447445897281758
[gh_15]:
  https://github.com/Ai-Vonie/Sky1984-Sheets-Collection/blob/v26.01.08-v1.2.0/Songs/Japanese/ナイト・オブ・ナイツ%202020%20(marasy%20arr.).txt
[dl_15]:
  https://fixcdn.hyonsu.com/attachments/798936282449182741/1457447446333624403/2020_marasy_arr..txt

<!-- -->

[ms_16]: https://musescore.com/user/29625/scores/5935037
[msg_16]: https://discord.com/channels/735827593710010369/798936282449182741/1458211093712207964
[gh_16]:
  https://github.com/Ai-Vonie/Sky1984-Sheets-Collection/blob/v26.01.08-v1.2.0/Songs/T/Touhou%20Boss%20Rush!!%20(I).txt
[dl_16]:
  https://fixcdn.hyonsu.com/attachments/798936282449182741/1458211093431193700/Touhou_Boss_Rush_I.txt

<!-- -->

<!-- End of reference links -->

<!-- LTeX: enabled=true -->

---

</details>

> [!NOTE]
>
> ℹ️ **Note:** Other conversion examples can be found in the channel history by checking messages
> near the links provided above (around the same dates).

### 📝 Usage Recommendations

For the best results, follow these recommended steps:

0. **Where to find MIDI files:** There are many ways to search for or generate MIDI files, but the
   easiest option is to check out the
   **[dl-librescore](https://github.com/LibreScore/dl-librescore)** repository for
   **[MuseScore](https://musescore.com/)** site.
1. **Source Selection:** Use MIDI files with a clear structure (e.g., _Piano Solo_ versions); avoid
   orchestral files with dozens of tracks.
2. **File Naming:** Before converting, rename the MIDI file to how you want the song title to
   appear.
   - The script uses the filename to populate the internal `"name"` field of the sheet.
   - It is recommended to remove unnecessary parts from the filename (e.g., _[Piano Solo]_,
     _«Synthesia»_, etc.) beforehand. If you forget to do this, you can manually edit the `"name"`
     field inside the JSON file later.
3. **Result Verification:** To listen to and verify the resulting sheet, use the **_Composer_** on
   _[Sky Music Nightly](https://sky-music.specy.app/composer)_ site, as the tool generates JSON
   sheets specifically valid for this site.
4. **Editing and Polishing:** In the _Composer_ settings, refine the sheet to _perfection_:
   - Adjust the **Pitch** and/or change the **Instrument**.
   - For a more atmospheric sound, enable echo by adjusting the **Base Reverb** parameter.
   - Manually fix "defective" areas like **glissandos** and **arpeggios**. It is better to
     transpose, thin out, or redraw these moments manually.
5. **Speed Correction:** If the automatic mode (`Auto_Scroll`) selected an incorrect BPM multiplier
   and the total duration differs from the original by 10–20 seconds or more, try regenerating the
   file with `Auto_Scroll` disabled and selecting the value manually via the `Manual_Multiplier`
   parameter.

> [!NOTE]
>
> ℹ️ **Note:** If the selected MIDI file contains a very large number of notes (several tens of
> thousands), the conversion process may take from one to several minutes.

<!-- -->

> [!TIP]
>
> **📢 Share the result!** Don't forget to share the converted skysheet file with others on the
> **[SkyAutoMusic](https://discord.gg/wzjWKyJtmk)** (**`https://discord.gg/wzjWKyJtmk`**) Discord
> server in the
> [**🎹 music / 🎶share-songs**](https://discord.com/channels/735827593710010369/798936282449182741)
> channel.

<p align="right">
  <a href="#sky1984-sheets-collection">↑ Back to top</a>
</p>

---

## 💭 Why?

The idea to create this collection came up two years ago, but back then I switched to other games,
where I also continued my path as a musical bard.

When I had some free time in FF XIV, I decided to just do it, because existing alternatives and
other library options didn't satisfy me with their implementation or organizational approach for
using these sheets in other games. The repository itself was assembled in a couple of evenings.

## ⚙️ Technical Details

Initially, ±59,457 files were collected. The final collection is the result where duplicates were
removed, and files with the most "quality" internal content and filename were retained.

A custom algorithm was used for filtering duplicates with the following logic:

1. **Exact Duplicates:** Comparison by SHA-256 file hash.
2. **Structural Duplicates:** Analysis of JSON metadata content.
3. **Exact Layer Variants:** Comparison of exact note signatures to identify different key
   variations of the same chart.
4. **Fuzzy Layer Variants:** Comparison of note signatures to identify different key variations with
   slight deviations (with a similarity threshold of ~97%).
5. **Fuzzy Content Matching:** Comparison of full note sequences within the same BPM group to
   identify similar arrangements (with a similarity threshold of ~80%).

> [!NOTE]
>
> ℹ️ **Note:** Some files were allowed into the repository if song variations were encountered
> (e.g., _Easy/Hard_, _V1/V2_, _Multi/Solo Sheets_ and other possible options).

## ⚖️ Legal & Copyright

### Repository

The code, scripts, and tools created for this repository are licensed under the
[**WTFPL**](LICENSE).

### Sheet Music Collection

The collection curation and the converted file formats (JSON/TXT) are dedicated to the public domain
under [**The Unlicense**](LICENSE).

The repository owner **waives all rights** to the compilation itself. However, please note:

- **Original Compositions:** All rights belong to their respective composers, publishers, and
  copyright holders.
- **Transcriptions:** Rights to the specific musical arrangements belong to the original authors who
  created the MIDI/Sheet files.

This collection is provided strictly for **archival purposes**.
