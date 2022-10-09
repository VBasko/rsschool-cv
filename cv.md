# Viktoriia Basko

## FRONTEND DEVELOPER

---

### CONTACTS

+995 595 09 34 85

Telegram: [Viktoriia](https://t.me/VictoriiaBasko)

vvbasko@outlook.com

[Linkedin](https://www.linkedin.com/in/vbasko/)

Batumi, Georgia

Ready to work remotely

### SUMMARY

I'm looking for new opportunities to improve my skills. I'm at the beginning of my professional path but I really enjoy the process. Have basic knowledge in HTML, CSS, JavaScript, API integration and adaptive layouts. Love mathematics and would like to apply all of my skills to make my projects in my best.

### SKILLS

- HTML, CSS3, Bootstrap
- JavaScript Basics
- Git/GitHub, VS Code, Chrome Developer Tools
- Figma, Photoshop

### CODE EXAMPLE

**Multiples of 3 or 5** kata from Codewars:

_If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3, 5, 6 and 9. The sum of these multiples is 23._

_Finish the solution so that it returns the sum of all the multiples of 3 or 5 below the number passed in. Additionally, if the number is negative, return 0 (for languages that do have them)._

    function solution(number){
        sum = 0;
        if (number < 0) {
            return 0;
        }

        for (let i = 0; i < number; i++) {
            if (i % 3 == 0 || i % 5 == 0) {
            sum += i;
            }
        }
        return sum;
    }
