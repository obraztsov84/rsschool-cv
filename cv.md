Obraztsov Sergey
Contacts
    Location: Russian Federation, Saint Petersburg
    Email: obraztsov84.rs@gmail.com
    GitHub: obraztsov84
    LinkedIn: https://www.linkedin.com/in/sergei-obraztsov-1483a3227/
About Me
My main strengths are problem solving skills and the ability to analyze complex information. I am good at finding a common language with people and building long-term working relationships. 
I have 10+ years of experience as a manager and a design engineer, including more than 2 years as a department head. I have experience in selling technically complex equipment.
I am interested in IT because it is a fast-growing field with a high demand for intelligent specialists.
Skills
I have some experience with html, css, scss, javascript/typescript, react/next.js.
I use git in CLI as cvs, and gitlab for CI/CD (as a user).
I can create little scripts in Selenium IDE.
Code Example
Example of my code from codewars:
https://www.codewars.com/kata/52742f58faf5485cae000b9a

function formatDuration (seconds) {
  //year=60*60*24*365=31536000 day=86400 hour=3600 min=60
  let arr = [seconds%60 + ' second',
            Math.floor(seconds%3600/60) + ' minute',
            Math.floor(seconds%86400/3600) +' hour',
            Math.floor(seconds%31536000/86400) + ' day',
            Math.floor(seconds/31536000) + ' year'].filter(x=>+x[0]).map(x=>+(x[0]+x[1])>1?x+'s':x);
  switch (arr.length) {      
  case 0: return 'now'; 
  case 1: return arr[0];
  case 2: return arr[1] + ' and ' +arr[0];
  default: arr[1]+= ' and ';
           for (let i=2; i<arr.length;i++) arr[i]+=', ';
           return arr.reverse().join('');
    }
}
I don't use linter or beautifier in this part, bc it's online platform.
Experience
I have been working as an intern/junior front end developer in a hosting company since the 4th quarter of 2021.
Most of my work is updating the design of pages and writing react components for the administrative panel.

Education
I spent five years at Saint Petersburg mining university (http://en.spmi.ru/). I graduated as a mining engeneer. 
I have certification for ISO 9001 as an expert-auditor in 2021. Also I have taken several courses for my engeneering work.
For my IT specialization i start with HTML Academy and some courses on Udemy.com (Ivan Petrechenko courses). 
English
My result indicates that my level of English is somewhere between B1 Intermediate and B2 Upper Intermediate according to the Common European Framework of Reference, also known as the CEFR. I can almost freely read any documentation related to my work specialization, as well as watch training videos on YouTube. 