# Liya Vysotskaya

## Junior Frontend Developer

### Contact information:

- Location: Saint-Petersburg, Russia
- Phone: +7(917)-774-97-47
- E-mail: Imredrat@yandex.ru
- Telegram: @liya_vysotskaya
- Discord: LiyaVysotskaya
- GitHub: LiyaVysotskaya

***
### About Myself:

At the moment I am a 2nd year student at the Ufa University of Science and Technology with a degree in Applied Mathematics and Informatics, but I decided to try my hand at web development and I liked it. Now I am actively studying in courses and self-studying in this direction.

I consider my strengths to be patience, perseverance, diligence in work, I quickly grasp and process information, I have a creative approach and I learn quickly.

***
### Skills and Proficiency:

- HTML5;
- CSS3;
- BEM methodology;
- JavaScript (basic);
- C++ (basic);
- Python (basic);
- Git;
- GitHub;
- Figma;
- VSCode.

***
### Code example:

**Tasks:**
1. *To implement the functions of opening and closing a popup by clicking on a button;*
2. *Handle editing form submission;*
3. *By default, when opening the form, the value in the input fields is equal to what is displayed in the profile*

```
const editBtn = document.querySelector('.profile__edit-button');
const addBtn = document.querySelector('.profile__add-button');
const closeBtn = document.querySelector('.popup__close-button');
const popup = document.querySelector('.popup');
const form = document.querySelector('.edit');
const profileName = document.querySelector('.profile__name');
const profileDescription = document.querySelector('.profile__description');
const editName = document.querySelector('.edit__input_profile_name');
const editDescription = document.querySelector('.edit__input_profile_description');

function openEditWindow() {
  popup.classList.add('popup_opened');
  editName.value = profileName.textContent;
  editDescription.value = profileDescription.textContent;
}

function closeEditWindow() {
  popup.classList.remove('popup_opened');
}

function handleFormSubmit (evt) {
  evt.preventDefault();
  profileName.textContent = editName.value;
  profileDescription.textContent = editDescription.value;
  closeEditWindow();
}

editBtn.addEventListener('click', openEditWindow);
closeBtn.addEventListener('click', closeEditWindow);
form.addEventListener('submit', handleFormSubmit);
```

***
### Projects:

1. [Traveling in Russia](https://liyavysotskaya.github.io/russian-travel/);
2. [Mesto](https://liyavysotskaya.github.io/mesto/);
3. [CSSBayan](https://liyavysotskaya.github.io/cssBayan/).

***
### Education:

1. Ufa College of Arts, Ufa
    - Faculty of Folk orchestra instruments;
2. Ufa University of Science and Technology, Ufa
    - Faculty of Applied Mathematics and Informatics;
3. Yandex.Prakticum 
    - Course «Web development for beginners»;
4. RS Schools
    - Course «JavaScript/Front-end»;
5. Stepik
    - Course «JavaScript for beginners»;
6. Hexlet
    - Course «JavaScript Basics»;
7. learnjavascript.ru
    - JavaScript Manual.

***
### Languages:

- Russian - Native;
- English - Intermediate/Upper-intermediate.
