# Feature_Toggle

```javascript
// Определение Feature Toggles
const featureToggles = {
    newFeature: true,
    betaFeature: false
};

// Использование Feature Toggle в коде
function renderPage() {
    console.log('Отображение основной страницы');

    if (featureToggles.newFeature) {
        console.log('Отображение новой функции');
    }

    if (featureToggles.betaFeature) {
        console.log('Отображение бета-функции');
    } else {
        console.log('Бета-функция отключена');
    }
}

// Вызов функции рендеринга страницы
renderPage();
```
