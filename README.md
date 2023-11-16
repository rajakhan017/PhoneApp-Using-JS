# PhoneApp-Using-JS

we can enjoy this app from here :[https://rajakhan017.github.io/PhoneApp-Using-JS/]
This is a simple web application that allows users to search for phones using an API. The application displays phone details and provides a "Show Details" button for each phone.
## Getting Started
1. Clone the repository.
2. Open the `index.html` file in a web browser.
## Usage
- Enter a search term in the search field and press Enter or click the search button.
- The application will display phone cards with basic information.
- Click the "Show Details" button to view more details about a specific phone.
## Functions
### `searchHandler(isShowAll)`
- Initiates a phone search based on the entered text.
- If `isShowAll` is true, it shows all available phones.
### `loading(isLoading)`
- Displays or hides a loading spinner based on the `isLoading` parameter.
### `loadPhone(searchText, isShowAll)`
- Fetches phone data from the API based on the provided search text.
- Displays phones using `displayPhones` function.
### `displayPhones(phones, isShowAll)`
- Renders phone cards with basic information.
- If `isShowAll` is false, it displays only the first 12 phones.
### `showBtn()`
- Calls `searchHandler` with `true` to show all available phones.
### `showDetailsHandler(id)`
- Fetches detailed information about a specific phone using the phone's `id`.
- Calls `showPhoneDetails` to display the details.
### `showPhoneDetails(details)`
- Displays detailed information about a phone, including its image, name, brand, main features, and release date.
## API
- Uses the [Programming Hero API](https://openapi.programming-hero.com/api/phones) to fetch phone data.
## Acknowledgments
- This project is a simple demonstration of integrating API data into a web application.
has context menu
## Screenshot 1
![image](https://github.com/rajakhan017/PhoneApp-Using-JS/assets/135150598/043208b4-618c-4de8-9809-07d8d2bda0b9)
## Screenshot 2
![image](https://github.com/rajakhan017/PhoneApp-Using-JS/assets/135150598/1e513250-c96c-4d81-91a2-46e8bf2d8a7f)

