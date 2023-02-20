# Solutions of 20 Basic DOM Manipulation Assignment (Manipulating other sites)

## 1. Dev.to

```js
document.querySelector(".side-bar .crayons-card .crayons-subtitle-2").innerHTML = "Tousif";
document.querySelector(".side-bar .crayons-card p").innerHTML = "I Love Computers";
```

## 2. Apple
```js
let arr = document.querySelectorAll(".as-imagegrid .as-imagegrid-item-title");
let newarr = [...arr].map(i => {
    return i.textContent.replace(" Support", "");
})
console.log(newarr)
```

## 3. Youtube Support
```js
let nav = document.querySelector("nav.accordion-homepage");
let sec = document.createElement("section");
sec.className = "parent";
let h3 = document.createElement("h3");
h3.innerHTML = "My New FAQ";
sec.appendChild(h3);
nav.appendChild(sec);
```

## 4. Oneplus
```js
let num = document.querySelector(".customer-support .one-tel-number.service-number");
num.innerText = '+91 6295302754';
```

## 5. Samsung
```js
let btn = document.querySelector(".listing .mytabs a:last-of-type");
btn.innerText = "Check Out";
```

## 6. Adidas
```js
let search = document.querySelector("input.searchinput___19uW0");
let defaultStyle = search.style;
search.onmouseenter = () => search.style.backgroundColor = 'red';
search.onmouseleave = () => search.style = defaultStyle;
```

## 7. MDN Web Docs
```js
let frm = document.querySelector(".homepage-hero-search #hp-search-form");
frm.elements['hp-search-input'].value = "CSS Selectors";
frm.submit();
```

## 8. Google
```js
let langs = document.querySelectorAll("#SIvCob a");
for(let i=0; i < langs.length; i=i+2){
    langs.item(i).remove();
}
```

## 9. Code Wars
```js
let txt = document.querySelector(".section h1.display-heading-1");
txt.style.fontFamily = 'monospace';
txt.style.color = '#b1361e';
```

## 10. FreeCodeCamp
```js
let button = document.querySelector('a.btn-cta-big .login-btn-text');
button.onmouseover = () => button.style.backgroundColor = 'red';
```

## 11. realme
```js
let logo = document.querySelector(".header.header-main .logo span");
logo.style.backgroundImage = "url('https://ineuron.ai/images/ineuron-logo.png')";
```

## 12. Github
```js
// can't find the button in the site
```

## 13. Hackerrank
```js
let desc = document.querySelector('.entry-content .fl-heading .fl-heading-text');
desc.innerText = "JSBOOTCAMP";
```

## 14. Asus
```js
let txt = document.querySelector(".HotDealsAll__HotCampaignsEventsContainer__FK0V2 .HotDealsAll__Heading__2fIbe");
txt.style.fontSize = '80px';
```

## 15. Dell
```js
let h3 = document.querySelector("#d560824win9b .ps-top .ps-title");
h3.style.textAlign = 'right';
```

## 16. Vercel
```js
let txt = document.querySelector('.section-title_title__VEDfK');
txt.innerHTML = 'Start with Scratch';
```

## 17. Sony
```js
let btn = document.querySelector(".btn-container");
btn.innerHTML = Date().toString();
```

## 18. Philips
```js
let footer = document.querySelector("footer.p-f03-footer-container");
footer.style.background = 'orange';
```

## 19. Canon
```js
let logo = document.querySelector(".navbar .navbar-brand .logo");
console.log(logo.src);
```

## 20. Oppo
```js
let desc = document.querySelector('.desc');
desc.style.color = 'orange';
```