
### Disclaimer

This docker image is far from being truly persistent and docker-way. It is more like a beginning to start an evolved container but it is a good way to improve it.


### Supported tags and respective Dockerfile links
I've worked to automate this image using this [Dockerfile](https://github.com/starase/puppetserver)


### Details
Image: Ubuntu 16.04 LTS
Process control system: supervisord

*Image size: ~640Mb*

### Software
* supervisor
* puppetserver
* zsh and bash (as you prefer)
* vim


### Customizations
You can customize this container as you want 


### Try it
You can pull the image and it will be up&running simply doing:

``` docker pull starase/puppetserver ```

You can start it:

```docker run -d -i -t starase/puppetserver```

Of course you can customize it. 
My recommendation is to run it with persistent volume to preserve the data simply adding -v option in puppet's configuration directory. Another thing that you can do is putting name or hostname ```--name name``` and ```--h hostname``` before the image's name




### Issues & Contributing
Before you start to code, we recommend discussing your plans through a GitHub issue, especially for more ambitious contributions. This gives other contributors a chance to point you in the right direction, give you feedback on your design, and help you find out if someone else is working on the same thing. Otherwise you feel free to drop me a line at paolo [at] starase.com


> Have fun, happy dockerizing

