# Replace with lesson title

Pull these changes

Push these changes

```hurl
POST https://api.artic.edu/api/v1/artworks/search
Content-Type: application/json

{
    "q": "cats",
    "query": {
        "term": {
            "is_public_domain": true
        }
    }
}
```
{: .codeblock #jw_runnable_hurl title="Runnable Hurl Test" points="1"}

Add your content here!

[Read up here for full instructions with examples for lesson writing.](https://learn.firstdraft.com/lessons/3-how-to-write-a-lesson)

## Heading 1

Use `##` second or greater level headings (HTML `<h2>` and greater).

### Heading 1.1

Reference images from the `assets/` folder like so:

```
![](assets/example-image.png)
```

You can use the path `/assets/my-image.png` or `assets/my-image.png`, both will render in your local markdown preview; and when you connect the repository with a Learn Lesson, the assets will upload to Cloudinary and the paths will automatically be converted to a hosted URL, e.g.:

```
![](https://res.cloudinary.com/[CLOUD_NAME]/image/upload/[IMAGE_VERSION]/appdev-lessons/[REPO_NAME]/[BRANCH]/[IMAGE_NAME])
```
