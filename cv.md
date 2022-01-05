Obraztsov Sergey
obraztsov84.rs@gmail.com
Инженерное образование и аналитический склад ума. 
10+ опыт работы в обасти конструирования, 2+ года опыт работы как менеджера проекта, 1 год опыт продаж.
I'm interested in IT 
I have some experience with html, css, scss, javascript/typescript, react/next.js.
I use git in CLI as cvs, and gitlab for CI/CD (as a user).

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

I spent five years at Saint Petersburg mining university (http://en.spmi.ru/). I graduated as a mining engeneer. 
I have certification for ISO 9001 as an expert-auditor in 2021. Also I have taken several courses for my engeneering work.

My result indicates that my level of English is somewhere between B1 Intermediate and B2 Upper Intermediate according to the Common European Framework of Reference, also known as the CEFR. I can almost freely read any documentation related to my work specialization, as well as watch training videos on YouTube. 





Краткая информация о себе (ваша цель и приоритеты, подчеркните свои сильные стороны, расскажите о своём опыте работы, если опыта работы нет, расскажите о своём стремлении учиться и узнавать новое)
Навыки (языки программирования, фреймворки, методологии, системы контроля версий и инструменты разработки, которыми вы владеете)
Примеры кода
Опыт работы. Junior Dev может перечислить учебные проекты с указанием использованных навыков и ссылками на исходный код.
Образование (включая пройденные курсы и тренинги)
Английский язык (уровень английского языка, если была языковая практика, расскажите о ней)