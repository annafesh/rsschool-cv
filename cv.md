# **Anna Feschenko**
---
## *Contact information*
* **Email:** work.annafesh@mail.ru
* **[GitHub](https://github.com/annafesh)** 
* **[LinkedIn](https://www.linkedin.com/in/anna-feschenko/)**
---
## *About me*
I'm 22 years old and looking for a new career path and opportunities. Really hardworking and passionate. I've been working in the fast food industry and am ready for anything. 
**My best qualities:**
* fast learner
* team player
* cute smiler
* no stresser when not hungry :3
---
## *Skills*
* HTML
* CSS
* JavaScript
## *Code example*
```
const board = document.querySelector('#board')
const colors = ['AntiqueWhite', 'SeaGreen', 'MediumAquaMarine', 'BlueViolet',
'LightBlue', 'Lavender', 'LavenderBlush', 'LightPink']
const SQUARES_NUMBER = 400

for (let i = 0; i < SQUARES_NUMBER; i++) {
    const square = document.createElement('div')
    square.classList.add('square')

    square.addEventListener('mouseover', ()=> setColor(square))

    square.addEventListener('mouseleave', ()=> removeColor(square))

    board.append(square)
}

function setColor(element) {
    const color = getRandomColor()
    element.style.backgroundColor = color
    element.style.boxShadow = `0 0 2px ${color}, 0 0 10px ${color}`
}

function removeColor(element) {
    element.style.backgroundColor = '#1d1d1d'
    element.style.boxShadow = `0 0 2px #000`
}

function getRandomColor() {
    const index = Math.floor(Math.random() * colors.length)
    return colors[index]
}
```
## *Experience*
Worked on some projects on my courses. Participated in several marathons and contests. Currently learning and gaining practical skills thanks to __*RS School*__. 
Now I'm open to any opportunity and willing to take a part in internships and small projects to gain experience, so feel free to reach out to me `;D`

---
## *Education*
*Website development using HTML, CSS and JavaScript*
**IT Academy**
March 2022 — July 2022

*Web application development with JavaScript*
**IT Academy**
August 2022 — November 2022

---
## *Languages*
__*Russian*__ — native
__*English*__ – C2: [EF SET English Certificate - 77/100](https://www.efset.org/cert/aZuUGV)