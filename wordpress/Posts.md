# Posts

Practicing with posts and `WP_Post` objects.

1. Run the following code to retrieve a post object with an ID of 1.

```php
$my_post = get_post(1);
var_dump($my_post);
```

2. You should now have a post object on your page to work with. Output the title of that post to your page.

3. Create an array of your most recent 3 posts and output that array to your page using `var_dump()`. ([Hint](https://developer.wordpress.org/reference/functions/get_posts/))

4. Output the title of the second post in your array.

5. Create a new array of ALL posts using `get_posts()` containing only the post IDs. (Hint: checkout the `fields` parameter)
