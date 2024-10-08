## Install-additional-Languages.md

### 1. Install needed Languages

* **Prologue:** i installed my "CachyOS" choosing English as default language and setting Germany as Country i live. No
Linux i know install the dictionaries by default yet. So, these are to be installed when OS-setup is completed. This is
necessary if you want to use the "Spell Check" in the Apps of your OS and/or eliminating errors by starting some apps
using dictionaries.

`sudo pacman -S --needed --noconfirm hunspell-en hunspell-de aspell-en aspell-de`

* That's at least necessary to setup the spell-check of your OS.
  
**Attention!**

* Under Plasma DE open `systemsettings` & click **"Language & Time / Spell Check/"** & disable:
**"✅ Enable autodetection of language"** 🟰 uncheck this box❗️



### 2. Alternatives

* If you have enough place on your data-carrier or are polyglot… you can install all available dictionaries for all
languages with following two commands:

```
sudo pacman -S --needed --noconfirm $(pacman -Ssq ^hunspell-)

sudo pacman -S --needed --noconfirm $(pacman -Ssq ^aspell-)
```

**"✅ Done & Enjoy❗️**


