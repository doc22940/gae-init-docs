{% raw %}

Same as [`flask.jsonify()`](http://flask.pocoo.org/docs/api/#flask.json.jsonify), which means it creates a Response with the JSON representation of the given arguments with an _application/json_ mimetype. The arguments to this function are the same as to the **dict** constructor.

In addition if `callback` argument is provided in the request then it will return a response with the JSONP representation.

> #### Demo
>
> Visit the following URL to check it in action: [gae-init.appspot.com/api/v1/user/?callback=foo](https://gae-init.appspot.com/api/v1/user/?callback=foo)

{% endraw %}
