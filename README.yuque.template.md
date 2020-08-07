<h2>Hi, 我是世界</h2>

<h4> Latest Blog Posts: </h4>
{{#each record}}
  - [{{title}} ( {{short created_at "MM-dd"}} · {{math likes_count "*" 7}} 颗稻谷)](https://yuque.com/{{@root.namespace}}/{{slug}})
{{/each}}


<p align="right"><a href="https://www.yuque.com/chenzesam">➡️ More blog posts</a></p>
