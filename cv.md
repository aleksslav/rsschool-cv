# Slav Aleksandr

+7 952 234 32 45 · Viber · WhatsApp · Telegram · Saint Petersburg, Russian Federation · [Aleksslav@gmail.com]

# Summary:

Hello, I’m a Aleksandr, web-developer based in Saint Petersburg. I am 34 years old. I am a process engineer. Recently I decided to change my life and become a Front-end developer. Now I am taking a course at the HTML Academy and «JavaScript/Front-end» at RS School. I have some experience in designing, building and customizing websites. 

## Skills:

 * Languages: HTML, CSS, Javascript (basics), PHP (basics);
 * Web libs:  Bootstrap, jQuery, Materialize;Responsive design;
 * Web Dev tools: Gulp, npm; 
 * VCS: Git basics;
 * DB: MySQL, MongoDB Atlas (basic set of queries);
 * Graphic editors: ADOBE Photoshop, CorelDRAW, Google Web Designer;

## Code Example:

```
const overlayModal = document.querySelector('.modal-overlay');
const catalogBlock = document.querySelector('.catalog');
const orderButton = document.querySelector('.popular-product__order');

if (overlayModal) {
  if (catalogBlock) {
    catalogBlock.addEventListener('click', openOrderForm);
  }

  if (orderButton) {
    orderButton.addEventListener('click', openOrderForm);
  }

  overlayModal.addEventListener('click', closeOrderForm);
  window.addEventListener('keydown', closeOrderForm);
}

function openOrderForm(event) {
  const element = event.target;

  if (
    element.classList.contains('product-card__button') ||
    element.classList.contains('popular-product__order')
  ) {
    event.preventDefault();
    overlayModal.classList.add('modal-overlay--opened');
  }
}

function closeOrderForm(event) {
  const element = event.target;

  if (element.classList.contains('modal-overlay') || event.keyCode === 27) {
    overlayModal.classList.remove('modal-overlay--opened');
  }
}
```

##Education:

Higher education. Technical University of Moldova.
Engineer-Technologist. 

##Language competencies:

 * Russian: native language
 * English: intermediate (B1)
