# symfony-micro-demo-app
Convenient Symfony app skeleton based on MicroKernelTrait.
Made as a base for demo purposes.
Comes with separate files:
- routing.yml
- config.yml
- services.yml

and an example greeter controller.

To start run a built-in server:
```
bin/console server:run
```

And send a curl GET request to the Greeting controller:
```
curl http://localhost:8000/Marek -i
```

Enjoy!