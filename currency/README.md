# 🐣 Currency 🐣


<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## :mag: Overview

Currency offers a great solution to convert currency. Enter an amount of money, the current and target currency and obtain the converted amount.
By default, the program converts USD into Bitcoins.


## :eyes: How use it

	Run the cli.js file and specify the amount, the current and target currency.

	If the amount money isn't mentionned, currency will return the value of one unit of currency.

	If you specify only one currency, the program will convert this amount of money into Bitcoins.

:heavy_exclamation_mark: Some currency isn't available for conversion.

The library contains 2 parts:
	cli.js manages the view parts and index.js manages the model part


## :package: Dependancies
Currency uses severals library

	Axios deals the HTTP request
	Ora  is used to display the state of progress
	Nock HTTP server mocking and expectations library for Node.js

