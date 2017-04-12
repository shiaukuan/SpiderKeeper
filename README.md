# SpiderKeeper

A scalable admin ui for spider service 

## Features

- Manage your spiders from a dashboard. Schedule them to run automatically
- With a single click deploy the scrapy project
- Show spider running stats


Current Support spider service
- [Scrapy](https://github.com/scrapy/scrapy)

## Screenshot
![job dashboard](https://raw.githubusercontent.com/DormyMo/SpiderKeeper/master/screenshot/screenshot_1.png)
![periodic job](https://raw.githubusercontent.com/DormyMo/SpiderKeeper/master/screenshot/screenshot_2.png)
![running stats](https://raw.githubusercontent.com/DormyMo/SpiderKeeper/master/screenshot/screenshot_3.png)

## Getting Started


### Installing


```
pip install spiderkeeper
```

### Deployment

```
Usage: 

spiderkeeper [options]

Options:

  -h, --help          show this help message and exit
  --type=SERVER_TYPE  access spider server type, default:scrapyd
  --host=HOST         host, default:0.0.0.0
  --port=PORT         port, default:5000
  --server=SERVERS    servers, default:http://localhost:6800

```

## TODO
- [ ] User Authentication
- [ ] Collect & Show scrapy crawl stats
- [ ] Optimize load balancing

## Contributing

Contributions are welcomed!

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/DormyMo/SpiderKeeper/tags). 

## Authors

- *Initial work* - [DormyMo](https://github.com/DormyMo)

![Contact](https://raw.githubusercontent.com/DormyMo/SpiderKeeper/master/screenshot/qqgroup_qrcode.png)

See also the list of [contributors](https://github.com/DormyMo/SpiderKeeper/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details