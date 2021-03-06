# InstaDakwah

InstaDakwah API is app that used for manage resource used by InstaDakwah Android App.

## How to Use
1. Clone this repository
`git clone git@github.com:TeknikInformatikaUII/insta-dakwah-api.git`
2. Cd into that directory
3. Run `composer install`
4. Duplicate `.env.example` to `.env`
5. Provide the `APP_KEY` value with some random string, like:
`base64:8Y6coT87VMVS5lfWa9ZwbgpWH5YcKhWgzkR/YiJZCNs=`
6. Set the database settings according to your system's database.
7. Run `php artisan migrate --seed`
8. Run `php artisan passport:install`
9. Copy the output value from `Password grant client` to your `.env`, like:

    ```
    APP_CLIENT_ID=2
    APP_CLIENT_SECRET=eRlUMINSSgmqXOUUJIISDQPFpfGODLiPTJ6wUKXQ
    ```
10. To run the application, issue this command `php artisan serve`. By default it's use port 8000. If you like to use different port, just specify the port as an argument, like `php artisan serve --port=9000`

## Example
The example how to access the API you can see here:

[![Example](http://img.youtube.com/vi/TWvWZvobpO0/0.jpg)](http://www.youtube.com/watch?v=TWvWZvobpO0 "Example")

## Security Vulnerabilities

If you discover a security vulnerability within this API, please send an e-mail to informatics.uii.club@gmail.com. All security vulnerabilities will be promptly addressed.

## License

InstaDakwah Application is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)
