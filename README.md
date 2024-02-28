
💎
</p>
<p align="center">
<sup>
<b>E-Commerce website i made , it needs a little bit more work but is almost ready . It is also mobile friendly . </b>
</sup>
</p>

---


#### Warning ( I have disabled Google Cloud Console so some features of the application like ( image loading will not work ) but the code is there :)

## Features
- **App**
  - User Authentication using  (BCrypt gem)
  - ADMIN and User roles 
  - Products icons saved on Google Cloud or Amazon Cloud
  - Email Account Activation
  - Users can follow other users
  - Twitter like feed mechenism for followers
  - Beautiful Search Bars
  - Beautiful Paginations
  - Users can post articles
  - Proceed products to cart
  - Make Orders
  - Edit , destroy orders (Admin)
- _**Working on it**_
  - - Implement State Machine
  - - Use more Ajax requests
  - - Implementing tickets
  - - Implementing shipping

Images from version V1.0


## Getting started

To get started with the app, clone the repo and then install the needed gems:

```
$ bundle install --without production
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly: THE TESTS FAIL (Because i didn't corrected them all loool! )

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails server
```
