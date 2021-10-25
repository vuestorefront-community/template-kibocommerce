# Kibo Commerce Vue Storefront 2 Layer0 Demo

### Requirements:
- NodeJS v14 or later
- KiboCommerce Account


To deploy your site to Layer0, you must first sign up for an account. [Sign up here for free.](https://app.layer0.co/signup?sgId=0f24fde8-77ed-40d0-8bc8-cbed15853a5e)




### Steps
* Fork the repo
* Clone your fork of the repo
    ```
    example:
    git clone https://github.com/KiboSoftware/vuestorefront-layer0-demo.git kibo-vuestorefront-layer0-demo
    cd kibo-vuestorefront-layer0-demo
    ```
* Run `yarn` to install dependencies
* sing up with 
* Define a store running environment by adding a STORE_ENV to your running project or execute the code
    ```$ echo "STORE_ENV=dev" >> .env```
* Copy config/example.json to an environment named config and update GraphQL Endpoint
    ```
    $ cp ./config/example.json ./config/dev.json
    ```
* Update clientId and sharedSecret with your respective Application Client ID and Shared secret found in your Kibo Commerce Developer Console.  Visit [Kibo documentation](https://apidocs.kibong-perf.com/?spec=graphql#auth) for more details on API authentication
* Update apiHost to point at your Kibo Commerce site.
* Run `yarn dev` to run theme with hot reload at localhost:3000. You can find other commands in `package.json`
* For production build:

```bash

# build for production and launch server
$ yarn build
$ yarn start

```
For detailed explanation on how things work, check out the [documentation](https://docs.vuestorefront.io/v2/).

## Resources

- [Vue Storefront Documentation](https://docs.vuestorefront.io/v2/)
- [kibocommerce integration Documentation](https://docs.vuestorefront.io/kibocommerce)
- [Community Chat](https://discord.vuestorefront.io)

## Support

If you have any questions about this integration we will be happy to answer them on `kibocommerce` channel on [our Discord](discord.vuestorefront.io).

## Contributors ✨

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
