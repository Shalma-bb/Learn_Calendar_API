# Learn-Calendar_Apis

API collections for Learn Users - CRUD operation.

## Prerequisites
Postman - latest version

## Installation
To install Postman, follow these steps:

1. Visit the [Postman website](https://www.postman.com/downloads/).
2. Download the version suitable for your platform.
3. Run the installer.

## API Enpoints

The `Api_Export.json` file contains the following APIs:

- `GET /learn/api/public/v1/calendars`: Get Calendars.
- `GET /learn/api/public/v1/calendars/items`: Returns a list of Calendar Items.
- `POST /learn/api/public/v1/calendars/items`: Create a Calendar Item.
- `GET /learn/api/public/v1/calendars/items/{calendarItemType}/{calendarItemId}`: Returns a specific Calendar item based on its Type and Id.
- `DELETE /learn/api/public/v1/calendars/items/{calendarItemType}/{calendarItemId}`: Deletes a specific Calendar item by specifing its Type and Id.
- `PATCH /learn/api/public/v1/calendars/items/{calendarItemType}/{calendarItemId}`: Updates a specific Calendar item by specifing its Type and Id.

## Usage

After importing the `Api_Export.json` file into Postman, you can use the APIs by sending requests to them. Ensure to set up the environment variables correctly:

- `$Domain_name`: Learn domain name
- `$App_key`: Your application key here
- `$App_secret`: Your application secret here
- `$Bearer_token`: Obtain the Access token from the API request '/learn/api/public/v1/oauth2/token' using the above values and replace the variable
- `$Type`: Calendar item type
- `$Id`: Calendar item Id
