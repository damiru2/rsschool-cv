# Chalkarov Damir

## Contact information:

**Phone:** +7-708-682-99-64 <br />
**E-mail:** chalkarov11@mail.ru <br />
**Telegram**: @razdvau2 <br />
[LinkedIn](https://www.linkedin.com/in/damir-chalkarov-251ba7219/)

---

### Briefly about myself:

I started my career in a Kazakh-Italian company in my home country of Kazakhstan as an information technology inspector.
I have been working in this field for 5 years now.
Recently, I began to get involved in programming, studied the basic course on Python, and studied the Swift language for about 10 months.
My main goal is to become a good, in-demand programmer. My purposefulness, my diligence and dedication will help me in this.
I always try to learn new, unfamiliar things in the field of IT, every day after work I devote time to self-development.
Recently, on the advice of friends, I began to study front-end and decided to become a specialist in this particular direction.

---

### Skills and Proficiency:

- Microsoft services;
- Network;
- HTML5, CSS3;
- JS basics;
- Python basics;
- Swift basics;
- VS Code.

---

### Code example:

**Total amount of points from CODEWARS**.
_Our football team has finished the championship._ <br />
_Our team's match results are recorded in a collection of strings. Each match is represented by a string in the format "x:y", where x is our team's score and y is our opponents score.
Points are awarded for each match as follows_: <br />
_if x > y: 3 points (win); <br />
if x < y: 0 points (loss); <br />
if x = y: 1 point (tie)._ <br />
_We need to write a function that takes this collection and returns the number of points our team (x) got in the championship by the rules given above._

```
function points(games) {
    let points = 0
for (let score of games) {
    let result = score.split(":")
    if (result[0] > result[1]) {
        points += 3
    } else if (result[0] == result[1]) {
        points += 1
    }
}
    return points
}
```

---
