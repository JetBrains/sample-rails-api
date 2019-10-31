# SIMPLE RAILS REST API

This application can be used to test REST API using the [RubyMine HTTP client](https://www.jetbrains.com/help/ruby/http-client-in-product-code-editor.html).

## Prerequisites
1. Install MySQL.
2. Open this project in RubyMine.
2. Open [database.yml](config/database.yml) and provide your MySQL credentials.
3. Install dependencies:
    ```bash
    $ bundle install
    ```
4. Run `rake db:create`, then `rake:db:migrate`.
5. Run `rake db:seed` to supply the created database with data.
6. Run a server:
    ```bash
    $ rails s
    ```

## Work with HTTP client
To try the HTTP client in action, go to the [http-client-test.http](http-client-test.http) file and run sample requests. 
You can learn more from the [HTTP client](https://www.jetbrains.com/help/ruby/http-client-in-product-code-editor.html) topic.