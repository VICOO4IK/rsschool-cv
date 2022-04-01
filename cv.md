# Viktoryia Duhina
********* 
## Contact information:

**Phone:** +375 44 7400142

**E-mail:** vika.vika.dugina@gmail.com

**Telegram:** @ViCOOL4ik

[LinkedIn](https://www.linkedin.com/in/viktoryia-duhina-8aba17b1)

********* 
## About Me

I am 28 years old, I work as a teacher of mathematics and computer science at the gymnasium, I also work as a coach at [Teen Academy](https://iteen.by/), courses taught are robotics, scratch programming, web technologies and the creation of mobile VR and AR applications and games in Unity. Every year I take more and more new courses because it's all interesting to me, but this year I decided that I need to stop and be an expert in at least one area rather than be in all areas superficially, that's why I decided to enroll in these courses.


********* 
## Skills

* HTML
* CSS
* JavaScript (Basic)
* Git

********* 
## Code Example
Example of creating a modal window on a website by clicking on a button:
```
const btn = document.getElementById('open-modal');
const modal = document.getElementById('modal1');

const closeBtn = document.querySelector('.modal_close');

btn.onclick =() => {
    modal.classList.add("modal_active");
    closeBtn.addEventListener('click', closeModal);

    modal.addEventListener('click', hideModal);

    function closeModal(){
        modal.classList.remove("modal_active");
        closeBtn.removeEventListener('click', closeModal);
        modal.removeEventListener('click', hideModal);
    }

    function hideModal(event){
        if (event.target === modal){
            closeModal();
        }
    }
};
```
********* 
## Education

Maxim Tank Belarusian State Pedagogical University, mathematics and computer science major

********* 

## Languages

* Russian - native speaker.

* English - A2 (B1 in process…)
