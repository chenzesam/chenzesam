<h2>Hi, 我是世界</h2>

<h4> Latest Blog Posts: </h4>

{{#each record}}
  - [{{title}}](https://yuque.com/{{@root.namespace}}/{{slug}})
{{/each}}

<p><a href="https://www.yuque.com/chenzesam">😎 More blog posts</a></p>
