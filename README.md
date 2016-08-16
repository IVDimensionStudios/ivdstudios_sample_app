# IVth Dimension Studios sample application

This is the sample application for
[*IVth Dimension Studios: Gaming Studios & Film Production House*](http://www.ivdstudios.com/)
by [Abhimanyu Aryan](https://www.facebook.com/iAbhimanyuAryan).

## Licence
All source code of this app is available jointly under the MIT Licence. See [LICENCE.md](Licence.md) for details.

## Getting started

To get started with the app, clone the repo and then install the needed gems:

```
$ bundle install --without production
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails server
```