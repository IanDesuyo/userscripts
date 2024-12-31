# userscripts

Some userscripts I use myself

## Scripts

### [UtaTen Enhancer](/utanet-enhancer/user.js)

Enhances the [UtaTen](https://utaten.com/) website by adding a few features:
- Copyable lyrics
  - Enable selecting and copying lyrics
  - Ignore ふりがな(furisgana) texts when selecting

- Better translation for Browser's built-in translation
  - Translate whole lines of lyrics instead of words
  - Only tested on Chrome

- Tool Buttons
  - Copy lyrics
  - ChatGPT Translation
    - Modify the `GPT_TRANSLATE_LANG` and `GPT_PROMPT` variables to change the language and prompt


### [CPE Auto Exam Selector](/cpe-auto-exam-selector/user.js)

Automatically selects the exam site and submit for the [CPE exam registration page](https://cpe.cse.nsysu.edu.tw/cpe/newest).

- Modify the `EXAM_SITE_KEYWORD` and `AUTO_SUBMIT` variables to change the exam site and auto-submit settings
  - `EXAM_SITE_KEYWORD`: The keyword of the exam site. Ex: `逢甲` will match `逢甲大學／資電 125 、資電234 、資電 330【0/210, 0%】`
  - `AUTO_SUBMIT`: Whether to auto-submit the form after selecting the exam site

You still need to login by yourself, or you can try this [Python script](https://github.com/IanDesuyo/CPEBot).
