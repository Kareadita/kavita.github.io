---
title: Posts
---

If you want to show the latest (blog) posts on your website, you can use the posts brick. This requires you to use the following markup:

```
---
title: Page title
---
{{</* brick_posts */>}}

{{</* breadcrumbs */>}}

# Blog posts

Here you will find releases and normal posts from Kavita and all it's softwares

{{</* /brick_posts */>}}
```

<!--{{< brick_posts >}}{{< /brick_posts >}}-->

Note that this requires you to have a directory called 'posts' in 'content'. In this folder you need to store your posts as markdown files.