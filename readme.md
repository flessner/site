# Home

**👋 Welcome to this new Website!**

Resources:
- [[de]]
- [[en]]

Here are some articles:
<ul>
    {% for post in site.posts %}
        <li> <a href="{{ post.url | absolute_url | remove: '.html' }}">{{ post.title }}</a> - {{ post.date | date_to_string }}</li>
    {% endfor %}
</ul>

[//begin]: # "Autogenerated link references for markdown compatibility"
[de]: de.md "Wissensbasis"
[en]: en.md "Knowledge Base"
[//end]: # "Autogenerated link references"