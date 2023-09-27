# How to preview documentation changes locally?

The documentation can be hosted on a local webserver via httpd.

You can run it with the following command, note that it requires docker:

```shell
./start-preview.sh
```

Then you can open [localhost:8080](http://localhost:8080) on your browser and browse the documentation.

To kill the process, just type ctrl + c