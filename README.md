# hashmakr
Quick & dirty tool to hash all passwords in a database table.

## Installation
1. Clone repository: `git clone https://...`
2. Switch to directory: `cd hashmakr-main`
3. Install dependencies: `composer install`
4. Setup (see next section)

## Setup
1. Rename .env-example to .env.
2. Change database connection details in .env file.
2. If your database table is called different from `users`, your users do not have an `id` or the `password` column is not called `password`, you will need to adjust these settings in `hashmakr`-file.

## Usage
**Please backup your database before proceeding!**

After setup, simply run `php hashmakr` in the Terminal.