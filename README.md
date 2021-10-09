# AnLinkTranslation

What's this?
---
AnLink translation repository

What's AnLink?
---
It's a free software you can operate your phone on PC.  
AnLink is inspired by scrcpy, specially thanks to https://github.com/Genymobile/scrcpy/tree/master/server .  
Download it from https://anl.ink/ .

How to make a new language translation?
---
Download a copy of `template.lang`, then fill the item after `=`.
Language code(LangID) should be one of these items:
```
'am', 'ar', 'bn', 'bg', 'ca', 'cs', 'da', 'de', 'el', 'en-GB', 'es', 'es-419', 'et', 'fi', 'fa', 'fil', 'fr', 'gu', 'hi', 'hr', 'hu', 'id', 'is', 'it', 'iw', 'ja', 'kn', 'ko', 'lt', 'lv', 'ml', 'mr', 'ms', 'nl', 'no', 'or', 'pl', 'pt-BR', 'pt-PT', 'ro', 'ru', 'sk', 'sl', 'sr', 'sv', 'sw', 'ta', 'te', 'th', 'tr', 'uk', 'ur', 'vi', 'zh-CN', 'zh-HK', 'zh-TW'
```
Translation file name should be the language words in that language.  
Eg: `日本語.lang` for Japanese, `LangID` should be `ja`.  
Keep in mind some placeholders shouldn't be translated: `%s %d AnLink`.

How to update the language file?
---
Download this repository, then drag the language file which to be update on the `Translation.exe`.  
You will be able to edit the additional items in language file.

How to submit or correct translation?
---
Fork this repository and make a new pull request.  
AnLink will respect your contribution, and get agreement with you if integrating the translation in software package.

Thank you for the contribution
---
> Our goal is to develop and publish high quality and user-friendly software that provides convenient experience for you.

Contributors:
---
Japanese: AnLink Employee  
Simplified Chinese: [LuanJian](https://github.com/LuanJian) [FallenXtar](https://github.com/FallenXtar) [Crystal-RainSlide](https://github.com/Crystal-RainSlide)  
Traditional Chinese (zh-HK): [xnadnad](https://github.com/xnadnad) [nicolas-chan-42](https://github.com/nicolas-chan-42)  
Traditional Chinese (zh-TW): [SiderealArt](https://github.com/SiderealArt)  
Serbian: [bzzrak](https://github.com/bzzrak)
