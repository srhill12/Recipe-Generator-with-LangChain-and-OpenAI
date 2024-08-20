
# Recipe Generator with LangChain and OpenAI

This project utilizes LangChain and OpenAI's GPT-3.5-turbo model to generate and explore various recipes. By leveraging the capabilities of LangChain, users can receive a list of recipes, select one, and obtain detailed instructions on how to prepare it.

## Features

- **Recipe Listing:** Generates a list of recipes using a language model.
- **Detailed Recipe Instructions:** Provides step-by-step instructions for the selected recipe.
- **Interactive Selection:** Allows users to choose a specific recipe for more details.

## Prerequisites

Before running the code, ensure you have the following installed:

- Python 3.7+
- `langchain`
- `dotenv`

You can install the required Python packages using:

```bash
pip install langchain python-dotenv
```

## Setup

1. **Set Up the Environment Variables:**

   Create a `.env` file in the root directory of the project and add your OpenAI API key:

   ```env
   OPENAI_API_KEY=your_openai_api_key_here
   ```

## Example Usage

After running the project, you can:

1. **Generate Recipes:** The model will list a few recipes for you.
2. **Select a Recipe:** Choose a recipe by entering the corresponding number.
3. **Get Detailed Instructions:** The model will provide step-by-step instructions for preparing the selected recipe.

### Sample Output

```
Here are some recipes:
1. Spaghetti Aglio e Olio
2. BBQ Pulled Pork Sandwiches
3. Chocolate Chip Cookies

Enter the number of the recipe you want more information on: 2

Ingredients:
- 2 pounds pork shoulder
- 1 cup barbecue sauce
...

Enjoy your delicious BBQ pulled pork sandwiches!
```


## License

This project is licensed under the MIT License.
```
