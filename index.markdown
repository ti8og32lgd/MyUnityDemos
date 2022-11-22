---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
<table>    <tr><th></th><th>简介</th> </tr>
{% for demo in site.demo_collection %}
<tr>
<td><a href=".{{demo.url}}">     {{ demo.title }} </a> </td>
<td> {{demo.intro}} </td>
</tr>
{% endfor %}
</table>
