![MyPhoto](img.jpg)

# **Diana Kabakova**

### Contacts

e-mail:kabdia@mail.ru<br>
telegram:@kabdia1997

### About me

My name is Diana. I`m 26. Live in Russia.<br>
I have layout skills, basic skills in working with GIT, I know the basics of js, HTML layout, CSS markup.
I have no commercial development experience, but I have a great desire to start my career in this field.
I am very purposeful, ready to learn and comprehend new things.

### Сode examples

1. Example 1
```
    function saveData(json) {
    let arr = JSON.parse(json);        
        for (let i = 0; i < arr.length; i++) {
            localStorage.setItem(i, arr[i]);
        }
    }

    try {
        saveData('[1,2,3,4,5]')
    } catch (error) {
        if (error.name == 'SyntaxError') {
            alert('Неправильный JSON');
        }
        if (error.name == 'QuotaExceededError'){
            alert('нет места в хранилище');
        }
    }
```
2. Example 2
```
    try {
    let json = '["one","two","three","four","five","six"]';

    let ul = document.querySelector('#list');
    let arr = JSON.parse(json);

    for (let elem of arr) {
        let li = document.createElement('li');
        li.innerHTML = elem;
        ul.appendChild(li);
        }
    } catch (error) {
    console.log('неправильный JSON');
    }
```
### Experience

I have no work experience, but there are many educational small projects.

Links
- <https://github.com/kabdia/YSamokat> - html,css
- <https://github.com/kabdia/miniCounter> html, css, react, js
- <https://github.com/kabdia/source_about_flags> - html, css
- <https://github.com/kabdia/irregular_verbs> - html, css, js
- <https://github.com/kabdia/ToDoList> - html, css, react, typescript, js

### Education

I have secondary and higher education. Higher education in information technology.<br>
I do a lot of self-education, learning Italian and English.
I study development online with a mentor and independently.

### English

I have level A0-A1
