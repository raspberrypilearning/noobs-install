### NOOBS බාගත කිරීම

ඔබගේ SD කාඩ් පතේ Raspbian ස්ථාපනය (install) කිරීමට ඇති පහසුම ක්‍රමය NOOBS භාවිතා කිරීමයි. NOOBS හි පිටපතක් (copy එකක්) ලබා ගැනීම සඳහා:

+ [www.raspberrypi.org/downloads/](https://www.raspberrypi.org/downloads/) වෙත පිවිසෙන්න. 

![බාගැනීම්(Download) පිටුව](images/downloads-page.png)

+ NOOBS ලිපිගොනු (files) වෙත සබැඳියක් (link එකක්) ඇති කොටුවක් ඔබට දැකිය හැකිය. සබැඳිය (link එක) මත ක්ලික් (click) කරන්න.

![NOOBS මත ක්ලික් කරන්න](images/click-noobs.png)

+ සරලම ක්‍රමය වන්නේ, zip කල ලිපිගොනු (files) වල සංරක්ෂිතය (archive එක) බාගත (download) කිරීමයි.

![zip ගොනුව බාගන්න](images/download-zip.png)

### SD කාඩ්පත ෆොමැට් කිරීම

ඔබ විසින් Raspbian ස්ථාපනය (install) කිරීමට බලාපොරොත්තු වන SD කාඩ් පතේ දැනට පැරණි Rasbian අනුවාදයක් (version එකක්) තිබේ නම්, මෙම ක්‍රියාවලියේදී ලිපිගොනු (files) නැවත ලියනු (overwritten) ලබන බැවින්, කාඩ්පතේ ඇති ගොනු (files) පළමුව උපස්ථ (backup) කිරීම වඩා සුදුසු වේ.

+ SD Association ගේ වෙබ් අඩවියට පිවිස [SD ආකෘති කාරකය(Formatter) 4.0](https://www.sdcard.org/downloads/formatter_4/index.html) වින්ඩෝස්(Windows) හෝ මැක්(Mac) සඳහා බාගත කරගන්න.

+ මෘදුකාංගය (software) ස්ථාපනය (install) කිරීම සඳහා ලබදී ඇති උපදෙස් (instructions) අනුගමනය කරන්න.

+ ඔබේ SD කාඩ් පත පරිගණකයට හෝ ලැප්ටොප් පරිගණකයේ SD කාඩ් කියවනය තුළට ඇතුළු කර, ඒ සඳහා වෙන් කර ඇති ධාවක (drive) අකුර (letter එක) සටහන් කරගන්න, උදා. `F: /`.

+ Zip සංරක්ෂිතයෙන් (archive එකෙන්) NOOBS උකහා ගැනීම (extracting.

### Zip සංරක්ෂිතයෙන් (archive එකෙන්) NOOBS උකහා ගැනීම (extract)

ඊළඟට, ඔබ Raspberry Pi වෙබ් අඩවියෙන් බාගත(download) කළ NOOBS zip සංරක්ෂිතයෙන්, ගොනු(files) උකහා (extract) ගත යුතුය.

+ දැන් ඔබගේ *බාගැනීම්(Downloads)* ෆෝල්ඩරය(folder එක) වෙත ගොස් ඔබ බාගත කළ zip ගොනුව(file එක) සොයා ගන්න.

+ ලිපිගොනු(files) උකහාගැනීම(extract) සිදුකර, එහි ප්‍රතිඵලයක් ලෙස එන එක්ස්ප්ලෝරර් / සෙවුම්(Explorer/Finder) කවුළුව(window එක) විවෘතව තබාගන්න.

### ලිපිගොනු පිටපත් කිරීම

+ දැන් තවත් එක්ස්ප්ලෝරර්/සෙවුම් (Explore/Finder) කවුළුවක් (window එකක්) විවෘත කර SD කාඩ් පත වෙත යන්න. කවුළු (window) දෙක එක ළග ස්ථානගත (side by side) කිරීම වඩාත් සුදුසුය.

+ *NOOBS* ෆෝල්ඩරයේ (folder එකේ) ඇති සියලුම ගොනු (files) තෝරාගෙන, ඒවා SD කාඩ්පතට ඇද දමන්න (drag කරන්න).

![වින්ඩෝස් පිටපත](images/copy3.png)

![මැක් (mac) මෙහෙයුම් පද්ධති පිටපත](images/macos_copy.png)

+ ලිපිගොනු පිටපත් වූ පසු , micro SD කාඩ්පත ඔබේ Raspberry Pi එක තුළට ඇතුළු කර, Pi එක බල ප්‍රභවයකට (power source එකට) සම්බන්ධ කරන්න.

### NOOBS මගින් බූට් කිරීම

+ ලිපිගොනු පිටපත් වූ පසු , micro SD කාඩ්පත ඔබේ Raspberry Pi එක තුළට ඇතුළු කර, Pi එක බල ප්‍රභවයකට (power source එකට) සම්බන්ධ කරන්න.

+ ස්ථාපකය (installer එක) ලෝඩ් වූවිට එය ඔබට තේරීමක් ලබාදෙයි. මෙයින් ඔබ **Raspbian** සඳහා වූ කොටුව සලකුණු කරන්න, පසුව **ස්ථාපනය බොත්තම (install button)** ක්ලික් කරන්න.

![ස්ථාපනය කරන්න](images/install.png)

+ අනතුරු ඇඟවීමේ පණිවිඩයට **ඔව්(Yes)** ක්ලික් කරන්න, පසුව වාඩි වී විවේකීව බලාසිටින්න. එයට ටික වේලාවක් ගතවනු ඇත, නමුත් Raspbian ස්ථාපනය(install) වනු ඇත.

![ස්ථාපනය කරමින්](images/installing.png)

+ Raspbian ස්ථාපනය (install) වී අවසන් වූ විට, **හරි (OK)**ක්ලික් කරන්න, එවිට ඔබේ Raspberry Pi එක නැවත ආරම්භ (restart) වන අතර Raspian ආරම්භ (boot) වේ.

![ස්ථාපනය කර ඇත](images/installed.png)