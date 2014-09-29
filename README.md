# webpagetest-private

## About

For local installation [WebPagetest Private Instance](https://github.com/WPO-Foundation/webpagetest)

## Requirements

* [Vagrant](http://vagrantup.com/)
* [VirtualBox](http://virtualbox.org) or [Parallels Desktop for Mac](http://www.parallels.com/products/desktop/)
* [Ansible](http://ansible.com/) for provisioning

## Usage

### Clone repository

```sh
$ git clone https://github.com/bayandin/webpagetest-private.git
```

### Boot vagrant

```sh
$ vagrant up
```

Or, if you have installed [Parallels Desktop for Mac](http://www.parallels.com/products/desktop/) you can use it as vagrant provider

```sh
$ vagrant plugin install vagrant-parallels
$ vagrant up --provider=parallels
```

### Browse `http://192.168.33.33:8080`

## License

MIT
