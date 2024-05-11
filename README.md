# Certification-Professional-Data-Scientist-DataCamp-
Certification and Project Overview for DataCamp's Data Scientist Professional Certificate Program
![data_scientist_linkedin](https://github.com/GOMEZBORIS6/Certification-Professional-Data-Scientist-DataCamp-/assets/84849041/58e4efd5-6aff-4228-87ba-82432810fa5c)

# Practical Exam - Recipe Site Traffic

## About Tasty Bytes

Tasty Bytes was founded in 2020 in the midst of the Covid Pandemic. The world wanted inspiration so we decided to provide it. We started life as a search engine for recipes, helping people to find ways to use up the limited supplies they had at home. Now, over two years on, we are a fully fledged business. For a monthly subscription we will put together a full meal plan to ensure you and your family are getting a healthy, balanced diet whatever your budget. Subscribe to our premium plan and we will also deliver the ingredients
to your door.

**Example Recipe**
This is an example of how a recipe may appear on the website, we haven’t included all of the steps but you should get an idea of what visitors to the site see.

*Tomato Soup*
**Servings:** 4
**Time to make:** 2 hours
**Category:** Lunch/Snack
**Cost per serving:** $

| Nutritional Information (per serving) |     |
|---------------------------------------|-----|
| Calories                              | 123 |
| Carbohydrate                          | 13g |
| Sugar                                 | 1g  |
| Protein                               | 4g  |

**Ingredients:**
- Tomatoes
- Onion
- Carrot
- Vegetable Stock

***

## Data Information

The product manager has tried to make this easier for us and provided data for each recipe, as well as whether there was high traffic when the recipe was featured on the home page. As you will see, they haven’t given us all of the information they have about each recipe. You can find the data [here](./Presentation%20and%20Workbook/recipe_site_traffic_2212.csv). I will let you decide how to process it, just make sure you include all your decisions in your report. Don’t forget to double check the data really does match what they say - it might not.

### *Dataset Description*

<table>
    <tr>
        <th><center> Column Name </center></th>
        <th><center> Details </center></th>
    </tr>
    <tr>
        <td><center> recipe </center></td>
        <td><center> Numeric, unique identifier of recipe </center></td>
    </tr>
    <tr>
        <td><center> calories </center></td>
        <td><center> Numeric, number of calories </center></td>
    </tr>
    <tr>
        <td><center> carbohydrate </center></td>
        <td><center> Numeric, amount of carbohydrates in grams </center></td>
    </tr>
    <tr>
        <td><center> sugar </center></td>
        <td><center> Numeric, amount of sugar in grams  </center></td>
    </tr>
    <tr>
        <td><center> protein </center></td>
        <td><center> Numeric, amount of protein in grams  </center></td>
    </tr>
    <tr>
        <td><center> category </center></td>
        <td><center> Character, type of recipe. Recipes are listed in one of ten possible groupings (Lunch/Snacks', 'Beverages', 'Potato', 'Vegetable', 'Meat', 'Chicken, 'Pork', 'Dessert', 'Breakfast', 'One Dish Meal').  </center></td>
    </tr>
    <tr>
        <td><center> servings </center></td>
        <td><center> Numeric, number of servings for the recipe  </center></td>
    </tr>
    <tr>
        <td><center> high_traffic </center></td>
        <td><center> Character, if the traffic to the site was high when this recipe was shown, this is marked with “High”. </center></td>
    </tr>
</table>

## Written Report

Your written report should include written text summaries and graphics of the following:

- **Data validation:**
    - Describe validation and cleaning steps for every column in the data
- **Exploratory Analysis** to answer the customer questions ensuring you include:
    - Two different types of graphic showing single variables only
    - At least one graphic showing two or more variables
    - Description of your findings
- **Model Development** including:
    - What type of problem this is
    - Fitting a baseline model
    - Fitting a comparison model
- **Model evaluation**
    - Show how the two models compare
- Definition of a **metric for the business to monitor**
    - How should the business monitor what they want to achieve?
    - Estimate the initial value(s) for the metric based on the current data?
- **Final summary including recommendations** that the business should undertake


***Questions to need answers in this Exam:***

Can your team:
- Predict which recipes will lead to high traffic?
- Correctly predict high traffic recipes 80% of the time?
