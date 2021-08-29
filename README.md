# Budget Tracker

![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg)

## Link(s)

* [GitHub Repository](https://github.com/emangano2816/budget_tracker)
* [Application](https://tranquil-river-79971.herokuapp.com/)

## User Story

```md
AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling
```

## Summary of Application Functionality
The Budget Tracker application is able to be downloaded as an application to the user's desktop, phone, or tablet and can be used while offline.  

A user is able to track deposits and withdraws using the application.  To track a deposit, the user provides a description, the amount of the transacation, and then hits 'Add Funds'.  To track a withdraw from the account, the user provides a description, the amount of the transaction, and then hits 'Subtract Funds'.  Once the 'Add Funds' or 'Subtract Funds' button is hit, the transaction is added to the list of transactions and the graph updates accordingly.

The application can also handle offline activity.  While offline, the transactions are stored in an offline database.  When the application comes back online the transactions are added to the online database and the offline database is cleared out for future transactions.
    
## Application Demo

https://user-images.githubusercontent.com/79860046/131256144-3a7f9850-f275-488f-833f-9b5324cc87a4.mp4

## Tecnhologies Used
1. NodeJS (packages: express, mongoose, morgan, compression, lite-server)
2. MongoDB, MongoDB Atlas
3. Robo 3T
4. Heroku

## Installation

No installation required.

## License

This application is covered under the MIT license.
