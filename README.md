<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios-new.png" />

<h3 align="center">
  Challenge 07: GoFinances Web
</h3>


<p align="center">
 <img src="https://img.shields.io/static/v1?label=PRs&message=welcome&color=#FE7F2D&labelColor=#FE7F2D" alt="PRs welcome!" />

  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=#FE7F2D&labelColor=#FE7F2D">
</p>


<p align="center">
  <a href="#rocket-about-the-challenge">About the challenge</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licence">Licence</a>
</p>

## :rocket: About the challenge

This challenge is a complement of the last challenge I have done before using NodeJS and TypeScript. The link to access it will be available below.

**[GoStack_challenge-NodeJs Fundamentals](https://github.com/Fernandosilvasc/gostack-nodejs_fundamentals)**<br />
**[GoStack_challenge-Database and file upload on Node.js](https://github.com/Fernandosilvasc/gostack_challenge-typeorm-concepts)**

In this challenge was necessary create front-end part using ReactJs and Typescript!


### Features

This was requested through that challenge.

- **`List your API` transactions**: Your` Dashboard` page should be able to display a listing through a table, with the `title`,` value`, `type` and` category` field of all transactions that are registered in your API.

**Tip**: You can use the function [Intl](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/NumberFormat) to format the values. Inside the `utils` folder in the template you will find a code to help you.

- **`Display the balance of your API`**: Your `Dashboard` page, you must display the balance that is returned from your backend, containing the grand total, together with the total of entries and exits.

- **`Import CSV files`**: On your `Import` page, you must allow a file in `csv` format to be sent to your backend, which will import the transactions into your database. The csv file must follow the following [template](https://github.com/Rocketseat/bootcamp-gostack-desafios/blob/master/desafio-database-upload/assets/file.csv).

**Tip**: We have made available a component called `Upload` in the` components` folder so that you have already prepared a drag-n-drop option for uploading files. PS: If you are on windows and are experiencing any errors when trying to import CSV, change the file type inside the `components / upload / index.ts` file from` text / csv` to `.csv, application / vnd. ms-excel, text / csv`.

**Tip 2**: Use [FormData ()](https://developer.mozilla.org/pt-BR/docs/Web/API/FormData/FormData) to be able to send your file to your backend.

### Tests Specification

To complete this challenge was necessary to follow these rules:

- **`should be able to list the total balance inside the cards`**: In order for this test to pass, your application must allow cards containing the total 'income`,` outcome` and the total subtraction of income - outcome that are returned by the balance of your backend.

- **`should be able to list the transactions`**: For this test to pass, your application must allow all transactions that are returned from your backend to be listed within a table.

**Tip**: To display the values ​​in the transaction listing, transactions with type `income` must display the values ​​in the form` R$ 5,500.00`. Transactions of the outcome type must display the values ​​in the format `- R$ 5,500.00`.

- **`should be able to navigate to the import page`**: In order for this test to pass, you must allow the page change through the Header, by the button that contains the name` Import`.

**Tip**: Use the `Link` component that is exported from the` react-router-dom`, passing the `to` property that takes you to the` / import` page.

- **`should be able to upload a file`**: In order for this test to pass, you must allow a file to be uploaded via the drag-n-drop component on the` import` page, and you can view it the name of the file sent to the input.

**Tip**: We make a component called `FileList` available in the` components` folder to help you list the files that you upload via the `Upload` component, it should display the file title and size.


## :memo: Licence

This project is licensed under the MIT License - see the [LICENSE](LICENSE.md) file for more information.

---

👨🏻‍💻 - Made by Fernando Corrêa da Silva.
