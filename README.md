# Content_Management

Add your content to Akkadu applications here! This is an easy, efficient, and relatively simple way for us to handle our static content without having to edit code.

## How It Works

Each folder contains content relating to a component. You can add internationalized .json files in multiple languages flagged with `file-en.json`, `file-cn.json`, etc. You can also add images and videos, but for delivery speed and performance, it is better to upload to [AWS S3](https://console.amazonaws.cn/s3/buckets/content-management/?region=cn-north-1&tab=overview). The content you create here can be accessed by all applications to be built in or delivered directly to the client.

### Adding a New File

You can upload a folder of files, or create a new file directly in Github.

### Editing Files

To edit a file, open it in Github and click the pencil on the top right corner on the file. If it's a `*.json` file, be sure to [make sure it's formatted correctly](https://jsonlint.com/?code=).

### Reverting Changes

If something goes wrong, you can revert your changes in Github to quickly undo any mistakes or whatever before figuring out what went wrong.
