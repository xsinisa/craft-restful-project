<p align="center"><a href="https://craftcms.com/" target="_blank"><img width="312" height="90" src="https://craftcms.com/craftcms.svg" alt="Craft CMS"></a></p>

## About Craft CMS

Craft is a content-first CMS that aims to make life enjoyable for developers and content managers alike. It is optimized for bespoke web and application development, offering developers a clean slate to build out exactly what they want, rather than wrestling with a theme.

Learn more about Craft at [craftcms.com](https://craftcms.com).

## How to Install Craft 3

See the Craft 3 documentation for [installation](https://docs.craftcms.com/v3/installation.html) and [updating](https://docs.craftcms.com/v3/updating.html) instructions.

## Resources

#### Official Resources
- [Craft 3 Documentation](https://docs.craftcms.com/v3/)
- [Craft 3 Class Reference](https://docs.craftcms.com/api/v3/)
- [Craft 3 Plugins](https://plugins.craftcms.com)
- [Demo site](https://demo.craftcms.com/)
- [Craft Slack](https://craftcms.com/community#slack)
- [Craft CMS Stack Exchange](http://craftcms.stackexchange.com/)

#### Community Resources
- [Mijingo](https://mijingo.com/craft) – Video courses and other learning resources
- [Envato Tuts+](https://webdesign.tutsplus.com/categories/craft-cms/courses) – Video courses
- [Straight Up Craft](http://straightupcraft.com/) – Articles, tutorials, and more
- [pluginfactory.io](https://pluginfactory.io/) – Craft plugin scaffold generator


---

## API Endpoint Examples
[![Run in Postman](https://run.pstmn.io/button.svg)](https://documenter.getpostman.com/view/293467/SVtYRmTE)

## Getting Started

Start Docker containers, and run Craft CMS setup.
```
make craft-setup

-or (for those without Make)-

docker-compose -f docker-compose.yml exec web sh -c "php craft setup"
```
*For db settings use: mysql, db, 3306, craft, craft, craft, NO-TABLE-PREFIX*


Install the Restful plugin

```
make install/plugin restful

-or (for those without Make)-

docker-compose -f docker-compose.yml exec web sh -c "php craft install/plugin restful"
```

Preform a GET request: https://localhost/api/v1/users 
