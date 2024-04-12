# Spam Filter Function
 Regular expressions, often shortened to "regex" or "regexp", are patterns that help programmers match, search, and replace text. Regular expressions are powerful, but can be difficult to understand because they use so many special characters.  In this spam filter project, you'll know about capture groups, positive lookaheads, negative lookaheads, and other techniques to match any text you want.
 REgular Expressions are 
const helpRegex = /please help|assist me/i;
const dollarRegex = /[0-9]+ (?:hundred|thousand|million|billion)? dollars/i;
const freeRegex = /(?:^|\s)fr[e3][e3] m[o0]n[e3]y(?:$|\s)/i;
const stockRegex = /(?:^|\s)[s5][t7][o0][c{[(]k [a@4]l[e3]r[t7](?:$|\s)/i;
const dearRegex = /(?:^|\s)d[e3][a@4]r fr[i1|][e3]nd(?:$|\s)/i;

![1](https://github.com/SamitSaha/Spam-Filter-Function/assets/72096509/a752132f-d060-4e94-b1f1-52ebb41693a9)
