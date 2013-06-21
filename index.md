---
layout: page
title: Openkas
tagline: platform for greenhouse operations management
---
{% include JB/setup %}

Openkas is a platform for developing operation management software systems 
for greenhouse horticulture.

Seamless, standards based integration with other software systems 
is a requirement 
instead of an afterthought.

### Modules

At the moment, Openkas consists of the following modules:

 * Configuration Manager
 * Production Planner, targetting (but not limited to) potted plants production

### Development

Openkas targets the Microsoft .Net platform, using C#, Asp.Net MVC4 and some Javascript.
Openkas uses many open source libraries including 
Jonathan Oliver's [Event Store](https://github.com/joliver/EventStore), 
[Rhino Service Bus](http://www.hibernatingrhinos.com/oss/rhino-service-bus) (a service bus for .Net)
and [Castle Windsor](http://www.castleproject.org)

If you'd like to contribute or use the openkas modules in your own system, 
please [contact us](mailto:info@serraict.com).
    
### Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

