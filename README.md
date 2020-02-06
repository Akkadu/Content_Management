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

## Uploading Images or Videos

### AWS S3

S3 is the best CDN for China we use, but it's not the most user friendly interface.

1. Click [here](https://console.amazonaws.cn/s3/buckets/content-management/cases/?region=cn-north-1&tab=overview) to navigate to the "content-management" folder, or open AWS and navigate to S3. Open the bucket 'content-management' then the folder 'cases'. 
2. Drag and drop your files here or click "upload"
3. When the upload is finished, click the file then copy the objectURL

### Github

You can also upload files here directly, which is simpler and serves globally just fine, but less so in China.

1. Open the folder for what section you want to add assets to
2. Drag and drop the video or image
3. Click'commit changes'
4. When it's uploaded, open it in Github then right click and 'copy image location'. It should start with 'https://raw.githubusercontent.com/'.

### Other CDN

You can add images anywhere, really. Use whatever you're comfortable with, then add it to the 'url()' tag here. Not all CDNs are created equal, though, and you'll find some CDNs like S3 will perform much better than most other tools out there.

