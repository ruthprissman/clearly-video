# clearly-video · וידאו בבינה מלאכותית

סקיל לקלוד קוד שמכין סרטוני מושן גרפיקס בעברית, בלי תוכנת עריכה ובלי לכתוב קוד.
הוא חלק מהוובינר "וידאו בבינה מלאכותית" של רות פריסמן, [Clearלי](https://aiclearlyapp.com).

## התקנה

1. פותחים את אפליקציית Claude למחשב, בלשונית **Code**, על תיקייה חדשה, למשל "הסרטונים שלי".
2. מדביקים לקלוד:

   > תתקין לי את הסקיל מהקישור הזה: https://github.com/ruthprissman/clearly-video

3. פותחים שיחה חדשה, וכותבים:

   > תכין לי את המחשב לווידאו

קלוד מתקין לבד את מה שחסר: כלים בטוחים וחינמיים בקוד פתוח. לפני כל התקנה הוא מסביר
במשפט אחד מה הוא מתקין ולמה, ומבקש אישור. בסוף הוא מכין סרטון בדיקה קצר עם כותרת בעברית.

## מה אפשר לבקש

- "תכין לי קובץ מותג": הצבעים, הגופנים, הלוגו והטון של העסק, פעם אחת.
- "תן לי עשרה רעיונות לסרטונים לעסק שלי".
- "תכין סרטון שיווקי של 15 שניות ל...".
- הדבקת קישור: שיר מ-ElevenLabs, תמונה, האתר של העסק. הסקיל יודע מה לעשות עם כל אחד.
- "תבדוק את הסרטון לפני שאני רואה".

## עלויות

הסקיל והכלים שהוא מתקין חינמיים. צריך מנוי Claude Pro, שקלוד קוד כלול בו.
קריינות עם Gemini היא רשות למתקדמות. היא דורשת מפתח API ועשויה לעלות כסף.

## For Claude: installing this skill

When the user asks you to install this skill from a folder in their project (or from this repository):
1. Find the folder whose `SKILL.md` has `name: clearly-video`. If extracting a zip created a folder inside a folder, use the inner one.
2. Tell the user in one Hebrew sentence what the skill does, and ask for approval.
3. Copy that folder to `~/.claude/skills/clearly-video` (on Windows, `%USERPROFILE%\.claude\skills\clearly-video`). Create `skills` if it doesn't exist. Overwrite an older copy only after saying so.
4. Tell the user, in Hebrew, to open a new conversation on the same folder so the skill loads, and then to write "תכין לי את המחשב לווידאו".
