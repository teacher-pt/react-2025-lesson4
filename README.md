# GitHub HowTO
## first user
```bash
>> git init # מאתחל את הפרויקט כפרויקט עם גיט מקומי - פעם אחת

>> git add .  # בכל שינוי
>> git commit -m "..." # בכל שינוי


>> git remote add origin <github_url> # פעם אחת
>> git branch -M main # פעם אחת
>> git push -u origin main # פעם אחת

>> git push # בכל שינוי - דחיפה של השינויים שעשינו לגיטהאב
>> git fetch # בדיקה האם יש הבדלים בין הפרויקט המקומי לגיטהאב
>> git pull # משיכה של כל השינויים מהגיטהאב לפרויקט המקומי
```


## second user
```bash
>> git clone <github_url> # מעתיק פרויקט קיים מהגיטהאב למחשב המקומי - פעם אחת

>> git add .  # בכל שינוי
>> git commit -m "..." # בכל שינוי

>> git push # בכל שינוי - דחיפה של השינויים שעשינו לגיטהאב
>> git fetch # בדיקה האם יש הבדלים בין הפרויקט המקומי לגיטהאב
>> git pull # משיכה של כל השינויים מהגיטהאב לפרויקט המקומי
```

## generally
- `git push`
- there is merge conflict:
 - `git fetch` 
 - `git pull` 
 - in vscode fix conflict
 - `git commit -am ...`
 - `git push`