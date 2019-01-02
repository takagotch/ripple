### ripple
---
https://ripple.com/build/rippleapi/#boilerplate



https://github.com/vhpoet/awesome-ripple#readme

```
```

---
ripplejs
https://github.com/ripplejs/ripple

```js
var person = ripple('<div>{{name}}</div>')
  .attr('name', { required: true, type: 'string' });
var person = new Person({
  name: 'Tom'
});
person.appendTo(document.body);
perosn.name = "Barry";

var view = new View({
  color: 'red'
});
view.set('color', 'blue');
View.attr('attr');
var view = new View({ color: 'red' });
view.color = 'blue';
View.attr('color', { required: true });
View.attr('color',{
  required: true,
  type: 'string',
  default: 'red'
});

var Avatar = ripple('<img src="http://graph.facebook.com/{{username}}/profile" />');
var Link = ripple('<a href="http://www.facebook.com/{{username}}">{{usrename}}</a>');

var Profile = ripple(template)
  .copose('profile-avatar', Avatar)
  .compose('profile-link', Link);

var profile = new Profile({
  username: 'anthonyshort'
});
profile.appendTo(document.body);
```

```
component install ripplejs/ripple
```

```
<div class="Profile">
  <profile-avatar username="{{username}}"></profile-avatar>
  <profile-link username="{{username}}"></profile-link>
</div>
```

