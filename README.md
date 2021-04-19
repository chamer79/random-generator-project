# Project Overview

## Project Name

Virtual Happy Heure  (Virtual Happy Hour)

## Project Description

A website that will randomly generate a cocktail recipe, with image, based on the based spirit choosen.

## API and Data Sample
[The CocktailDB.com] {https://www.thecocktaildb.com/api.php}

```json
{
    "drinks": [
        {
            "strDrink": "3-Mile Long Island Iced Tea",
            "strDrinkThumb": "https://www.thecocktaildb.com/images/media/drink/rrtssw1472668972.jpg",
            "idDrink": "15300"
        },
        {
            "strDrink": "69 Special",
            "strDrinkThumb": "https://www.thecocktaildb.com/images/media/drink/vqyxqx1472669095.jpg",
            "idDrink": "13940"
        },
        {
            "strDrink": "A1",
            "strDrinkThumb": "https://www.thecocktaildb.com/images/media/drink/2x8thr1504816928.jpg",
            "idDrink": "17222"
        },
        {
            "strDrink": "Abbey Cocktail",
            "strDrinkThumb": "https://www.thecocktaildb.com/images/media/drink/mr30ob1582479875.jpg",
            "idDrink": "17834"
        }
   ]
}	
```

API data sample for requesting a random cocktain recipe
```json
{
    "drinks": [
        {
            "idDrink": "11007",
            "strDrink": "Margarita",
            "strDrinkAlternate": null,
            "strTags": "IBA,ContemporaryClassic",
            "strVideo": null,
            "strCategory": "Ordinary Drink",
            "strIBA": "Contemporary Classics",
            "strAlcoholic": "Alcoholic",
            "strGlass": "Cocktail glass",
            "strInstructions": "Rub the rim of the glass with the lime slice to make the salt stick to it. Take care to moisten only the outer rim and sprinkle the salt on it. The salt should present to the lips of the imbiber and never mix into the cocktail. Shake the other ingredients with ice, then carefully pour into the glass.",
            "strInstructionsES": null,
            "strInstructionsDE": "Reiben Sie den Rand des Glases mit der Limettenscheibe, damit das Salz daran haftet. Achten Sie darauf, dass nur der äußere Rand angefeuchtet wird und streuen Sie das Salz darauf. Das Salz sollte sich auf den Lippen des Genießers befinden und niemals in den Cocktail einmischen. Die anderen Zutaten mit Eis schütteln und vorsichtig in das Glas geben.",
            "strInstructionsFR": null,
            "strInstructionsIT": "Strofina il bordo del bicchiere con la fetta di lime per far aderire il sale.\r\nAvere cura di inumidire solo il bordo esterno e cospargere di sale.\r\nIl sale dovrebbe presentarsi alle labbra del bevitore e non mescolarsi mai al cocktail.\r\nShakerare gli altri ingredienti con ghiaccio, quindi versarli delicatamente nel bicchiere.",
            "strInstructionsZH-HANS": null,
            "strInstructionsZH-HANT": null,
            "strDrinkThumb": "https://www.thecocktaildb.com/images/media/drink/5noda61589575158.jpg",
            "strIngredient1": "Tequila",
            "strIngredient2": "Triple sec",
            "strIngredient3": "Lime juice",
            "strIngredient4": "Salt",
            "strIngredient5": null,
            "strIngredient6": null,
            "strIngredient7": null,
            "strIngredient8": null,
            "strIngredient9": null,
            "strIngredient10": null,
            "strIngredient11": null,
            "strIngredient12": null,
            "strIngredient13": null,
            "strIngredient14": null,
            "strIngredient15": null,
            "strMeasure1": "1 1/2 oz ",
            "strMeasure2": "1/2 oz ",
            "strMeasure3": "1 oz ",
            "strMeasure4": null,
            "strMeasure5": null,
            "strMeasure6": null,
            "strMeasure7": null,
            "strMeasure8": null,
            "strMeasure9": null,
            "strMeasure10": null,
            "strMeasure11": null,
            "strMeasure12": null,
            "strMeasure13": null,
            "strMeasure14": null,
            "strMeasure15": null,
            "strImageSource": "https://commons.wikimedia.org/wiki/File:Klassiche_Margarita.jpg",
            "strImageAttribution": "Cocktailmarler",
            "strCreativeCommonsConfirmed": "Yes",
            "dateModified": "2015-08-18 14:42:59"
        }
    ]
}
```

## Wireframes

[Wireframe]{https://www.figma.com/file/4t0l59CGg28AkRKUjPtDjV/Virtual-Happy-Heure-Desktop?node-id=3%3A2}

### MVP/PostMVP

#### MVP 

-Add HTML & connect all files.
-Create dynamic dropdown menu.
-Create form option tags.
-Get option value tag.
-Event handler for form. 
-API request for ingredients data.
-API request for random cocktail data.
-Connecting both APIs together.
-Create dynamic tags & append to the DOM: imageb & article.
-Remove previous results.
-Style with CSS.
-CSS responsive design.
-Ding! Done!!

#### PostMVP  

-Add a cocktail shaker animation.
-Add a " Feeling Lucky" button that produce a randomly generated cocktail option.
-Adding images to each option on the dropdown menu.
-Add a gradient effect to the header's background image.
-Ask a UX student for input.

## Project Schedule

|  Day | Deliverable | Status
|---|---| ---|
|April 16-18| Prompt / Wireframes / Priority Matrix / Timeframes | Incomplete
|April 19| Project Approval | Incomplete
|April 20| Core application structure (HTML, CSS, etc.) | Incomplete
|April 20| Pseudocode / Dropdown menu code | Incomplete
|April 20| Requesting APIs: ingredients & random cocktail | Incomplete
|April 20| Connecting both APIs | Incomplete
|April 21| Dynamic tags & append to DOM  | Incomplete
|April 21| Remove previous results  | Incomplete
|April 22| CSS | Incomplete
|April 23| Presentations | Incomplete

## Priority Matrix

[Priorty Matrix] {https://www.figma.com/file/UzrCJwd54pW3og75mxgyht/Virtual-Happy-Heure-Priority-Matrix?node-id=0%3A1}

## Timeframes

| Component | Priority | Estimated Time | Time Invested | Actual Time |
| --- | :---: |  :---: | :---: | :---: |
| Adding Form | M | 3hrs| 0hrs | 0hrs |
| Dropdown Menu | H | 4hrs| 0hrs | 0hrs |
| Requesting Ingredient API | H | 5hrs| 0hrs | 0hrs |
| RequestRandom Cocktail API | H | 5hrs| 0hrs | 0hrs |
| Connecting both APIs together | H | 5hrs| 0hrs | 0hrs |
| Dynamic tags & append to DOM: image & article | M-H | 4hrs| 0hrs | 0hrs |
| Remove previous results | H | 4hrs| 0hrs | 0hrs |
| CSS | M | 8hrs| 0hrs | 0hrs |
| Total | H | 38hrs| 0hrs | 0hrs |

## Code Snippet

Describe code snippet proud of & why

```
function reverse(string) {
	// here is the code to reverse a string of text
}
```

## Change Log
 Use this section to document what changes were made and the reasoning behind those changes.  
